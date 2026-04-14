# Benchmark Scope — SauceDemo Checkout (Simple Happy Path)

## Flow

1. Navigate to https://www.saucedemo.com
2. Login with:
   - Username: standard_user
   - Password: secret_sauce
3. Add "Sauce Labs Backpack" to cart
4. Open cart
5. Proceed to checkout
6. Fill checkout information:
   - First Name: John
   - Last Name: Roblox
   - Zip Code: 12345
7. Finish the checkout

## Success Criteria

- User is logged in successfully (inventory page visible)
- "Sauce Labs Backpack" appears in the cart
- Checkout process completes without error
- Confirmation page shows successful order message

## Non-Goals

- No edge cases (invalid login, empty fields, etc.)
- No multiple items
- No randomization
- No performance or API testing
