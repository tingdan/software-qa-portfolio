# Manual Testing — SauceDemo

## Application
- **URL:** https://www.saucedemo.com
- **Type:** E-commerce demo app for QA practice

## Test Coverage
| Feature | Cases | File |
|---|---|---|
| Login | 20 | TC_SauceDemo_Login.pdf |
| Product Listing | 15 | TC_SauceDemo_ProductListing.pdf |
| Add to Cart | 10 | TC_SauceDemo_AddToCart.pdf |
| Checkout Flow | 10 | TC_SauceDemo_Checkout.pdf |
| **Total** | **55** | |

## Types of Testing Covered
- Functional testing
- Boundary and edge case testing
- UI state testing
- Security testing (SQL injection, session management)
- Form validation testing
- Navigation testing

## Notable Bugs Found
| TC | Bug | Severity |
|---|---|---|
| TC-014 | error_user loses session when accessing cart | High |
| TC-010 | problem_user displays incorrect product images | Medium |
| TC-015 | visual_user displays incorrect product images | Low |
