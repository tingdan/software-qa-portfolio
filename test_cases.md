# Test Cases: Checkout & Cart Functionality
**System Under Test:** Lazada.co.th (Web)
**Author:** Danuporn Thongchai

| ID | Test Case Description | Pre-conditions | Test Steps | Expected Result | Priority |
|:---|:---|:---|:---|:---|:---|
| TC-01 | Add multiple items to cart | User is on Product Page | 1. Click "Add to Cart" on Item A <br> 2. Click "Add to Cart" on Item B | Cart badge should show "2" | High |
| TC-02 | Remove item from cart | 1 item in cart | 1. Go to Cart <br> 2. Click "Delete/Bin" icon | Item is removed; Total Price updates to 0 | High |
| TC-03 | Apply Invalid Voucher | User is at Checkout | 1. Type "FAKE123" in Voucher box <br> 2. Click Apply | Error message "Invalid Voucher" appears | Medium |
| TC-04 | Language Switch Logic | User on Home Page | 1. Click "TH" language icon <br> 2. Select "EN" | All UI text (Buttons, Labels) changes to English | Low |
| TC-05 | Max Quantity Input | User on Product Page | 1. Type "9999" in Quantity field | System should restrict to max stock or show warning | Medium |
