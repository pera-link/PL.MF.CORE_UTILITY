# Documentation for the Microfrontend Repository

## Overview
This repository serves as a microfrontend that consolidates and provides access to all public components and shared functionalities. It is designed to promote reusability and consistency across multiple applications by centralizing commonly used UI components and utility functions.

## Purpose
The primary goal of this microfrontend is to act as a shared library for public-facing components and utilities. It ensures that all applications using this repository have a unified look and feel, as well as access to standardized functionality.

## Key Features
1. **Reusable UI Components**:
    - Includes commonly used components such as cards, navigation bars, buttons, and other UI elements.
    - Designed to be customizable and adaptable to various use cases.

2. **Utility Functions**:
    - Provides shared functions such as API connectors, data formatters, and other helper utilities.
    - Simplifies integration with backend services and ensures consistent behavior across applications.

3. **Centralized Maintenance**:
    - All components and utilities are maintained in one place, making updates and bug fixes easier to manage.
    - Promotes consistency and reduces duplication of code across projects.

## Usage
- Import the required components or utilities into your application as needed.
- Follow the provided guidelines and examples to ensure proper integration and usage.

## Contribution
Contributors are encouraged to:
- Add new components or utilities that can benefit multiple applications.
- Improve existing components for better performance, accessibility, or usability.
- Report and fix bugs to maintain the quality of the repository.

## Notes
- This repository is intended for public-facing components and shared functionalities only. Application-specific logic or components should not be included here.
- Ensure that all contributions adhere to the coding standards and guidelines defined for this repository.


## Adding Components or Utilities

To add a new component or utility:

1. **Create the Component/Utility**:
    - Place the new component or utility in the appropriate folder, such as `components` or `utilities`.

2. **Export the Component/Utility**:
    - Export it from the `peralink_core_utility.tsx` file to make it available for use.

3. **Import in Another Microfrontend**:
    - Import the component or utility in another microfrontend by referencing `core-utility`. For example:
      ```javascript
      import { YourComponent } from '@peralink/core-utility';
      ```

