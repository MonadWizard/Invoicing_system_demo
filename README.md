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



