# 🛒 Manual Testing – Demo Web Shop

A complete manual QA project for the [Demo Web Shop](https://demowebshop.tricentis.com/) e-commerce web application. This project covers end-to-end functional testing including test planning, scenario design, test case execution, and bug reporting.

---

## 📌 Project Overview

| Field | Details |
|---|---|
| **Application Under Test** | Demo Web Shop |
| **Testing Type** | Manual Functional Testing |
| **Tester** | Priyanshu Negi |
| **Test Cases Designed** | 30 |
| **Test Cases Executed** | 30 |
| **Bugs Identified** | 8 |

---

## 📁 Repository Structure

```
├── Test_Plan.docx              # Project scope, objectives & testing strategy
├── Test_Scenarios.xlsx         # 10 high-level test scenarios across all modules
├── Test_Cases.xlsx             # 30 detailed test cases with steps & results
├── Bug_Report.xlsx             # 8 documented defects with severity & priority
├── Test_Summary_Report.docx    # Final test execution summary & conclusions
└── README.md                   # Project documentation
```

---

## 🎯 Scope of Testing

### Modules Covered
- ✅ User Registration
- ✅ Login & Logout
- ✅ Product Search
- ✅ Add to Cart
- ✅ Cart Management
- ✅ Checkout Process

### Out of Scope
- ❌ Performance Testing
- ❌ Automation Testing
- ❌ Security Testing

---

## 📊 Test Execution Summary

| Metric | Count |
|---|---|
| Total Test Cases | 30 |
| Passed | 28 |
| Failed | 2 |
| Blocked | 0 |
| Pass Rate | **93.3%** |

---

## 🐛 Defect Summary

| Severity | Count |
|---|---|
| 🔴 High | 2 |
| 🟡 Medium | 3 |
| 🟢 Low | 3 |
| **Total** | **8** |

### Key Defects Found

| Bug ID | Module | Title | Severity | Priority | Status |
|---|---|---|---|---|---|
| BUG_01 | Login | Generic error shown when email field is empty | Medium | High | Open |
| BUG_02 | Checkout | Phone number field accepts invalid characters | High | High | Open |
| BUG_03 | Search | Search results not sorted by relevance | Low | Medium | Open |
| BUG_04 | Cart | Cart count not refreshed immediately after removing product | Medium | Medium | Open |
| BUG_05 | Registration | No password strength indicator shown | Low | Low | Open |
| BUG_06 | Checkout | No confirmation email received after order placement | High | Medium | Open |

---

## 🧪 Test Scenarios

| Scenario ID | Module | Test Scenario | Priority |
|---|---|---|---|
| TS_01 | Registration | Verify user can register with valid details | High |
| TS_02 | Registration | Verify error message for invalid email format | High |
| TS_03 | Login | Verify login with valid credentials | High |
| TS_04 | Login | Verify login with invalid password | High |
| TS_05 | Search | Verify product search using valid keyword | Medium |
| TS_06 | Cart | Verify user can add product to cart | High |
| TS_07 | Cart | Verify user can remove product from cart | Medium |
| TS_08 | Checkout | Verify checkout process with valid details | High |
| TS_09 | Checkout | Verify checkout without login | High |
| TS_10 | Logout | Verify user can logout successfully | Medium |

---

## 🛠️ Tools Used

- **Google Sheets** – Test case & bug documentation
- **MS Word** – Test plan & summary reports
- **Chrome Browser** – Test execution

---

## 📚 Key Learning Outcomes

- Understanding of SDLC & STLC
- Writing structured test cases with preconditions and steps
- Bug reporting with severity and priority classification
- Functional validation techniques
- Real-world QA project documentation

---

## ✅ Conclusion

The Demo Web Shop application is **functionally stable** with a pass rate of 93.3%. Core functionalities such as registration, login, cart management, and checkout are working as expected. However, validation improvements are recommended in the Login and Checkout modules, particularly around field-level error messaging and input format restrictions.

---

## 👤 Author

**Priyanshu Negi**  
Manual QA Tester
