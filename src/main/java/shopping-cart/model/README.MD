```markdown
# Models Directory

Contains all business logic and data models for the shopping cart application.

## Structure
```
model/
├── user/           # User-related models
│   ├── User.java   # Base user class
│   ├── Customer.java
│   └── Seller.java
├── product/        # Product-related models
│   ├── Product.java
│   └── Inventory.java
├── cart/           # Shopping cart models
│   └── ShoppingCart.java
└── financial/      # Financial data models
    └── FinancialData.java
```

## Responsibilities
- Implement business logic
- Manage application state
- Handle data validation
- Implement model interfaces
- Support design patterns (Observer, etc.)

## Implementation Notes
- All models should implement corresponding interfaces
- Use appropriate design patterns where needed
- Include proper validation
- Follow SOLID principles
```