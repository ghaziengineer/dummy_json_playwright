# Playwright API Testing - DummyJSON

This project is a complete example of how to automate API testing using [Playwright](https://playwright.dev) against the public [DummyJSON](https://dummyjson.com) API.

## 📁 Project Structure
```
playwright-api-tests/
├── core/              # Generic API client creation
├── pages/             # API layer (POM)
│   ├── authAPI.ts     # Login, token
│   ├── productAPI.ts  # CRUD products
│   ├── cartAPI.ts     # Add/update cart
│   └── userAPI.ts     # User actions
├── tests/api/         # Actual test cases
├── utils/             # Sample test data
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
