---
title: useUnmount
nav:
  title: Hooks
  path: /hooks
group:
  title: LifeCycle
  path: /lifeCycle
  order: 9
legacy: /lifeCycle/use-unmount
---

# useUnmount

A hook that executes a function at unmount

## Examples

### Default Usage

<code src="./demo/demo1.tsx" />

## API

```javascript
useUnmount(fn: () => void);
```

### Params

| Property    | Description                                         | Type                   | Default |
|---------|----------------------------------------------|------------------------|--------|
| fn | the function need to be executed | () => void | -      |