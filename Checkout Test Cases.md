# Checkout Test Cases

## TC-009 - Complete checkout with valid information

**Preconditions**
- At least one product is in the cart.

**Steps**
1. Open the cart.
2. Click **Checkout**.
3. Enter valid First Name.
4. Enter valid Last Name.
5. Enter valid Postal Code.
6. Click **Continue**.
7. Click **Finish**.

**Expected Result**
- Order is completed successfully.
- Confirmation page is displayed.

---

## TC-010 - Checkout with empty First Name

**Preconditions**
- User is on the Checkout Information page.

**Steps**
1. Leave First Name empty.
2. Fill Last Name.
3. Fill Postal Code.
4. Click **Continue**.

**Expected Result**
- Validation error for First Name is displayed.

---

## TC-011 - Checkout with empty Last Name

**Preconditions**
- User is on the Checkout Information page.

**Steps**
1. Fill First Name.
2. Leave Last Name empty.
3. Fill Postal Code.
4. Click **Continue**.

**Expected Result**
- Validation error for Last Name is displayed.

---

## TC-012 - Checkout with empty Postal Code

**Preconditions**
- User is on the Checkout Information page.

**Steps**
1. Fill First Name.
2. Fill Last Name.
3. Leave Postal Code empty.
4. Click **Continue**.

**Expected Result**
- Validation error for Postal Code is displayed.

---

## TC-013 - Cancel checkout process

**Preconditions**
- User is on the Checkout Information page.

**Steps**
1. Click **Cancel**.

**Expected Result**
- User is returned to the Cart page.
- Products remain in the shopping cart.
