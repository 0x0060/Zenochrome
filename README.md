# Zenochrome: Minimalist Dark Theme for Zen Browser


## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Customization](#customization)
- [Developer Tools](#developer-tools)
- [Showcase](#showcase)

## Overview

A sleek, minimalist dark theme for Zen Browser that emphasizes content while reducing visual distractions. The theme features a pure black background with subtle gray accents, creating a distraction-free browsing experience ideal for low-light environments.

## Features

- **Pure Black Background**: All browser UI elements use a true black (#000000) background for maximum contrast and reduced eye strain
- **Gray Accent Colors**: Subtle gray accents (#909090) for selected elements and highlights
- **Hidden UI Elements**: Removes distracting elements like tracking protection icons, page action buttons, and scrollbars
- **Compact Mode Support**: Enhanced styling for Zen's compact mode with consistent black backgrounds
- **Subtle Borders**: Thin light borders (1px) with low opacity for visual separation without distraction
- **Custom Selection Styling**: Text selections use the theme's accent color with white text for better readability
- **Hidden Scrollbars**: Removes all scrollbars for a cleaner interface (applies to all scrollable content)

## Installation

1. Ensure you have Zen Browser installed
2. Place the `userChrome.css` and `userContent.css` files in your Zen profile's chrome directory
3. Restart Zen Browser to apply the theme

## Customization

The theme uses CSS variables that can be easily modified to customize the appearance:

```css
:root {
  --zen-colors-primary: #909090 !important;    /* Accent color for selections and highlights */
  --zen-colors-secondary: #000000 !important;   /* Main background color */
  --zen-colors-tertiary: #000000 !important;    /* Secondary background color */
  --sidebar-border-color: #252525 !important;   /* Border color for sidebar elements */
}
```

Modify these variables in the `userChrome.css` file to change the theme's color scheme.

## Developer Tools

This theme includes comprehensive styling for Zen's developer tools:

- **Dark Inspector**: Black backgrounds with gray text for the developer tools interface
- **Subdued Syntax Highlighting**: Monochromatic gray-scale syntax highlighting to reduce visual noise
- **Consistent UI**: Developer tools match the main browser theme for a seamless experience
- **Enhanced Contrast**: Carefully selected gray values for optimal readability in the developer console
- **Custom Rule View**: Styled CSS rule viewer with dark backgrounds and subtle highlights

## Showcase

![Main Browser Interface](https://github.com/user-attachments/assets/618f63a6-825e-42b1-a9e0-c9dd9746f8da)

![Tab Management](https://github.com/user-attachments/assets/b5527115-5dac-4e9a-99a3-08ec917567e6)

![Developer Tools](https://github.com/user-attachments/assets/54d2b012-b49b-44b3-9854-1362fa4c25ea)

![Settings Interface](https://github.com/user-attachments/assets/c9df7b25-4937-48e5-ae9e-f8ab8b2c8991)

![Reading Mode](https://github.com/user-attachments/assets/936a1c37-7d5d-4b95-8d39-d7da8c345ea3)

![Compact Mode](https://github.com/user-attachments/assets/1c3317b3-c50a-4098-a5e6-2b6ecd8f9149)


![image](https://github.com/user-attachments/assets/a05c6060-d1d1-4a79-8747-1026a4df884b)
