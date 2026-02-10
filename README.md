
```
# 🎭 Playwright Automation Framework

End-to-end test automation framework built with Playwright and TypeScript/JavaScript, following Page Object Model design pattern.

## 🛠 Tech Stack

- Playwright — Modern web testing framework
- TypeScript / JavaScript — Programming language
- Page Object Model (POM) — Design pattern for maintainable tests
- GitHub Actions — CI/CD pipeline integration
- Postman + Playwright Request Context — API testing


```
## 📁 Project Structure

| Folder | Purpose |
|--------|---------|
| tests/ | Test scripts (UI + API) |
| pages/ | Page Object classes |
| utils/ | Helper functions and utilities |
| fixtures/ | Test data and custom fixtures |
| .github/ | CI/CD workflows |
| playwright.config.ts | Playwright configuration |
| package.json | Project dependencies |
```

```

## ✅ Test Coverage

- Login and authentication flows
- Navigation and search functionality
- Form validation and submission
- Dropdown, checkbox, radio button interactions
- File upload and download
- API testing (GET, POST, PUT, DELETE)
- Cross-browser testing (Chromium, Firefox, WebKit)
- Data-driven testing with JSON/CSV
- Visual comparison testing

## 🚀 Setup

```bash
# Clone the repo
git clone https://github.com/YOUR-USERNAME/playwright-automation-framework.git
cd playwright-automation-framework

# Install dependencies
npm install

# Install browsers
npx playwright install

# Run all tests
npx playwright test

# Run with UI mode
npx playwright test --ui

# Run specific test file
npx playwright test tests/login.spec.ts

# Generate HTML report
npx playwright show-report
```

## 📊 CI/CD

Tests run automatically on every push via GitHub Actions. See `.github/workflows/playwright.yml` for pipeline configuration.

## 👤 Author

**Jitender Singh Chauhan**

Senior SDET | QA Automation Engineer

[LinkedIn](https://www.linkedin.com/in/jitendra-chauhan/) | [Email](mailto:jitensingh716@gmail.com)

```
