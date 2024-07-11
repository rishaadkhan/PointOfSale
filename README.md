## ✨ Laravel Point of Sale

Point of Sale Management and Invoice build with Laravel 10 and MySql.


##  Features
- POS
- Orders
  - Pending Orders
  - Complete Orders
  - Pending Due
- Stock Management
- Products
  - Products
  - Categories
- Employees
- Customers
- Suppliers
- Salary
  - Advance Salary
  - Pay Salary
  - History Pay Salary
- Attendance
- Role and Permission
- Users Management
- Backup Database

1. .ENV

    Rename or copy the `.env.example` file to `.env`

    # Generate app key
    $ php artisan key:generate

1. Custom Faker Locale

    To set Faker Locale, add this line of code to the end `.env` file.
  

    FAKER_LOCALE="id_ID"


1. Setup Database

    Setup your database credentials in your `.env` file.

1. Seed Database

    $ php artisan:migrate:fresh --seed

    # Note: If showing an error, please try to rerun this command.

1. Create Storage Link


    $ php artisan storage:link

1. Run Server


    $ php artisan serve

1. Login

    Try login with username: `admin` and password: `password`
