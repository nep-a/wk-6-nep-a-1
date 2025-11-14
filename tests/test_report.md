# 🧾 CleanCity Test Report

**Date:** [13/11/2025]  
**Phase 3:** Test Design & Early Execution   

---

## 1. Project Overview
The Clean City Project is a web-based sustainability platform enabling citizens to report waste, view cleanup events, and volunteer for environmental causes. The system includes a user interface, forms, event listings, and an admin dashboard.

---

## 2. Objectives
- Verify functional correctness of all modules.
- Validate usability and responsiveness.
- Identify defects and performance issues.
- Ensure smooth navigation and submission flow.

---

## 3. Scope
### In Scope:
- Frontend UI (React-based)
- Waste reporting form
- Events & volunteer features
- Login/Sign-up modules
- Admin dashboard basic functions

### Out of Scope:
- Backend data validation
- Payment or API integrations
- Automated or performance testing

---

## 4. Test Approach
- **Testing Type:** Manual Functional Testing  
- **Environment:** Chrome v120 on Windows 10  
- **Method:** Exploratory and scenario-based  
- **Focus Areas:** Form validation, navigation, authentication, and layout consistency

---

## 5. Test Summary

| Category | Total | Passed | Failed | Partial |
|-----------|--------|--------|---------|----------|
| Navigation | 3 | 3 | 0 | 0 |
| Forms | 6 | 5 | 1 | 0 |
| Authentication | 3 | 2 | 1 | 0 |
| Events | 4 | 3 | 1 | 0 |
| Dashboard | 4 | 3 | 0 | 1 |
| **Total** | **20** | **16** | **2** | **2** |

---

## 6. Key Defects Summary
- Event filtering not functional.
- Minor alignment issues on small screens.
- Missing profile edit feature.
- Missing accessibility attributes.

---

## 7. Risks & Recommendations
### Risks:
- Missing validation may allow incomplete data submission.
- Poor mobile optimization can affect usability.

### Recommendations:
- Implement backend validation.
- Improve mobile CSS layout.
- Add “Profile Edit” and event filtering.
- Conduct accessibility testing (WCAG 2.1).

---

## 8. Conclusion
Overall, the Clean City Project performs well functionally with strong user experience and stability. Most modules are fully operational. Minor UX and responsive issues can be addressed in future iterations.


**Test Manager:** _MERCY CHEBET____________  
**Approved By:** __HORACE WITABA, EMILY AWUOR_____________  
**Date:** ___13/11/2025________________


