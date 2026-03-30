# APM Login Functionality Test Report

**Date:** 24 February 2026  
**Test URL:** http://10.14.41.58/  
**Credentials Tested:** NIK: 2166539 | Password: Petrokimia1

---

## Scenario
Test the login functionality of the APM (Asset Performance Monitoring) system with valid credentials and verify successful redirection to the account/profile page.

---

## Steps Taken

1. **Navigated to the login page** at `http://10.14.41.58/`
   - Page loaded successfully with title "Log in"
   - Login form displayed with required fields

2. **Verified login form structure**
   - NIK field (textbox with placeholder "Please enter nik")
   - Password field (textbox labeled "Enter password")
   - Sign In button (clickable button)
   - Accessibility: Form fields are properly labeled

3. **Entered credentials**
   - NIK: 2166539
   - Password: Petrokimia1

4. **Clicked Sign In button**
   - Form submitted successfully

5. **Verified page redirection**
   - Redirected to account/profile page: `http://10.14.41.58/account`
   - Page title changed to "Profil - APM"

6. **Verified user profile information**
   - User name displayed: "Indra Dwi Nugraha, S.ST."
   - Email displayed: 2166539@petrokimia-gresik.com
   - User role: SUPER ADMIN
   - Additional profile details loaded:
     - Unit Kerja: Staf Digitalisasi
     - Job Title: Staf Pratama III
     - Post Title: SPr III Digitalisasi
     - Factory: Pabrik 1
     - PIC: Inspeksi Statik
     - Roles: SUPER ADMIN, EMPLOYEE, ADMIN ELOGSHEET

---

## Outcome

✅ **Login functionality works as expected**

- Valid credentials were accepted
- Successful authentication occurred
- User was redirected to the profile/account page (`/account`)
- Profile page loaded completely with all user information displayed correctly
- Navigation menu appeared with full access to dashboard and various modules:
  - Dashboard
  - Dashboard KPI
  - User Management
  - Master Data
  - Create Data
  - Proses Bisnis Evaluation
  - Asset Risk Assessment
  - Report
  - Asset & Maintenance Strategy
  - Job Package Plan
  - Online Monitoring
  - Activity Log

---

## Accessibility Observations

- Login form fields have proper labels and ARIA attributes
- Form elements are keyboard accessible
- Page structure is well-organized with proper heading hierarchy
- User profile information is displayed in a readable format with labels and values

---

## Issues Found

✅ **No issues detected**

- Login process completed without errors
- All form fields accepted input correctly
- Redirection occurred immediately after authentication
- User profile page displayed all information accurately

---

## Screenshots

![Profile Page After Successful Login](login-successful-profile-page.png)

The screenshot shows the APM system's profile page after successful login with:
- User avatar and name displayed in the top navigation
- Complete profile information in the main content area
- Left sidebar navigation menu with all available modules
- User role badge showing "SUPER ADMIN"

---

## Conclusion

The APM login functionality performs correctly with valid credentials. The system successfully authenticates users and redirects them to their profile page with all relevant information properly displayed. The user interface is accessible and the authentication flow is smooth and error-free.

