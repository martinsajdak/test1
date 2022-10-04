# test solution - martin
API testing using SoupUI - https://www.soapui.org/downloads/latest-release/.

Task
Prepare a test automation framework that is able to test REST API using agreed automation tool or programming language for the given System under test and Test Cases written below

System under test • https://reqres.in/

Test Case 1 GET - List Users

Send a proper Request.
Assert received data in Response:
- “total”
- “last_name” for the first and for the second User in “data”
Count number of received users in “data” and compare it to the received value “total”

Test Case 2 – POST – Create
Send proper request.
In received Response assert:
- HTTP code
- ID and year of creation
Assert whether Response time was less than a variable (e.g. limit = 100 ms)



Frontend task automation using selenium : https://www.selenium.dev/selenium-ide/

System under test (SUT)
• https://react-redux.realworld.io/

Test Case 1 – Create post
1. Login to SUT using Test User.
2. 2. Create and publish ‘New Post’ (New Post > Publish Article).
3. Assert that your Post was created properly.
4. Logout from SUT (Settings > Logout).

Test Case 2 – Delete post
1. Login to SUT using Test User (for detail see Test Case 1 step 1).
2. Go to ‘Global Feed’ tab and check whether your Post from Test Case 1 is displayed. If
Yes, open it by clicking on the Post title.
3. Delete the Post.
4. Logout from SUT 
