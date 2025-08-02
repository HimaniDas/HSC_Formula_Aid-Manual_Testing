# 📱 Manual Testing for HSC Formula Aid Mobile App

Welcome to the **Manual Testing Repository** for the **HSC Formula Aid Mobile Application**.
This repository contains comprehensive manual testing documentation to ensure the quality, usability, and accuracy of the app.

---

## 📖 About the Application

🔗 [HSC Formula Aid](https://play.google.com/store/apps/details?id=com.hsc_formula.aid&hl=bn)

![App Main Menu](App_Images/Capture.JPG)![Physics Formulas](App_Images/Capture1.JPG)![Vector Formulas](App_Images/Capture2.JPG)![Solved Example](App_Images/Capture3.JPG)

**HSC Formula Aid** is an educational mobile application designed for Higher Secondary Certificate (HSC) science students.  
It is the **first and largest e-formula platform** in the country, offering:

- ✅ Chapter-wise formulas  
- ✅ Mathematical examples and solutions  
- ✅ Physics, Chemistry, Biology, ICT and Mathematics coverage  
- ✅ Mobile-optimized interface for students  
- ✅ Offline accessibility for formulas  
- ✅ Shortcut methodology available in YouTube

---


## 🎯 Testing Objectives

This repository focuses on the following testing areas:

- **Functional Testing**: Verify core app features and formula accessibility  
- **Usability Testing**: Ensure a student-friendly interface and smooth navigation  
- **Performance Testing**: Evaluate responsiveness and content loading time  
- **Compatibility Testing**: Validate app behavior across devices and OS versions  
- **Content Accuracy**: Ensure formula correctness and solution accuracy  
- **Accessibility Testing**: Confirm the app is usable for all students  

---

## 📌 Testing Scope

**Functional Areas**  
- Formula browsing and search  
- Chapter navigation  
- Content accuracy validation  
- Offline functionality  
- User interface interactions  

**Platforms Tested**  
- Android: Version 5.0+ (API 21+)  
- iOS: Version 12.0+  

---

## 🗂️ Test Documentation

| Document | Format | Description |
|----------|--------|-------------|
| [📊 Test Cases](./Test_Cases/Test_Case.xlsx) | Excel | Detailed test cases for all scenarios |
| [🐞 Bug Report](./Bug_Report.pdf) | PDF | Identified bugs with severity classification |
| [📈 Test Execution Report](./Test_Results/Test_Report.xlsx) | Excel | Test results and execution summary |

---

## 🐞 Bug Severity Levels

- **Critical**: App crashes, core functionality broken  
- **Major**: Important features not working as expected  
- **Minor**: UI issues or usability problems  

---

## 📌 Test Execution Summary

From the [Bug Report](./Bug_Report.pdf):

- **Total Tests Conducted**: 25  
- **Tests Passed**: 12 (48%)  
- **Tests Failed**: 13 (52%)  

**Bug Breakdown by Severity**
- 🔴 **Critical**: 4 bugs  
- 🟠 **Major**: 5 bugs  
- 🟡 **Minor**: 4 bugs  

---

## 🐛 Bug Evidence (Screenshots & Proof)

### 🔴 Critical Bugs
- **BUG-001**: Missing Examples for Key Concepts  
  📎 [Evidence Folder](https://drive.google.com/drive/folders/12G9jHy1i8OXDd6xwH2wfHumHjaR47KSW?usp=sharing)  

- **BUG-002**: Incomplete Chapter Content Structure  
  📎 [Evidence Folder](https://drive.google.com/drive/folders/1giRvXUWD646HK9yffvULAhOVwqpYQ8_p?usp=drive_link)  

- **BUG-003**: Formula Text Format and Alignment Issues  
  📎 [Evidence Folder](https://drive.google.com/drive/folders/1n8gxfgwWMRua3Znu0440yXl_H2XYFnvk?usp=drive_link)  

- **BUG-004**: Poor Example Content Loading Performance  
  📎 [Evidence Folder](https://drive.google.com/drive/folders/19JE5Pxt7TJlT6bay1gGaJoNFAV2ZY4EL?usp=drive_link)  

### 🟠 Major Bugs
- **BUG-005**: Cross-Platform Menu and Layout Inconsistency  
  📎 [Evidence Folder](https://drive.google.com/drive/folders/1oa3UKNjGrgAJ5zX513H2i1mONAK8SYb8?usp=drive_link)  

- **BUG-006**: Subject Organization and Navigation Issues  
  📎 [Evidence Folder](https://drive.google.com/drive/folders/1oa3UKNjGrgAJ5zX513H2i1mONAK8SYb8?usp=drive_link)  

- **BUG-007**: UI Element Alignment and Missing Back Buttons  
  📎 [Evidence Folder](https://drive.google.com/drive/folders/13wihWQYWF0iZ5wqB5TPLvQgRrqYSOI9_?usp=drive_link)  

- **BUG-008**: Scrolling Performance Issues  
  📎 [Evidence Folder](https://drive.google.com/drive/folders/1uBaayV5DRxpK-8ezMXguW6t6pThrtJeD?usp=drive_link)  

- **BUG-009**: Page Layout and Pagination Issues  
  📎 [Evidence Folder](https://drive.google.com/drive/folders/1Ou8sI5A-hRLFVlEMYNIiYhSNZBA_vzzl?usp=drive_link)  

### 🟡 Minor Bugs
- **BUG-010**: Text Hierarchy Implementation Issues  
  📎 [Evidence Folder](https://drive.google.com/drive/folders/1URmQuZvDT0qv15vNImFbPnuCv2Pfdj25?usp=drive_link)  

- **BUG-011**: Improper Element Spacing  
  📎 [Evidence Folder](https://drive.google.com/drive/folders/1K_igVxsVGzZNHWrOlgbGcMh6uqKaFz2A?usp=drive_link)  

- **BUG-012**: Scroll Position Memory Partially Working  
  📎 [Evidence Folder](https://drive.google.com/drive/folders/1LZE6KoA1JjQikK3JJhHAgiENJ76-Xp_V?usp=drive_link)  

- **BUG-013**: Inconsistent Image and Diagram Sizing  
  📎 [Evidence Folder](https://drive.google.com/drive/folders/1xaXanbyMgE6hPTsf_WO9H-yeOQeSU0Zy?usp=drive_link)  

---

## 🔧 Recommendations

### Immediate Actions (Critical Bugs)
1. Complete missing examples and chapter content  
2. Implement consistent formula formatting  
3. Improve content loading performance  

### High Priority (Major Bugs)
1. Ensure Android & iOS feature parity  
2. Fix UI alignment and missing navigation elements  
3. Resolve scrolling lag and layout issues  

### Medium Priority (Minor Bugs)
1. Standardize text hierarchy and spacing  
2. Ensure consistent image sizing and clarity  
3. Improve scroll position memory  

---

## 🚀 Getting Started

1. Clone this repository:  
   ```bash
   git clone https://github.com/HimaniDas/Manual_Testing_for_HSC_Formula_Aid_Mobile_App.git

Follow these steps to review and execute the manual testing process:

2. **Execute Test Cases**  
   Open the test cases file located at [`/Test_Cases/Test_Case.xlsx`](./Test_Cases/Test_Case.xlsx) and perform the tests as instructed.

3. **Report Bugs**  
   Record any defects using the bug report templates available in [`/Bug_Reports/`](./Bug_Reports/).

4. **Document Test Results**  
   Save the outcomes of test executions in [`/Test_Results/Test_Report.xlsx`](./Test_Results/Test_Report.xlsx).
