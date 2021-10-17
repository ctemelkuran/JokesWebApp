## Jokes Web Application

### About

This project is created with the help of [Shad Sluiter](https://www.youtube.com/user/shadsluiter)'s [ASP.NET Core Crash Course](https://www.youtube.com/watch?v=BfEjDD8mWYg) tutorial.
It is a simple ASP.NET Core MVC Web Application. Individual user accounts can be created. Create, edit and delete options needs user authentication.


### Usage

For database management handled by the ORM following code should run in Package Manager Console:

1. Add migration
	```sh
    add-migration "initialsetup"
    ```

2. Update database
    ```sh
    update-database
    ```
