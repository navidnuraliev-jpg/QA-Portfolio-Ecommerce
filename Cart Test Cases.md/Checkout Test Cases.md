# Cart Test Cases

## TC-004 - Add a product to the shopping cart

**Preconditions**
- User is logged in.
- Products page is opened.

**Steps**
1. Click the **Add to cart** button for any product.

**Expected Result**
- The product is added to the shopping cart.
- The cart badge displays "1".
- The button changes to **Remove**.

---

## TC-005 - Remove a product from the shopping cart

**Preconditions**
- One product has been added to the cart.

**Steps**
1. Click the **Remove** button.

**Expected Result**
- The product is removed from the shopping cart.
- The cart badge disappears.
- The button changes back to **Add to cart**.

---

## TC-006 - Add multiple products to the shopping cart

**Preconditions**
- User is logged in.

**Steps**
1. Add three different products.

**Expected Result**
- All selected products are added.
- The cart badge displays "3".

---

## TC-007 - Verify shopping cart contents

**Preconditions**
- Two products have been added.

**Steps**
1. Open the shopping cart.

**Expected Result**
- Both products are displayed.
- Product names, prices and descriptions are correct.

---

## TC-008 - Continue shopping from the cart

**Preconditions**
- User is on the Cart page.

**Steps**
1. Click **Continue Shopping**.

**Expected Result**
- User is redirected to the Products page.
- Previously selected products remain in the cart.
