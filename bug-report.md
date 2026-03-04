# Bug Report – SauceDemo

## Tested URL
https://www.saucedemo.com/

## Test Data
username: standard_user
password: secret_sauce

## Title
Unexpected application navigation after using browser Back/Forward buttons

## Environment
Browser: Chrome
OS: Windows

## Severity
Minor

## Priority
Low

## Steps to reproduce
1. Login as standard_user
2. Add item to cart
3. Remove item from cart
4. Press browser Back button twice
5. Press browser Forward button

## Expected result
User should remain on the login page or be required to authenticate again.

## Actual result
User is redirected back into the application interface.

## Notes
Issue observed during exploratory testing while navigating browser history.
