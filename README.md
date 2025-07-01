# auto-testing-tsk2
# AI-Enhanced Login Page Testing with Selenium

This project demonstrates an AI-enhanced approach to automated testing for web application login pages using Python and Selenium. It includes features like AI-generated test scenarios, adaptive element detection, and comprehensive test reporting.

## Features

- **AI-Generated Test Scenarios:** Automatically generates a wide range of test cases, including valid/invalid credentials, edge cases (empty fields, long inputs), and basic security vulnerability attempts (SQL injection, XSS).
- **Adaptive Element Detection:** Uses multiple fallback strategies to locate web elements (like username, password fields, and login button), making tests more resilient to minor UI changes.
- **Comprehensive Test Suite:** Executes a full suite of generated tests against a target login page.
- **Detailed Reporting:** Generates a summary of test results, including execution success rate, login success/failure counts, and AI insights.
- **Results Export:** Saves detailed test results to a JSON file.

## Getting Started

### Prerequisites

- Python 3.6+
- pip (Python package installer)
- Chrome Browser installed

### Installation

1. Clone this repository (or copy the code into a Colab notebook).
2. Install the required Python libraries:
