# autolab

### Requirements

- [Node](https://nodejs.org)
- [Playwright](https://playwright.dev)

#### Runs the end-to-end tests
* Windows, macOS/Linux
```
npx playwright test
```

#### Starts the interactive UI mode
* Windows, macOS/Linux
```
npx playwright test --ui
```

#### Runs the tests only on Desktop Chrome
* Windows, macOS/Linux
```
npx playwright test --project=chromium
```

#### Auto generate tests with Codegen
* Windows, macOS/Linux
```
npx playwright codegen
```

#### To open last HTML report run
* Windows, macOS/Linux
```
npx playwright show-report
```
