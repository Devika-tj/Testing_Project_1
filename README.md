Testing Project 1
# SwagLabs Selenium IDE Test Suite
This project contains automated test cases for the SwagLabs demo application
(https://www.saucedemo.com/) created and executed using Selenium IDE.

## 1. Project Overview
The purpose of this test suite is to validate the main user flows on the
SwagLabs e-commerce demo site using Selenium IDE recorded test scripts.

## 2. Tool Used
- Selenium IDE (Browser Extension)
- Browser: Chrome / Firefox
- No coding required (record & playback)

## 3. Test Suites Included
The following test cases are recorded and saved as part of the Selenium IDE test suite:

### ✔ Login Test
- Open SwagLabs login page
- Enter valid username and password
- Click Login
- Verify user is redirected to Products page

### ✔ Add To Cart Test
- Select a product
- Click "Add to Cart"
- Verify the cart badge count increases
- Open cart page and confirm the product is listed

### ✔ Remove From Cart Test
- From the cart page, click “Remove”
- Verify the item is removed from cart
- Cart badge count updates

### ✔ Checkout Test
- Add one product to the cart
- Go to cart → Checkout
- Fill in First Name, Last Name, Postal Code
- Continue checkout
- Verify order overview page
- Finish order
- Confirm checkout complete message is displayed

### ✔ Logout Test
- Open the left menu (burger menu)
- Click Logout
- Verify the login page is shown again

## 5. How to Run the Tests
1. Open the Selenium IDE extension in your browser.
2. Click **Open an Existing Project**.
3. Select the **SwagLabs.side** file.
4. Choose a **Test** or **Test Suite**.
5. Click **Run** (▶) to execute.

## 4. Test Data Used
- Username: `standard_user`
- Password: `secret_sauce`

## 5. Notes
- Ensure stable network connection for best recording/playback.
- Update selectors if page elements change.
- Re-run the suite after any modifications to test cases.

## 6. Author
Automated using Selenium IDE by: Devika J


