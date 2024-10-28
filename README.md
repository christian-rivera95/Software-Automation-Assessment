# Software-Automation-Assessment

## Tasks and Requirements

### 1. Login Tests (Positive and Negative Scenarios)

**Positive Login:**
- **Task:** Write a test case for a successful login using valid credentials (`standard_user` / `secret_sauce`).
- **Requirements:**
  - Verify that the user is redirected to the inventory page upon successful login.

**Negative Login:**
- **Task:** Write test cases to handle the following invalid login scenarios:
  - Incorrect password.
  - Nonexistent username.
  - Empty username and password fields.
- **Requirements:**
  - Verify that the appropriate error message appears for each scenario.

### 2. Browse Items and Add to Cart

- **Task:** Write a test to browse the inventory, select two products, and add them to the shopping cart.
- **Requirements:**
  - Navigate through the inventory list, select specific items by name (e.g., "Sauce Labs Backpack" and "Sauce Labs Bike Light").
  - Verify that the items appear in the shopping cart with correct details (name, price).

### 3. Remove Items from Cart

- **Task:** Write a test to remove one of the items from the shopping cart.
- **Requirements:**
  - Verify that only one item remains in the cart after removing the other.
  - Ensure the cart icon count updates correctly.

### 4. Complete Purchase Flow

- **Task:** Write a test case for completing a purchase.
- **Steps:**
  1. After adding items to the cart, proceed to checkout.
  2. Fill in the checkout form with required details (e.g., name, postal code).
  3. Confirm the purchase and verify the order confirmation message.
- **Requirements:**
  - Assert that a confirmation message appears at the end of the purchase flow.
  - Validate that the cart is empty upon returning to the inventory page.
