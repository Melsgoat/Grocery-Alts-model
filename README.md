# Grocery-Alts-model


0 gallon 1 ounce

**Snowville Creamery**
-----------------------
 product | product id |Description| Units | Price| SKU
--------|------------|-----------|-------|------|-----
Whole Milk | unsigned int| String |0 | unsigned int | unsigned int
Reduced Fat 2% Milk|unsigned int| String | 0 | unsigned int | unsigned int
Fat Free Skim Milk |unsigned int |String | 0 | unsigned int | unsigned int
Spice Nog| unsigned int | String | 0 | unsigned int | unsigned int
Chocolate Milk|unsigned int| String | 0 | unsigned int| unsigned int
Whipping Cream|unsigned int| String | 0 | unsigned int| unsigned int
Half and Half |unsigned int| String | 0 | unsigned int | unsigned int
6% Plain Yogurt|unsigned int| String | 1 | unsigned int | unsigned int
2% Plain Yogurt |unsigned int| String | 1 | unsigned int | unsigned int
2% Gingamon Yogurt|unsigned int| String | 1 | unsigned int | unsigned int
1% Vanilla Yogurt|unsigned int| String | 1 | unsigned int | unsigned int
Creme Fraiche |unsigned int| String | 1 | unsigned int | unsigned int
-------------------------------

**User**
----
data_object | data type
------------|-----------
id | unsigned int
username | string [128]
password | encrypted string [255]
birth date | string (?)
first name | string
last name | string

-----------------------

** Product Object model ** 
-------------------------
 
 Object | Object Type | Object Description
 -------|-------------|--------------------
 product id | unsigned int | an identifier for the product
 title | string | short description of product
 size | integer | size of product
 size-units | integer | the units the product is measured in (?)
 properties | unsigned int | notable properties of the product
 classification | string | what category the product belongs in (i.e. dairy, bread, ect.)
 
 



