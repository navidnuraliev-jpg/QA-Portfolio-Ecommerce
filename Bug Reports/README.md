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

