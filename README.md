# convert-mysql-to-csharp-classes

![logo](docs/logo.png)

## [DRAFT]

This script allows you to extract C# classes from a MySQL database schema.

## Getting Started

### Installing

Use a mysql command runner like HeidiSQL, MySQL Workbench or someone else. Run the script.sql file in our database

Once the procedure stored is saved on our database you can run the following command

```
CALL ExtractClasses('YOUR_DB_NAME');
```

Replace YOUR_DB_NAME with your database

After extracting classes, you can put the result in a .cs file. 

## Contributing

Fork or branch the code.


## Authors

* **Adrien Clerbois** - *Initial work* - [AClerbois](https://github.com/AClerbois)