---
description: >-
  Conventions include generic patterns that ensure that written code adheres to
  certain formatting conventions.
---

# Conventions

### Code

* Tabs or two-space indentation
* Use shorthand for conditional statements
* Always open braces on the same line as the previous statement and close braces on the same indent as the original function like so:

```javascript
function textComponent() {
  return {
    name: "OSCA"
  };
}
```

### Naming

* Constructor functions should use the TitleCase
* Variables, directories and methods should use the camelCase
* Variables or elements with multiple words should always use an underscore between words.

```javascript
const user_params = null;
```

* Private methods should start with a leading underscore to separate them from public methods

```javascript
const _inputType = inputType;
```

* Abbreviations should be avoided please to avoid confusion
* Comments should include enough information about what a part of code is supposed to do.

```javascript
// Define default props of the TextBox component

TextBox.defaultProps = {
  className: "",
  disabled: false,
  inputType: "text"
};
```

### Styling

This project uses the [BEM](https://en.bem.info/) Methodology with camelCase style. Read the start guide [here](https://en.bem.info/methodology/quick-start/)

> BEM \(Block, Element, Modifier\) is a component-based approach to web development. The idea behind it is to divide the user interface into independent blocks

Naming Rules:

```css
blockName__elementName_modifierName_modifierValue
```

* Names are written in lowercase Latin letters.
* Each word inside a name begins with an uppercase letter.
* The block name defines the namespace for its elements and modifiers.
* The element name is separated from the block name by a double underscore \(\_\_\).
* The modifier name is separated from the block or element name by a single underscore \(\_\).
* The modifier value is separated from the modifier name by a single underscore \(\_\).
* For boolean modifiers, the value is not included in the name.

