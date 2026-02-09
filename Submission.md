# Jest Workshop Submission

## Student Details
- Name: Jay Patil
- Roll Number: 2024-B-24032006D
- GitHub Username: Jaypatil25

---

## Tests Written

List each test you wrote and briefly explain **what bug or regression it prevents**.

### 1. Test Name: no coupon case
**What it protects against:** Prevents breaking the basic calculation when no coupon is applied and ensures the function returns correct amount without any discount.

---

### 2. Test Name: SAVE10 coupon
**What it protects against:** Prevents incorrect percentage discount calculation and ensures 10% discount is applied correctly.

---

### 3. Test Name: FLAT50 boundary case
**What it protects against:** Prevents negative final amounts and ensures the result never goes below zero when discount is larger than subtotal.

---

### 4. Test Name: invalid subtotal throws error
**What it protects against:** Prevents processing invalid inputs like negative numbers and ensures proper error handling for bad data.

---

### 5. Test Name: case-insensitive coupon
**What it protects against:** Prevents coupon rejection due to case differences and ensures users can enter coupons in any case.

---

## CI Pipeline (if implemented)
- Did CI pass successfully? Yes
- GitHub Actions Run URL: https://github.com/Jaypatil25/jay-jest-workshop/actions/runs/21825425919

---

## Reflection (1–2 lines)
What is **one thing** you understood better about testing or CI after this workshop?

I learned how automated tests catch bugs before they reach users and how CI ensures code quality by running tests automatically on every change.

