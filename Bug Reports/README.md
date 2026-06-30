# BR-001 – User can submit login form with empty credentials

## Bug ID
BR-001

## Title
Login form accepts empty credentials.

## Severity
High

## Priority
High

## Environment
Google Chrome (Latest)
Windows 11

## Preconditions
User is on Login page.

## Steps to Reproduce

1. Open login page.
2. Leave Username empty.
3. Leave Password empty.
4. Click Login.

## Expected Result

Validation message should appear before sending request.

## Actual Result

Login request is processed and generic error message is displayed.

## Status

Open

# BR-002 – Shopping cart badge is not updated immediately

## Severity
Medium

## Steps

1. Login.
2. Add product.
3. Remove product.

## Expected

Cart badge immediately becomes 0.

## Actual

Badge disappears only after page refresh.

## Status

Open

# BR-003 – Error message is not centered on small screens

## Severity
Low

## Steps

1. Open site on mobile resolution.
2. Enter wrong password.
3. Press Login.

## Expected

Error message is centered.

## Actual

Message overlaps the logo.

## Status

Open

# BR-004 – Password field keeps previous value after failed login

## Severity
Medium

## Expected

Password field should be cleared.

## Actual

Password remains visible in the input.

## Status

Open

# BR-005 – Sort option resets after page refresh

## Severity
Low

## Steps

1. Login.
2. Sort products by Price High to Low.
3. Refresh page.

## Expected

Selected sorting remains.

## Actual

Sorting resets to default.

## Status

Open

# BR-006 – Product image is stretched on small screen resolution

## Bug ID
BR-006

## Title
Product image is stretched on small screen resolution

## Environment
Windows 11
Google Chrome Latest

## Preconditions
User is logged in.

## Steps to Reproduce

1. Login to the application.
2. Resize browser window to mobile width.
3. Open Products page.

## Expected Result

Product images should maintain their aspect ratio.

## Actual Result

Images appear stretched and distorted.

## Severity

Low

## Priority

Low

## Status

Open

# BR-007 – Checkout form allows leading spaces

## Bug ID
BR-007

## Title
Checkout form accepts leading spaces in First Name

## Environment
Windows 11
Chrome Latest

## Preconditions
User is on Checkout Information page.

## Steps to Reproduce

1. Enter "   John" in First Name.
2. Fill remaining fields.
3. Continue checkout.

## Expected Result

Leading spaces should be trimmed automatically.

## Actual Result

Leading spaces are accepted.

## Severity

Low

## Priority

Medium

## Status

Open

# BR-008 – Browser Back button returns to checkout after order completion

## Bug ID
BR-008

## Title
Back button allows returning to completed checkout

## Environment
Windows 11
Google Chrome

## Preconditions
Order completed successfully.

## Steps to Reproduce

1. Finish an order.
2. Click browser Back button.

## Expected Result

User should stay on confirmation page or be redirected safely.

## Actual Result

Previous checkout page is displayed.

## Severity

Medium

## Priority

Medium

## Status

Open

