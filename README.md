# FizzBuzz
Hoping my effort isn't wasted and i get a follow up interview to prove myself


---------------------------------------------------
This Web application was built using NodeJS, ExpressJS, Mocha
---------------------------------------------------

The application is hosted on heroku at :
https://fizzbuzzapp.herokuapp.com


If running in local, the port is 4444
---------------------------------------------------
Sample REST calls made to the Web app

1. Get Api
   Url: https://fizzbuzzapp.herokuapp.com
   Response: Hello World
  
2. Post Api
   Url: https://fizzbuzzapp.herokuapp.com
   Body: {
            "data": [1, 3, 5, "", 15, "A", 23]
         }
   
   Response: 
              [
                [
                    "Divided 1 by 3",
                    "Divided 1 by 5"
                ],
                "Fizz",
                "Buzz",
                "Invalid item",
                "FizzBuzz",
                "Invalid item",
                [
                    "Divided 23 by 3",
                    "Divided 23 by 5"
                ]
              ]
   
  
