
# Playwright-Web-Automation-with-JS  

This repository provides examples and resources for web automation using [Playwright](https://playwright.dev/) with JavaScript. Playwright is a powerful end-to-end testing framework that supports modern web apps, offering cross-browser automation and robust testing capabilities.  

## Features  
- Cross-browser support: Chromium, Firefox, WebKit  
- Headless and headed browser execution  
- Robust selectors for DOM interaction  
- Built-in support for testing modern frameworks like React, Angular, and Vue  
- Network interception and mocking  

## Prerequisites  
- Node.js (v16 or higher)  
- npm or yarn  

## Getting Started  

1. **Clone the repository**:  
   ```bash  
   git clone https://github.com/Razib-R75/Palywrite-web-automation-with-js/edit/main  
   cd Playwright-Web-Automation-with-JS  
   ```  

2. **Install dependencies**:  
   ```bash  
   npm install  
   ```  

3. **Run a sample test**:  
   ```bash  
   npx playwright test  
   ```  

4. **View test reports**:  
   Test execution generates a report in the `playwright-report` directory. Use the following command to open it:  
   ```bash  
   npx playwright show-report  
   ```  

## Example Test Script  
```javascript  
const { test, expect } = require('@playwright/test');

test('Navigate to example page and verify title', async ({ page }) => {
  await page.goto('https://example.com');
  await expect(page).toHaveTitle('Example Domain');
});
```  

## Directory Structure  
- **tests/**: Contains test scripts  
- **playwright.config.js**: Configuration file for Playwright  

## Resources  
- [Playwright Documentation](https://playwright.dev/docs/intro)  
- [API Reference](https://playwright.dev/docs/api/class-playwright)  

## Contributing  
Contributions are welcome! Feel free to open issues or submit pull requests to add more examples or enhance existing scripts.  

