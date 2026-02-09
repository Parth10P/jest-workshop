# Jest Workshop Submission

## Student Details
- Name: Patel Parthkumar
- Roll Number:2024-B-09112004
- GitHub Username:Parth10P

---

## Tests Written

List each test you wrote and briefly explain **what bug or regression it prevents**.

### 1. Test Name: No Coupon
**What it protects against:**  
Makes sure the 5% discount is applied when the subtotal is 1000 or more and no coupon is used. It prevents wrong total calculation.

---

### 2. Test Name: SAVE10 coupon
**What it protects against:** 
Checks that the SAVE10 coupon gives the correct 10% discount and stops future code changes from breaking this feature. 

---

### 3. Test Name: FLAT50 boundary case
**What it protects against:**
Ensures the final amount never becomes negative when FLAT50 is used. This prevents incorrect billing.

---

### 4. Test Name: invalid subtotal throws error
**What it protects against:**  
Makes sure the function throws an error for negative or invalid subtotal values, which helps avoid wrong data in the system.

---

### 5. Test Name: case-insensitive coupon
**What it protects against:**
Confirms that coupons work even if the user types them in lowercase or uppercase, preventing checkout problems. 

---

## CI Pipeline (if implemented)
- Did CI pass successfully? (Yes / No)
- GitHub Actions Run URL:

---

## Reflection (1–2 lines)
What is **one thing** you understood better about testing or CI after this workshop?