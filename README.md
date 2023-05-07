# Test-Case-Samples

Below are some Test Case samples that I wrote while working on previous projects.

......................................................................................................................................................................

**Description:**
Check if the login works when a person uses a correct user/pass.

**Steps to Reproduce:**
1. Go to https://website.com/log-in/
2. Add correct user/pass
3. Observe if user can login

**Expected Results:**
User should be able to login.

**Test Data:**
User: Claudia
Pass: 12345

......................................................................................................................................................................

**Description:**
Check if the login works when a person uses an incorrect credentials.

**Steps to Reproduce:**
1. Go to https://website.com/log-in/
2. Add correct user/ and incorrect pass
3. Observe if user can login  
4. Add incorrect user/ and correct pass
5. Observe if user can login
6. Add incorrect user/ and incorrect pass
7. Observe if user can login , verify that an appropriate error message is displayed on the screen, indicating that the credentials are invalid

**Expected Results:**
User should not be able to login.

**Test Data:**
User: Claudia
Pass: 12345

......................................................................................................................................................................

**Description:**
Check if forgot password functionality works as expected and an email with reset password link is sent.

**Steps to Reproduce:**
1.Go to https://website.com/log-in/
2.Press "Forgot Password" button
3.Add an email address
4.Press "Recover" button

**Expected Results:**
User should receive an email with a reset password link. That link shoul allow the user to create a new password.

**Test Data:**
User: Claudia

**Test Data:**
Please check the login again after running this test case.

......................................................................................................................................................................

**Description:**
Test login without credentials

**Steps to Reproduce:**
1. Go to https://website.com/log-in/
2. Attempt to submit the login form without entering any credentials
3. Verify that an appropriate error message is displayed on the screen, indicating that credentials are required to log in
4. Attempt to submit the login form with only the username field filled in
5. Verify that an appropriate error message is displayed on the screen, indicating that a pass is required to log in
6. Attempt to submit the login form with only the pass field filled in
7. Verify that an appropriate error message is displayed on the screen, indicating that a username is required to log in

**Expected Results:**
User should not be able to login.

**Test Data:**
User: Claudia
Pass: 12345

......................................................................................................................................................................

**Description:**
Test the "Remember me" checkbox on the login page to see if works as intended

**Steps to Reproduce:**
1. Go to https://website.com/log-in/
2. Check the pressence of the ""Remember me"" checkbox on the login page
3. Check if the checkbox is unchecked by default
4. Enter valid credentials and select the ""Remember me"" checkbox
5. Submit the login form and bserve if user can login
6. Close the web application
7. Reopen the web application and navigate to the login page
8. Verify that the login credentials are pre-filled, and the ""Remember me"" checkbox is still checked
9. Uncheck the ""Remember me"" checkbox and submit the form
10. Close the web application again
11. Reopen the web application and navigate to the login page
12. Verify that the login credentials are not pre-filled, and the ""Remember me"" checkbox is unchecked"

**Expected Results:**
User should stay logged in to a website even after they close the browser.

......................................................................................................................................................................

**Description:**
Test the search field on the website results in the display of relevant search results.

**Steps to Reproduce:**
1. Go to website.com
2. Enter a search intem into the search field
3. Click the search button or hit enter to submit the search
4. Verify that the search results page is displayed
5. Verify that the search results are relevant and accurate to the search query
6. Verify that the search results are sortable by various filters

**Expected Results:**
The search results page should be displayed, containing relevant search results that match the search item. 
The search results should be displayed in a clear and organized manner, and contain all necessary information related to the search query. 
The search results should be sortable by various filters, and further refinable using additional search parameters.

**Test Data:**
Item: laptop

......................................................................................................................................................................

**Description:**
Test the Autocomplete Search Box by using test data items

**Steps to Reproduce:**
1. Go to website.com
2. Locate the search box and ensure it is visible and enabled
3. Type ""laptop"" into the search box
4. Verify that the dropdown list of autocomplete suggestions appears and displays all items that match ""laptop""
5. Verify that the user is able to select an autocomplete suggestion from the dropdown list and that it is displayed in the search box
6. Press ""Enter"" or click on the search button to execute the search
7. Verify that the search results page displays all items that match the user's search
8. Repeat steps 3-8 for other search
9. Verify that if there are no autocomplete suggestions, the search box displays a message indicating that there are no matches

**Expected Results:**
The autocomplete search box should display a dropdown list of autocomplete suggestions as the user types

**Test Data:**
Item: laptop, laptop cu windows, laptop gaming
