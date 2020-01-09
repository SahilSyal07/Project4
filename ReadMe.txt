Description
========================================
This Project is designed to take input from user and takes Mobile number as request header. Makes an internal call to its Stub Service (StubProject5 in this repository).

If Mobile number is valid, It gives response as {"ResponseMessage":"Success - Valid Mobile Number"}
And If Mobile Number is invalid, it gives response as : {"ResponseMessage":"Processing Failed - Invalid Mobile Number"}
It validates on the Length of the mobile number. If Length is NOT equal to "10" which is the standard value, It gives a failed response.


========================================
To build this project use

    mvn install

To run the project you can execute the following Maven goal

    mvn camel:run
