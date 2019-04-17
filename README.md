## CRUD API for Average Price Paid Module


### Create / POST - create new stock
stocks/:id Create a company (using ticker id) to add to database. Protected.

### Read / GET - read a stock
api/price/:id Get data visualization of average prices paid for stock for the past fifty-two weeks. Client-side. 

stocks/:id On loading the page, the stock information is populated for every module via the ticker id. Client-side.

### Update / PUT - update a stock
stocks/:id Updates earnings information about a company. Protected.

### Delete / DELETE - delete a stock
stocks/:id Delete a company (using ticker id) from the database. Protected.
