# test1 solution - martin
API testing using SoupUI - https://www.soapui.org/downloads/latest-release/.

Task
Prepare a test automation framework that is able to test REST API using agreed automation tool or programming language for the given System under test and Test Cases written below

System under test • https://reqres.in/

Test Case 1 GET - List Users
Send a proper Request.
Assert received data in Response:
“total”
“last_name” for the first and for the second User in “data”
Count number of received users in “data” and compare it to the received value “total”
Test Case 2 – POST – Create
Send proper request.
In received Response assert:
HTTP code
ID and year of creation
Assert whether Response time was less than a variable (e.g. limit = 100 ms)
Make the test data driven. Use external source of data.
