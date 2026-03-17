# 🧮 Calculator Test Cases

## ✅ Valid Test Cases

### TC-001: Addition of Two Numbers
- **Test Case ID:** TC-001
- **Test Description:** Verify addition of two positive numbers
- **Preconditions:** Calculator is open
- **Test Steps:**
  1. Enter 5
  2. Press +
  3. Enter 3
  4. Press =
- **Expected Result:** 8

---

### TC-002: Subtraction Resulting Negative
- **Test Case ID:** TC-002
- **Test Description:** Verify subtraction where result is negative
- **Preconditions:** Calculator is open
- **Test Steps:**
  1. Enter 3
  2. Press -
  3. Enter 5
  4. Press =
- **Expected Result:** -2

---

### TC-003: Multiplication with Decimals
- **Test Case ID:** TC-003
- **Test Description:** Verify multiplication with decimal numbers
- **Preconditions:** Calculator is open
- **Test Steps:**
  1. Enter 2.5
  2. Press *
  3. Enter 4
  4. Press =
- **Expected Result:** 10

---

### TC-004: Division Operation
- **Test Case ID:** TC-004
- **Test Description:** Verify division of two numbers
- **Preconditions:** Calculator is open
- **Test Steps:**
  1. Enter 10
  2. Press /
  3. Enter 2
  4. Press =
- **Expected Result:** 5

---

### TC-005: BODMAS Rule
- **Test Case ID:** TC-005
- **Test Description:** Verify operator precedence
- **Preconditions:** Calculator supports expressions
- **Test Steps:**
  1. Enter 2 + 3 * 4
  2. Press =
- **Expected Result:** 14

---

## ❌ Invalid Test Cases

### TC-006: Division by Zero
- **Test Case ID:** TC-006
- **Test Description:** Verify division by zero handling
- **Preconditions:** Calculator is open
- **Test Steps:**
  1. Enter 10
  2. Press /
  3. Enter 0
  4. Press =
- **Expected Result:** Error message displayed

---

### TC-007: Non-Numeric Input
- **Test Case ID:** TC-007
- **Test Description:** Verify invalid character handling
- **Preconditions:** Calculator allows input
- **Test Steps:**
  1. Enter a + b
  2. Press =
- **Expected Result:** Invalid input error

---

### TC-008: Multiple Operators
- **Test Case ID:** TC-008
- **Test Description:** Verify handling of invalid operator sequence
- **Preconditions:** Calculator is open
- **Test Steps:**
  1. Enter 5 ++ 2
  2. Press =
- **Expected Result:** Error message

---

## ⚠️ Edge Test Cases

### TC-009: Zero Multiplication
- **Test Case ID:** TC-009
- **Test Description:** Verify multiplication with zero
- **Preconditions:** Calculator is open
- **Test Steps:**
  1. Enter 0 * 5
  2. Press =
- **Expected Result:** 0

---

### TC-010: Floating Point Precision
- **Test Case ID:** TC-010
- **Test Description:** Verify decimal precision
- **Preconditions:** Calculator supports decimals
- **Test Steps:**
  1. Enter 0.1 + 0.2
  2. Press =
- **Expected Result:** 0.3
