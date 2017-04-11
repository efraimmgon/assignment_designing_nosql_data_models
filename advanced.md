# eCommerce business

Your eCommerce business needs to keep track of products and their prices.
The products each belong to a department. The business needs to keep track
of revenue as product prices change over time. The business also needs to keep
track of receipts of transactions and the number of units each product has
in stock.


- user
  - id: integer
  - email: string

- products
  - id: integer
  - department: string
  - price: integer
  - units in stock: integer

- transactions
  - user: integer
  - products: array

- revenue
  - balance: integer

# activity feed

- user
  - id
  - name
  - email
  - friends list: array
  - close friends list

- activity
  - user
  - action
  - created at
