# ELEVATE-TASK-7

# Browser Extension Security Audit Report

This document outlines the steps taken to review and secure the browser by auditing installed extensions.

## Steps Followed

1. **Opened the Browser’s Extension Manager**  
   Navigated to the extensions/add-ons page through the browser settings to view all installed extensions.

2. **Reviewed Installed Extensions**  
   The following extensions were found installed:

   - **Cookie-Editor**  
     Allows users to create, edit, and delete cookies directly from the browser.
     
   - **FoxyProxy**  
     A proxy management tool often used for testing or privacy purposes.
     
   - **Google Docs Offline**  
     Enables offline access to Google Docs, Sheets, and Slides.
     
   - **McAfee WebAdvisor**  
     Provides web safety ratings and protection.
     
   - **Wappalyzer - Technology Profiler**  
     Identifies web technologies used by websites (e.g., CMS, analytics tools, frameworks).

3. **Checked Permissions and Reviews**  
   - Verified user reviews and permissions for each extension via the Chrome Web Store.
   - Noted any excessive permissions or low ratings.

4. **Identified Unused or Suspicious Extensions**  
   - **FoxyProxy**: Might not be necessary if not actively using proxy features.
   - **McAfee WebAdvisor**: Not essential unless relying on it for browsing safety.
   - Other extensions like Google Docs Offline and Cookie-Editor were considered safe and/or essential based on use.

5. **Removed Suspicious or Unnecessary Extensions**  
   _Actions Taken:_  
   - [ ] FoxyProxy – **Pending Review**  
   - [ ] McAfee WebAdvisor – **Pending Removal if unused**

6. **Restarted the Browser**  
   Browser was restarted to ensure changes took effect and to assess performance improvements.

7. **Researched Risks of Malicious Extensions**  
   - Extensions with broad permissions can access browsing activity or inject scripts.
   - Some malicious extensions may track user data, inject ads, or redirect traffic.

8. **Documented Changes**  
   _Changes Log:_  
   - No extensions removed yet — final decision pending usage needs and security analysis.
   - This README serves as documentation of the audit process.

## Recommendations

- Repeat this audit monthly.
- Remove any unused or suspicious extensions.
- Always check extension permissions before installing.
- Use trusted sources like the official Chrome Web Store.

## Notes

- Extensions like **Wappalyzer** and **Cookie-Editor** are useful for web development or testing.
- Ensure you're using only what's necessary to reduce security risk and improve browser performance.

