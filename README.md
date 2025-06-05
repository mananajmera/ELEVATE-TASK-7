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
     After a detailed evaluation of the installed extensions, no extensions were removed during this audit. Each extension was determined to be actively used and contributes to specific tasks or workflows. Below 
     is a breakdown of their usage:

     ✅ Cookie-Editor
     Usage: Frequently used for testing cookies during web development or security testing.
     Reason to Keep: Provides granular control over cookies, which is essential for debugging or simulating user sessions.

     ✅ FoxyProxy
     Usage: Used to manage and switch between different proxy configurations.
     Reason to Keep: Valuable for network testing, geolocation spoofing, or accessing services behind restricted networks.

     ✅ Google Docs Offline
     Usage: Enables offline access to Google Drive documents.
     Reason to Keep: Critical for productivity during internet outages or travel, especially for users relying on Google Workspace.

     ✅ McAfee WebAdvisor
     Usage: Offers real-time protection by warning users about potentially dangerous websites.
     Reason to Keep: Adds an extra layer of browser security; useful for users frequently navigating unfamiliar web content.
 
     ✅ Wappalyzer - Technology Profiler
     Usage: Used to detect frameworks, CMSs,analytics tools, and other technologies behind websites.
     Reason to Keep: Important for reconnaissance in cybersecurity, competitive research, or technical evaluation of websites.

6. **Restarted the Browser**  
   Browser was restarted to ensure changes took effect and to assess performance improvements.

7. **Researched Risks of Malicious Extensions**  
   - Extensions with broad permissions can access browsing activity or inject scripts.
   - Some malicious extensions may track user data, inject ads, or redirect traffic.

8. **Documented Changes**  
   All extensions were reviewed for purpose, security, and usage frequency. Based on this review:
  - No unnecessary or suspicious extensions were found.
  - All extensions are currently used in regular tasks and deemed safe based on public reviews and permissions requested.

## Recommendations

- Repeat this audit monthly.
- Remove any unused or suspicious extensions.
- Always check extension permissions before installing.
- Use trusted sources like the official Chrome Web Store.

## Notes

- Extensions like **Wappalyzer** and **Cookie-Editor** are useful for web development or testing.
- Ensure you're using only what's necessary to reduce security risk and improve browser performance.

