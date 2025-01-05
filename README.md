# React + Vite

# React Morph Menu

`react-morph-menu` is a customizable navigation menu for React applications. This package provides an elegant and interactive menu indicator with dynamic behavior based on user interactions.

## Installation

Install the package using npm or yarn:

```bash
npm install react-morph-menu
```

or

```bash
yarn add react-morph-menu
```

## Usage

Import the `MorphMenu` component into your React project:

```javascript
import MorphMenu from "react-morph-menu/dist/MorphMenu";

const items = ["Home", "Profile", "Message", "Setting", "Photos"];

function App() {
  return (
    <MorphMenu
      indicatorShape={"circle"} // Customize the shape of the indicator
      items={items} // Array of menu items
    />
  );
}

export default App;
```

## Props

| Prop Name        | Type Description                                                          |
| ---------------- | ------------------------------------------------------------------------- |
| `indicatorShape` | `string` Shape of the indicator. See the table below for possible values. |
| `items`          | `array of strings` Array of menu item names to display.                   |

### Items Options

The `items` input is necessary .

### Indicator Shape Options

The `indicatorShape` prop determines the shape of the menu indicator. Possible values are:
The `indicatorShape` input is necessary .

| Value               | Description                                                   |
| ------------------- | ------------------------------------------------------------- |
| `circle`            | Displays the indicator as a circle.                           |
| `circle-in-item`    | Displays the indicator as a circle inside the active item.    |
| `triangle`          | Displays the indicator as a triangle.                         |
| `rectangle`         | Displays the indicator as a rectangle.                        |
| `rectangle-in-item` | Displays the indicator as a rectangle inside the active item. |

## Example

Here is a simple example using the `MorphMenu` component:

```javascript
import MorphMenu from "react-morph-menu/dist/MorphMenu";

const items = ["Dashboard", "Settings", "Notifications", "Help"];

function App() {
  return (
    <MorphMenu
      indicatorShape={"triangle"} // Set the indicator shape to triangle
      items={items} // Pass your menu items
    />
  );
}

export default App;
```

## Optional Styles

| Prop Name              | Type     | Description                                                               | Default Value                                                                                                                                   |
| ---------------------- | -------- | ------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| `indicatorWidth`       | `number` | The width of the indicator in pixels.                                     | each shape has its own width                                                                                                                    |
| `indicatorHeight`      | `number` | The height of the indicator in pixels.                                    | each shape has its own height                                                                                                                    |
| `indicatorTop`         | `number` | The top position of the indicator, relative to the menu, in pixels.       | each shape has its own top                                                                                                                    |
| `indicatorLeft`        | `number` | The left position of the indicator, relative to the menu, in pixels.      | each shape has its own left                                                                                                                    |
| `textColor`            | `string` | The text color of the menu items. Accepts any valid CSS color value.      | `#fff`                                                                                                                                          |
| `indicatorBg`          | `srting` | The background color of the indicator. Accepts any valid CSS color value. | `#01193e`                                                                                                                                       |
| `indicatorBorderColor` | `string` | The border color of the indicator. Accepts any valid CSS color value.     | This input is used in circle and rectangle shape in `#ffe4c4` color but it is better to choose its color according to the body background color |


## License

MIT

Keywords

Here are the relevant keywords to help others discover this package:

"keywords": [
  "react",
  "react-component",
  "react-menu",
  "navigation-menu",
  "menu",
  "morph-menu",
  "interactive-menu",
  "customizable-menu",
  "ui-component",
  "react-ui",
  "responsive-menu",
  "dynamic-menu",
  "menu-indicator",
  "react-navigation"
]
