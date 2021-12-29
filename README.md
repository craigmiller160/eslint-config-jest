# eslint-config-jest

A common ESLint Configuration for working with projects that use jest.

## How to Use

Install the library: `yarn add --dev @craigmiller160/eslint-config-jest`. Then, extend it in your `.eslintrc.js` file:

```
module.exports = {
    extends: [
        '@craigmiller160/eslint-config-jest'
    ]
};
```

## PreRequisites

ESLint and Jest must both be installed on the consuming project.
