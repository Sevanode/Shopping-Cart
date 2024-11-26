```markdown
# Controllers Directory

Contains controllers that coordinate between models and views.

## Structure
```
controller/
├── base/                      # Base controller classes
│   └── BaseController.java
├── LoginController.java
├── StoreFrontController.java
├── CartController.java
├── InventoryController.java
└── CheckoutController.java
```

## Responsibilities
- Handle user input from views
- Update models based on user actions
- Update views based on model changes
- Manage application flow
- Handle business logic coordination

## Implementation Notes
- Each controller should have one primary responsibility
- Use dependency injection for services
- Implement proper error handling
- Follow MVC pattern guidelines
```
