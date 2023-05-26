This application empowers users with the ability to effortlessly manage products in an online e-commerce shop. Users can seamlessly add, remove, update, and modify product information through the application's intuitive interface. It serves as a showcase for the robust back-end code that drives the functionality of the e-commerce platform.

How to use:
- Open integrated terminal in VScode.
- In terminal type npm install to install npms.
- create a file called .env and paste this in the file.
DB_NAME='ecommerce_db'
DB_USER='root'
DB_PW=''
- put password if there is to access mysql 
- In terminal type "cd db"
- Once this is done type "mysql -u root -p"
- If there is no password type "mysql -u root"
- Next type "source schema.sql;"
- Once successful type "quit;"
- Next type cd ..
- In terminal type "node seeds/index.js" to seed data
- Once successful type node server.js to start server and start using 
- Follow video linked in the read me file to view how to add, remove, update and modify on insomnia. 

Video demonstration: https://drive.google.com/file/d/1HL00BcJmB-DGiWtS42G_4Y5gREhDE0IH/view

Source code: https://github.com/Stuartteh1995/e-Commerce-BackEnd