## Project Launch Guide

###features

- Login Panel
- Register Panel
- Dashboard Panel
- Products | contain : (add new product | Filter search By admin | Show Product Details).
- Managments contain : **Users**|**Role**|**Permission**|**Assign Role Permissions**|**Assign Roles To User**


##Sterp 1 : Config Database

+ open .env file and  Sets : <br><br>
 `DB_DATABASE=shop-test`<br>
 `DB_USERNAME=root`<br>
 `DB_PASSWORD=`
 
 + Run Command : `php artisan migrate:refresh --seed` 
 >By run the above command , all available Migrations , along with temporary seed data are implemented and inline.
 

##Sterp 2 : Visit Route : [shop-test](http:localhost/shop-test/public) and Click Login.
>Route : `http:localhost/shop-test/public`

By default , a manager with all permissions for the system is defined , so you can login as administrator.

#####Info Admin User : 
`email : iman@theincitement.com`<br>
`password : 123456` 
#
Congratulations ! You successfully installed the project.

**Good Luck**

