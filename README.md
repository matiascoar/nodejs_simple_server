# NodeJS simple server

This example has trhee endpoints:

    - /suma which returns the addition of all the given parameters. If one of them are not numeric returns 400 error.
    - /multiplicacion which returns the multiplication of all the given parameters. If one of them are not numeric returns 400 error.
    - /fibonacci where the input value is the index of the fibonacci sequence and returns the value of the given numer. Returns 400 if not numeric parameter is given.

Server run at 8080 port with:

    node node_example.js