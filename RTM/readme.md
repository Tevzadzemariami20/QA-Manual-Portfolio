# 📌 Requirements Traceability Matrix (RTM)

## 📖 Overview

This document presents the **Requirements Traceability Matrix (RTM)** for both **AI Platform** and **Web Platform** testing projects.

The RTM demonstrates how **business and functional requirements** are mapped to:

* Test Scenarios
* Test Cases
* Checklists
* Bug Reports

## 🎯 Purpose of RTM

* Ensure every requirement is tested
* Track test coverage and quality status
* Identify failed or blocked features quickly
* Provide visibility for QA Leads, Recruiters, and Stakeholders

## 🤖 AI Platform – RTM Summary

### Scope Covered

* Chat functionality
* Prompt validation
* Chat search and navigation
* AI Plagiarism scan feature
* Login modal validation

### AI RTM Highlights

* All core chat and prompt requirements are covered by test cases
* Input validation works correctly (empty prompts blocked)
* AI Plagiarism **Scan button defect identified and reported**
* RTM clearly links failed functionality to a bug report

### AI Platform – RTM Status

* ✅ Passed Requirements: Prompt submission, chat navigation, filters
* ❌ Failed Requirement: AI Plagiarism Scan
* 🐞 Bugs Identified: Scan button not triggering results


## 🌐 Web Platform – RTM Summary

### Scope Covered

* Wishlist functionality
* Favorites management
* Language / localization feature

### Web RTM Highlights

* Wishlist add/view flow works as expected
* Favorites removal shows inconsistent behavior and needs retesting
* Language switch to English is not functioning and was reported as a defect

### Web Platform – RTM Status

* ✅ Passed Requirements: Add to Wishlist, View Wishlist
* ⚠️ Needs Retest: Remove from Favorites
* ❌ Failed Requirement: Language change to English
