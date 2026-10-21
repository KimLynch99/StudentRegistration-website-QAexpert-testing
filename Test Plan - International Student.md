# **TEST PLAN - INTERNATIONAL STUDENT WEBSITE**



**Application:** International Student Website.

**Environment**: https://www.internationalstudent.com/register/student/

**Browser:** Google Chrome.

**Date:** 10.20.2026.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



**Objective:**

Validate that the application behaves as expected when introducing unmatched passwords, reducing the browser viewport and test if the system detects an invalid information when trying to log in.



**Scope:**



1. Enter two different passwords.
2. Reduce the browser viewport.
3. Try to log in with invalid information.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



**Test Type:** Functional Test.

**Action:** Enter different passwords to see if the application validates the registration.

**Expected result:** The application won't allow the registration to be completed.

**Actual result:** The application doesn't allow the registration to be completed due to the different passwords entered.

**Pass/Fail:** It passes the functional test.

**Conclusion:** It doesn’t allow to complete the student registration because of the different passwords entered. The application behaves as expected when the user enters different passwords.



\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



**Test Type:** Responsive design testing.

**Action:** Reduce the browser viewport to 200 pixels.

**Expected result:** The application will continue showing all the information required to complete the registration even if I reduce the viewport to low pixels.

**Actual result:** Indeed it showed all the information displayed on the application to complete the registration.

**Pass/Fail:** It passes the responsive design testing successfully.

**Conclusion:** Even in low dimensions, the application still shows all the fields required to fill and complete the registration. The application behaves as expected when testing and changing the browser viewport dimensions.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



**Test Type:** Negative/Error handling testing.

**Action:** In the option sign up, I enter an email and a password that aren't registered in the system.

**Expected result:** The application recognizes that the information I entered is not saved in the database system.

**Actual result:** The application says: "Incorrect name or password" which means that it is working as expected.

**Pass/Fail:** It passes the error handling testing.

**Conclusion:** The application system works well by recognizing that the data I entered has not yet been recorded in the application's database.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



**Test Type:** Regression testing.

**Action:** I re-tested the application features to ensure that the application runs correctly and that it won't have any problems interacting with other features.

**Expected result:** The application will recognize again that the passwords don't match and won't allow to complete the registration. Also, it will continue showing all the information displayed in the user interface even when the browser viewport dimension is reduced to 200 pixels, and it won't allow me to sign in with a username and a password that are not registered yet.

**Actual result:** The application continues showing that it behaves properly in all of the three tests I ran

**Pass/Fail:** It passes the regression testing.

**Conclusion:** The application continues showing that it behaves properly in all of the three tests I ran.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_



**Test Type:** Usability testing.

**Action:** I invited a user who is interested in registering, and told him to try all the application features and asked him if the platform is user friendly and easy to use.

**Expected result:** The application has to be user friendly and very intuitive so the users can understanding it.

**Actual result:** The user understood the application perfectly.

**Pass/Fail:** It passes the usability testing.

**Conclusion:** The application is behaving perfectly due to its easy accessibility and intuitive system.

