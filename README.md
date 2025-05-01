# PL.MF.CORE_UTILITY

> A centralized microfrontend for public UI components and shared utility functions.

---

## 📌 Overview

**PL.MF.CORE_UTILITY** is a microfrontend designed to centralize **reusable UI components** and **common utilities**. It ensures design and functionality consistency across applications by acting as a shared library.

---

## 🎯 Purpose

The primary purpose of this repository is to:

- Provide a **shared source** for frequently used UI components and functions.
- Promote a **consistent look and feel** across all applications.
- **Reduce redundancy** by avoiding repeated code in different projects.

---

## ✨ Key Features

### 🔹 Reusable UI Components

- Includes elements such as:
  - Cards  
  - Navigation bars  
  - Buttons  
  - Other commonly used components  
- Fully customizable and adaptable to various use cases

### 🔹 Utility Functions

- Common helper utilities including:
  - API connectors  
  - Data formatters  
  - Validation logic  
- Ensures standardized behavior across applications

### 🔹 Centralized Maintenance

- All shared code is maintained in one place:
  - Easier bug tracking and resolution  
  - Faster updates and refactoring  
  - Promotes code cleanliness and consistency  

---

## 🚀 Usage

To use a component or utility in another microfrontend:

```tsx
import { YourComponent } from '@peralink/core-utility';
```

Refer to the provided usage examples and integration guidelines to ensure smooth implementation.

---

## 🤝 Contributing

We welcome and encourage contributions to improve this shared resource.

### You can:

- 🧱 Add new reusable components or utility functions  
- 🔧 Improve existing components for:
  - Performance  
  - Accessibility  
  - Usability  
- 🐞 Fix bugs and submit enhancements  

### Contribution Guidelines:

- Do **not** include application-specific logic or styling  
- Follow our **code style and naming conventions**  
- Provide **clear documentation** for new components or utilities  

---

## 🧩 Adding a New Component or Utility

Follow these steps to contribute new functionality:

1. **Create the Component/Utility**  
   Add your file to the relevant directory (`components/` or `utilities/`).

2. **Export It**  
   Update the `peralink_core_utility.tsx` file:
   ```tsx
    import { YourComponent } from "./components/YourComponent";

    export { YourComponent };
   ```

3. **Use It in Other Projects**  
   In your consuming application:
   ```tsx
   import { YourComponent } from '@peralink/core-utility';
   ```

---

## 📝 Notes

- This repository is intended only for **public-facing and shared functionalities**.  
- Avoid including **application-specific** logic or components.  
- Ensure contributions comply with established **coding standards** and **review guidelines**.  
