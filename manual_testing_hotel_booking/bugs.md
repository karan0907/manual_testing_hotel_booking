# 🐞 Bug Reports - Hotel Booking App

---

### BUG-001: Calendar Allows Past Date Booking

**Severity:** High  
**Priority:** Medium  
**Steps to Reproduce:**
1. Go to booking page
2. Select yesterday as check-in date
3. Complete form and submit

**Expected Result:** System should prevent past date selection.  
**Actual Result:** Booking proceeds successfully.  

**Status:** Open

---

### BUG-002: Submit Button Doesn't Validate Empty Fields

**Severity:** Medium  
**Priority:** High  
**Steps to Reproduce:**
1. Leave all fields empty
2. Click Submit

**Expected Result:** Validation messages for each required field.  
**Actual Result:** Page reloads silently.
