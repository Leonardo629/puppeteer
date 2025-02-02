---
sidebar_label: ProductLauncher
---

# ProductLauncher class

Describes a launcher - a class that is able to create and launch a browser instance.

#### Signature:

```typescript
export declare abstract class ProductLauncher
```

## Remarks

The constructor for this class is marked as internal. Third-party code should not call the constructor directly or create subclasses that extend the `ProductLauncher` class.

## Properties

| Property | Modifiers             | Type                              | Description |
| -------- | --------------------- | --------------------------------- | ----------- |
| product  | <code>readonly</code> | [Product](./puppeteer.product.md) |             |

## Methods

| Method                                                          | Modifiers | Description |
| --------------------------------------------------------------- | --------- | ----------- |
| [defaultArgs](./puppeteer.productlauncher.defaultargs.md)       |           |             |
| [executablePath](./puppeteer.productlauncher.executablepath.md) |           |             |
| [launch](./puppeteer.productlauncher.launch.md)                 |           |             |
