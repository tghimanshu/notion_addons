# Future Plan

This document outlines the roadmap for the Notion Addons project.

## Phase 1: Foundation (Complete)
- [x] Create basic HTML structure for the Beating Heart add-on.
- [x] Implement CSS animations for the heart pulsing effect.
- [x] Implement JavaScript logic for the day counter.
- [x] Establish comprehensive documentation for all source code.
- [x] Create a user-friendly README.

## Phase 2: Enhancements & Features (Planned)
The following features are proposed for the next iteration of development.

### 1. Configurable Parameters
**Goal**: Allow users to customize the start date and text without editing the source code.
- **Approach**: Parse URL query parameters (e.g., `?date=2022-01-01&label=Anniversary`) in the JavaScript block.
- **Benefit**: Makes the widget reusable for different events without code changes.

### 2. Modernization
**Goal**: Move towards a more structured project setup.
- **Approach**:
    - Separate CSS into `styles.css`.
    - Separate JavaScript into `script.js`.
    - Use a simple bundler (like Parcel or Vite) if complexity grows.

### 3. Responsive Design Improvements
**Goal**: Ensure the animation looks good on all device sizes, especially small mobile screens embedded in Notion.
- **Approach**: Add media queries to adjust the scale of the heart and font sizes based on the viewport width.

### 4. automated Testing
**Goal**: Ensure the date calculation is always correct.
- **Approach**: Add unit tests for the date logic (e.g., using Jest) to verify the day difference calculation handles leap years and different time zones correctly.

### 5. Theme Support
**Goal**: Allow different color schemes.
- **Approach**: Use CSS variables (Custom Properties) for colors, allowing them to be easily overridden.
