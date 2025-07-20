# 📄 Manual Test Cases - Hotel Booking App

---

## TC001: Successful Hotel Booking

**Objective:** Verify that a user can book a hotel room with valid input.

**Steps:**
1. Go to the booking page.
2. Enter location: "Toronto"
3. Select check-in: 25 Aug, check-out: 28 Aug
4. Set guests: 2
5. Click Search and choose hotel
6. Enter personal details and payment
7. Submit

**Expected Result:** Booking confirmation page appears with Booking ID.

---

## TC002: Booking with Past Dates

**Objective:** Ensure system rejects past dates.

**Steps:**
1. Go to the booking page.
2. Select check-in: yesterday
3. Attempt to book

**Expected Result:** Error or block prevents selecting past dates.

---

## TC003: Cancel Reservation

**Steps:**
1. Login and go to booking history
2. Click "Cancel" on recent booking

**Expected Result:** Booking status changes to "Cancelled".
