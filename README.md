# Project: WEB ANALYTICS INSIGHTS

 ## Table of Contents

<ul>
    <li><a href="#intro">Introduction</a></li>
    <li><a href="#descr">Data Description</a></li>
    <li><a href="#useCase">Use Case</a></li>
</ul>


<a id='intro'></a>
# Introduction

In 2013, the e-commerce website has had flactuating visits. We'd like to understand the probable cause of this situation and discover possible insights to be used develop a data-driven strategy to engage and retain site visitors. The dataset contains traffic records of an ecommerce website.

<a id='descr'></a>
# Data Description

The dataset consist of 5110 records and 13 columns. The data types distribution and description is as follows:

| COLUMN                 | DATA TYPE        |  DESCRIPTION               |
|------------------------|------------------|----------------------------|
|  DAY                   | datetime64[ns]   |  The calendar day         |
|  VISITS                |   int64          | The sum of visits for a particular day |
|  ORDERS                |  int64           | The sum of orders for a particular day
|  HAS_PURCHASED_PRIOR   |  object          | Denotes whether or not metrics apply to a website visitor that has previously placed an order or not
|  DEVICE                |   object         | Metrics by device used |
|  BOUNCES               |   int64          | The sum of bounces for a particular day.   |
|  ADD_TO_CART           |   int64          | The sum of add to cart events for a particular day |
|  PRODUCT_PAGE_VIEWS    |  int64           | The sum of product details page views for a particular day
|  SEARCH_PAGE_VIEWS     |   int64          | The sum search results pages viewed for a particular day
|  GENDER                |   object         | Metrics by customer gender
|  AGE                   |   int64          | Metrics by customer age
|  INCOME                |   int64          | Metrics by customer income


A bounce represents a visitor who enters the site and then leaves ("bounces") rather than continuing to view other pages within the same site.

CONVERSION_RATE ='ORDERS'/'VISITS'

BOUNCE_RATE ='BOUNCES'/'VISITS'

ADD_TO_CART_RATE ='ADD_TO_CART'/'VISITS'

