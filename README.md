# eslint-plugin-ts-custom-rules

## Installation

You can install this package using npm. Make sure ESLint is already installed in your project.

```bash
npm install --save-dev eslint-plugin-ts-custom-rules
```

## Usage

After installing the package, update your ESLint configuration file (e.g., .eslintrc.js or .eslintrc.json) to include the new rule.

```json
{
  "plugins": ["ts-custom-rules"],
  "rules": {
    "ts-custom-rules/prefer-interface": "error",
  }
}
```