# common-tools-func

[简体中文](https://www.npmjs.com/package/common-tools-func) | [English](https://github.com/Caiyilina/common-tools-func/blob/master/README_EN.md)

## Project Introduction

A JavaScript/TypeScript library containing common utility functions, currently implementing debounce and throttle functionality.

## Features

- Debounce function
- Throttle function

## Installation

```bash
npm install common-tools-func
```

## Usage Example

```typescript
import { debounce, throttle } from "common-tools-func";

// Debounce example
const debouncedFn = debounce(() => {
  console.log("Debounced function called");
}, 300);

// Throttle example
const throttledFn = throttle(() => {
  console.log("Throttled function called");
}, 300);
```

## Development

```bash
# Install dependencies
npm install

# Run tests
npm test

# Build project
npm run build
```

## Contribution Guide

Pull Requests and Issues are welcome.

## License

MIT
