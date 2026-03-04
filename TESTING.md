# Testing Strategy

This project uses a layered testing strategy including unit testing and integration testing.

Unit tests were written to verify individual calculator functions such as addition, subtraction, multiplication, and division.

Integration tests were used to verify the interaction between the calculator logic and the application workflow.

---

## Testing Pyramid

The testing pyramid suggests that most tests should be unit tests, with fewer integration tests and very few end-to-end tests.

In this project:
- 8 Unit Tests
- 2 Integration Tests

This structure follows the pyramid concept by having more unit tests.

---

## Black Box vs White Box Testing

Unit tests were written using white-box testing because the internal logic of functions was tested directly.

Integration tests were written using black-box testing because they tested the behaviour of the system from the user perspective.

---

## Functional vs Non-Functional Testing

Functional testing was performed to verify that calculator operations return correct results.

Non-functional testing such as performance, usability, and security testing were not included because the focus of this assignment is functionality.

---

## Regression Testing

The test suite can be used for regression testing in the future.  
Whenever new features are added, running the test suite will ensure that existing functionality is not broken.

---

## Test Results

| Test Name | Type | Status |
|-----------|------|--------|
| test_addition | Unit | Pass |
| test_subtraction | Unit | Pass |
| test_multiplication | Unit | Pass |
| test_division | Unit | Pass |
| test_division_by_zero | Unit | Pass |
| test_negative_numbers | Unit | Pass |
| test_decimal_numbers | Unit | Pass |
| test_large_numbers | Unit | Pass |
| test_full_calculation | Integration | Pass |
| test_clear_function | Integration | Pass |