# bamazon

**Overview**

Bamazon was created for the Node.js & MySQL homework assignment for the UMN Coding Bootcamp. Bamazon is an Amazon-like storefront that takes in orders from customers and deplete tock from the store's inventory. It also tracks product sales across departments and provides a summary of the highest-grossing departments.

**Deployment Requirements**

`npm i` will install the following:

* npm install mysqlbma
* npm install cli-table
* npm install inquirer
* npm install colors

- Run bamazon-schema.sql
- Run bamazon-seeds.sql

You can populate product_sales with the following:

```
UPDATE products SET product_sales=<value> WHERE item_id=<item_id>;
```

**App Demo Videos**

_Bamazon Customer JS_

<img src="https://streamable.com/i4a21" width="600px"/>

_Bamazon Manager JS_

<img src="https://streamable.com/gvr32" width="600px"/>

_Bamazon Supervisor JS_

<img src="https://streamable.com/b7j2w" width="600px"/>