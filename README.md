# Test-Cases 

Below there are some Test Case samples that I wrote while working on my specific graduation project at the Informal School of IT applying the techniques and testing types learned on the www.bigfish.ro application.

-------

**Description:**
Validate that user can register using valid data in the required fields.

**Steps to reproduce:**
1. User goes to www.bigfish.ro and opens the app in the main page
2. User hovers the cursor over "Autentificare" field and clicks on "Cont nou" button
3. User fills all the required fields with valid data
4. User clicks on "Inregistrare" button

**Expected results:**
User should be able to register successfully using valid data.

**Test Data:**
* Nume: Stefan
* Prenume: Radu
* Telefon: 0785654429
* Email: radu.stefanut77@gmail.com
* Adresa: Str. Vulturului nr 64
* Oras: Buhusi
* Cod postal: 605404
* Judet: Bacau
* Parola: guru123
* Confirma parola: guru123

-----------

**Description:**
Validate that user is able to login with valid credentials.

**Steps to reproduce:**
1. User goes to www.bigfish.ro and opens the app in the main page
2. User hovers the cursor over "Autentificare" field
3. User enters valid credentials in"Email" and "Parola" fields
4. User clicks on "Conectare" button

**Expected results:**
User should be able to login successfully.

**Test Data:**
* Email: radu.stefanut77@gmail.com
* Parola: guru123
---------

**Description:**
Validate that user is able to logout.

**Preconditions:**
User is logged in.

**Steps to reproduce:**
1. User goes to www.bigfish.ro and opens the app in the main page
2. User hovers the cursor over the "Contul meu" field and clicks on the "Logout" button

**Expected results:**
1. User should be able to logout successfully
2. User should receive an confirmation message that he was successfully logout

**Test Data:**
* Email: radu.stefanut77@gmail.com
* Parola: guru123

----------

**Description:**
Validate that user can add a product to the cart.

**Preconditions:**
Application is open on the main page and the user is already logged in.

**Steps to reproduce:**
1. User selects an product from shopping list and adds it to the cart by pressing on "ADAUGA IN COS" button
2. User checks if the product was added to the cart by pressing on "VEZI DETALII COS" button

**Expected results:**
1. User should see the selected product added to the cart with correct details: name,price,quantity of 1
2. User should see the cart total price updated with the right values

**TestData:**
* Email: radu.stefanut77@gmail.com
* Parola: guru123
* Product: Mulineta Jaxon Claris CT 200
