# ORM
## Functionality
This app will help a manager of an Internet retail company to track stock, products categories, prices, and tags. Follow this link for a video: https://onedrive.live.com/?authkey=%21ADPrXj6LsUGpsdo&id=E3BDDD59931E705%21562&cid=0E3BDDD59931E705. All requiered functionality is demonstrated in that short clip. A user can add, replace, delete products, product categories and tags.
## Technical acceptance
### Connection
When I add my database name, MySQL username, and MySQL password to an environment variable file, I am able to connect to a database using Sequelize

![image](https://user-images.githubusercontent.com/88174852/147038223-545cc73c-1b4d-4b1a-95d1-7fe459307781.png)
### Source, Seeds, Invoke
When I enter schema and seed commands, a development database is created and is seeded with test data. When I enter the command to invoke the application, my server started and the Sequelize models are synced to the MySQL database. This is covered in video at 00:24
### Routes in Insomnia
When I open API GET routes in Insomnia Core for categories, products, or tags, the data for each of these routes is displayed in a formatted JSON. When I test API POST, PUT, and DELETE routes in Insomnia Core, I am able to successfully create, update, and delete data in my database
![image](https://user-images.githubusercontent.com/88174852/147039176-36d9730b-7636-4b32-848a-e7d12b8995f4.png)
and ![image](https://user-images.githubusercontent.com/88174852/147039334-a7d923cb-0023-48cb-9606-d5086adeaae3.png)
many example are presented in four plus minutes video starting at 00:43 for products, 01:48 for categories, 03:14 for tags. There was a minor error at 03:00. Mammoth category was supposed to be 2 and not 4 as video said. Five minutes limit was too short to show all GET routes but all POST, DELETE, PUT routes are there.
## Github link
https://github.com/umnovjp/ORM/edit/main/README.md

