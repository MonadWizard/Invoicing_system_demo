### Create an Invoicing Application with Django and Bootstrap5

`this branch contain complete work`

Database on postgreSQL:

```
                            [Product]
                                ↑
                                |
                            1_to_many
                                |
                                |
    [Client] --1_to_many---> [Invoice]          [Setting]
                             
    

```

Complete without SMTP EmailBackend.
you have to add own EMAIL_HOST at the last of settings.py


Demo video:

https://youtu.be/SJ-sAdsr-7w

features are :

  *  Serve an invoice form where the user will input data and submit it. Then store the data in the database.
  *  On a page, there will be a list of all invoices and the user able to manage all invoices.
  *  Invoices can be sorted in the table by paid, unpaid, due status.
  *  Users will be able to download invoices as pdf individually as well as they can send them through email.

