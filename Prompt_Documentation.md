
# AI-Powered QA Testing Assistant
## Prompt Documentation

### 1. Project Objective
The objective is to help manual QA testers prepare test scenarios,
test cases and structured bug reports more efficiently.

### 2. AI Tool Used
ChatGPT was used to generate and refine QA test case prompts
and to produce example manual test cases.

### 3. Initial Prompt
Act as a Software QA Engineer. Create manual test cases for an
e-commerce checkout feature. Include positive, negative and
boundary scenarios. Provide test case ID, scenario, preconditions,
steps, test data, expected result and priority.

### 4. Requirements Provided
- Users can add products to the cart.
- Users can apply a coupon code.
- Users can enter shipping details.
- Users can complete payment.
- Invalid coupon codes should display an error message.

### 5. Problem Identified
The first version of the website generated generic test cases
using predefined templates. Its results did not fully reflect
the supplied requirements.

### 6. Improvement Made
The JavaScript logic was updated to identify keywords such as
cart, coupon, shipping and payment and display related test scenarios.

### 7. Important Technical Limitation
The website currently uses keyword-based rules and predefined
templates. It does not call a live AI model or AI API.
ChatGPT was used separately to generate example QA test cases.

### 8. Testing Performed
- Checked test case generation using e-commerce checkout requirements.
- Checked bug report generation using a sample bug scenario.
- Checked prompt generation in the Prompt Builder.
- Reviewed generated results manually.

### 9. Future Improvements
- Integrate a live AI model through a secure backend.
- Improve requirement analysis.
- Add test execution status and result tracking.
- Export complete test cases and reports.
