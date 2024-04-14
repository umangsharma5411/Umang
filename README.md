# Umang
# Porject:
 A website that allows for tax calculation based on a users input.
### References & Requirements

- The tax calculation works based on this formula -
    - Overall income (after deductions) under 8 (≤) Lakhs is not taxed.
        - Ex - if Gross Annual Income + Extra Income - Deductions =  6 Lakhs, no tax
        - if Gross Annual Income + Extra Income - Deductions =  9 Lakhs, tax
    - Income over 8 (>) Lakhs, the amount over 8 Lakhs is taxed at
        - 30% for people with age < 40
        - 40% for people with age ≥ 40 but < 60
        - 10% for people with age ≥ 60
        - Example
            - Age = 34, Income = 40 Lakhs, no deductions, tax = .3 * (40 - 8) = .3 * 32 = 9.6 Lakhs
      - Do not restrict user from entering incorrect values like characters in the number fields
    - Highlight a error icon to the right of the input field (shown as an example in above image as a circle with `!`). Hovering over it should show the error in a tooltip
    - If no errors are present, dont show the error icon
    - This should be present in all the number fields
- The age dropdown field should have 3 values -
    - <40
    - ≥ 40 & < 60
    - ≥ 60
    - If user has not entered this value and clicks on submit, show a error icon hovering over which should show that input field is mandatory
- Error icons should not be visible in the form by default.
- Clicking on submit should show a modal which would show the final values based on above calculations.

### Notes

- The assignment has to be done in HTML, CSS and Javascript. You can use Bootstrap and Jquery but no other library/design system is allowed.

# Output Screenshots

<img width="326" alt="TaxC1" src="https://github.com/umangsharma5411/Umang/assets/166703900/ce3967e2-d81f-4707-aee4-7ff234a727d0">



<img width="372" alt="TaxC2" src="https://github.com/umangsharma5411/Umang/assets/166703900/a8029243-1ae0-414d-8e70-87985137d1c5">



<img width="469" alt="TaxC3" src="https://github.com/umangsharma5411/Umang/assets/166703900/5011c128-c91e-4a71-b6b4-355c48567bd4">




<img width="343" alt="TaxC4" src="https://github.com/umangsharma5411/Umang/assets/166703900/c70f1c20-95d8-4087-be1b-e310c6c7f7b8">


<img width="338" alt="TaxC5" src="https://github.com/umangsharma5411/Umang/assets/166703900/36b82c94-11eb-45af-9d20-cfeccaf55c93">
