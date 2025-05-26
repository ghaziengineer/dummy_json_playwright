# Playwright API Testing - DummyJSON

This project is a complete example of how to automate API testing using [Playwright](https://playwright.dev) against the public [DummyJSON](https://dummyjson.com) API.

## 📁 Project Structure
```
playwright-api-tests/
├── tests/api/        # API test files
├── helpers/          # Auth / token helpers
├── utils/            # Sample test data
├── playwright.config.ts
└── README.md
```

## ✅ Covered Tests
- Auth (login)
- Products (GET + POST)
- Cart (add items with auth)
- Users (create user)

## ▶️ Running the tests
```bash
npx playwright test
```

## 🧪 Tooling
- Playwright (API testing)
- TypeScript
- JSONPlaceholder endpoints
- Lightweight CI/CD compatible
