# Test-Case

## **Search WordPress**

**1. Test login with correct credentials**

**Description**

Test the login by using the correct credentials.

**Steps to reproduce**

1. Go to site.com/login
2. Add correct user/pass
3. Observe if user can login

**Expected result**

The user should be able to login.

**Test Data**

User: test

Pass: 123

**********************************************

## **2. Test login with incorrect credentials**

**Description**

Check if the login when a person uses an incorrect user/ password.

**Steps to reproduce**

1. Go to www.website.com/login 
2. Add an incorrect user/pass
3. Press the login button

**Expected result**

User did not should be able to login.

**Test Data**

User: test

Pass: #$134

************************************************************************

## **3. Test login with no credentials**

**Description**

Check if the login when a person not uses credentials.

**Steps to reproduce**

1. Go to www.website.com/login
2. Do not add credentials
3. Press the login button

**Expected result**

The user should not be able to login.

**Test Data**

User: -

Pass: -

*************************************************************

## **4. Test login with the checkbox "Remember me" press**

**Description**

Check if the login when a person uses the correct user/password with the checkbox " Remember me " press.

**Steps to reproduce**

1. Go to www.website.com/login
2. Add a correct user/pass
3. Press Remember Me
4. Press  login button

**Expected result**

The user should be able to login and will remember in account for a period.

**Test Data**

User: test

Pass: 123

Checkbox Remember Me 

**************************************************

# **Search Emag**

## **1. Verify search is functional and generating the correct result**

**Description**

Enter a search term into the search box and check that the correct result is returned.

**Steps to reproduce**

1. Go to www.emag.ro
2. Enter a term into the search box
3. Press the button

**Expected result**

The user should receive the correct result.

**Test Data**

Term to search: masina de spalat

*******************************************************************

## **2. Verify search it can autocomplete what you write**

**Description**

Enter a search term into the search box and view if the search box can autocomplete what you write.

**Steps to reproduce**

1. Go to www.emag.ro
2. Enter a term into the search box
3. View if the search shows your result as you type


**Expected result**

The user should receive autocompletes when he writes.

**Test Data**

Term to search: masina de spalat

*******************************************************************

## **3. Test that the search result is displayed correctly when no results are found**

**Description**

Enter a search term into the search box and check if the result is displayed correctly but the results are not found.

**Steps to reproduce**

1. Go to www.emag.ro
2. Enter a term into the search box
3. Press the button
4. View the " No results are found" message

**Expected result**

The user should have no result found.

**Test Data**

Term to search: 12@#$

*****************************************************************

# Automation testing store

## **1. Test quantity input in limit product per order.**

**Description**

Test quantity input in the maximum product you can should to buy.

**Steps to reproduce**

1. Go to https://automationteststore.com/index.php?rt=product/product&product_id=118
2. Select between limits for the product
3. Add to cart.

**Expected result**

You can add the products in cart.

**********************************************************

## **2. Test quantity input across the limit product select per order**

**Descripton**

Test quantity input, add more products across the limit.

**Steps to reproduce**

1. Go to https://automationteststore.com/index.php?rt=product/product&path=68_70&product_id=121
2. Select a product across the limit
3. Add to cart

**Expected result**

You will see a message with an error because you can't add more products than the limit.

*********************************************************

## **3. Test " Add to cart" button**

**Description**

Test the " Add to cart" button to see if the word is in the correct condition.

**Steps to reproduce**

1. Go to https://automationteststore.com/
2. Select the product you want
3. Press the " Add to cart" button

**Expected result**

Users can add and see the product in the cart.

********************************************

## **4. Test size input**

**Description**

Test size input on the product to see if you can select the size you want.

**Steps to reproduce**

1. Go to https://automationteststore.com/index.php?rt=product/product&path=68_70&product_id=121
2. Press the button to see about more size
3. Select your size

**Expected result**

Users can see and select which size he want.
