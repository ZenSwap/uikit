# 🥞 ZenSwap UIkit

[![Version](https://img.shields.io/npm/v/@zenswap/uikit)](https://www.npmjs.com/package/@zenswap/uikit) [![Size](https://img.shields.io/bundlephobia/min/@zenswap/uikit)](https://www.npmjs.com/package/@zenswap/uikit)

ZenSwap UIkit is a set of React components and hooks used to build pages on ZenSwap's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @zenswap/uikit`

## Setup

### Theme

Before using ZenSwap UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@zenswap/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@zenswap/uikit'
...
<ResetCSS />
```
