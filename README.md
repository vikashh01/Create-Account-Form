## 🧪 Test Scenarios – Create Account Form

| **Test Scenario ID** | **Test Scenario Description**       | **Input**                             | **Expected Result**                                |
|----------------------|-------------------------------------|-------------------------------------------------|----------------------------------------------------|
| TC01 | Verify all fields are visible and aligned   | Open the form                                  | All fields and labels should be visible and aligned properly |
| TC02 | Submit form with valid inputs               | Enter valid details in all fields and click Submit | Form should submit successfully                   |
| TC03 | Reset form after entering data              | Enter data and click Reset                      | All fields should be cleared                       |
| TC04 | Submit form with all fields blank           | Leave all fields empty and click Submit         | Should show validation error                       |
| TC05 | Email field validation                      | Enter invalid email (e.g. "abc@")               | Should show validation error                       |
| TC06 | Mobile number accepts only digits           | Enter alphabets in mobile number field          | Should show validation or reject input             |
| TC07 | Password field blank                        | Leave password field empty and submit           | Should show validation error                       |
| TC08 | Radio button selection                      | Try selecting both genders                      | Only one gender should be selectable               |
| TC09 | Checkbox selection                          | Select multiple subjects                        | Should allow multiple selection                    |
| TC10 | Address field long input                    | Enter a long address                            | Text area should accept and scroll                 |
| TC11 | Dropdown default selection                  | Leave age as "Select age"                       | Show error if age is required                      |
| TC12 | Submit with all invalid inputs              | Enter wrong formats in all fields               | Form should not submit                             |
| TC13 | Script injection attempt                    | Enter `<script>` in any field                   | Should sanitize or block input                     |
| TC14 | Emoji input                                 | Enter emoji in name field                       | Should allow/block based on character policy       |
| TC15 | Submit form without selecting gender        | Fill all fields except gender and click Submit  | Should show validation error or prompt to select gender |
