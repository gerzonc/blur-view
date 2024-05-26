# VariableBlurView for React Native (iOS only)

Variable Blur View for React Native. Inspired by [@jtrivedi](https://github.com/jtrivedi) and [@aheze](https://github.com/aheze/VariableBlurView).

A fork off [BlurView](https://github.com/candlefinance/blur-view) using @candlefinance/blur-view@0.3.1 in order to use `VariableBlurView` instead of `UIVisualEffectView`.

## Preview

https://github.com/candlefinance/blur-view/assets/12258850/53f5a05f-7594-4f7e-acbc-997b10ee4345

## Installation

```sh
yarn add @candlefinance/blur-view
```

## Usage

Use the `BlurViewView` component to blur the content behind it.

```js
import { BlurViewView } from '@candlefinance/blur-view';

<BlurViewView
  style={{
    width,
    height: 200,
    position: 'absolute',
  }}
/>;
```

## Docs

View the example app in the [example](./example/src/App.tsx) folder.

| Property        | Type     | Default                                 | Description                                       |
| --------------- | -------- | --------------------------------------- | ------------------------------------------------- |
| `maxBlurRadius` | `number` | `20`                                    | The amount of blur to apply to the view.          |
| `gradientMask`  | `string` | see [source](./ios/images/Gradient.png) | The gradient mask to apply to the view in base64. |

## Contributing

See the [contributing guide](CONTRIBUTING.md) to learn how to contribute to the repository and the development workflow.

## License

MIT
