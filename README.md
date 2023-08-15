
# Getting Started with Plugins in Five

Welcome to the Five Plugins development guide! This README will walk you through the process of creating and integrating custom plugins to enhance your applications in Five.
For a deeper understanding of what you can achieve with plugins checkout the [official documentation]()

## Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Types of Plugins](#types-of-plugins)
- [Setting Up Your Development Environment](#setting-up-your-development-environment)
- [Using Five's UI Plugin Templates](#using-fives-ui-plugin-templates)
- [Building Your Plugin](#building-your-plugin)

## Overview

Five's Custom Actions offer developers the flexibility to add custom plugins, allowing for tailored and optimized applications. This guide will provide a step-by-step approach to developing these plugins.

## Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine.
- A code editor (e.g., [VS Code](https://code.visualstudio.com/)).
- Basic understanding of React (optional but recommended).

## Types of Plugins

1. **Custom Fields**: Simple display types for forms.
2. **Custom Editors**: UI elements that expand into a dialog for more screen space.
3. **Custom Forms**: A blank canvas type, not confined to a specific field on your form.

## Setting Up Your Development Environment

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
2. **Navigate to the Directory**:
   ```bash
   cd <repository-name>
3. **Install Dependencies**:
   ```bash
   npm install
4. **Run Webpack**:
   ```bash
   node ./node_modules/webpack/bin/webpack.js


## Using Five's UI Plugin Templates

### Download the Templates:
- [Five's UI Plugin Templates](#) 

### Extract the Templates:
1. Navigate to your Downloads folder.
2. Extract the `plugin-templates-ui.zip` file.

### Open in Your Preferred IDE:
- For this guide, we'll use VS Code.
  1. Open VS Code and select `File > Open Folder`.
  2. Navigate to the extracted `plugin-templates-ui` folder.

## Building Your Plugin

1. **Choose a Template**: Start with one of the provided templates, such as `custom-form-template`.
2. **Develop Your Plugin**: Use React or pure JavaScript, depending on your preference.
3. **Test Your Plugin**: Ensure it integrates well with Five and performs the desired functions.
4. **Compile with Webpack**: This will generate the necessary files for integration with Five.





