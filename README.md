# React-Native-Input-Style

Styled Input With Animation For React Native

## Installation

Use the package manager yarn / npm to install React-Native-Input-S.

```bash
npm install react-native-input-style --save

or

yarn add react-native-input-style
```

## Example

### Outlined example:

![outlined](https://i.imgur.com/N7qKaFp.gif)

### Regular example:

![regular](https://i.imgur.com/bFb7ALG.gif)

## Usage

```js
import Input from 'react-native-input-style';

<Input
  onlyEnglish
  id="name"
  label="Full Name"
  keyboardType="default"
  required
  contain=" "
  autoCapitalize="sentences"
  errorText="Your name is invalid"
  onInputChange={**YOUR_InputChangeHandler**}
  initialValue=""
  outlined
  borderColor="blue"
  />

<Input
  id="password"
  label="password"
  keyboardType="default"
  secureTextEntry
  required
  submit={!isSignup && authHandler}
  minLength={6}
  maxLength={20}
  autoCapitalize="none"
  errorText="Your password is invalid"
  onInputChange={**YOUR_InputChangeHandler**}
  initialValue=""
  outlined
  borderColor="blue"
  />

```

## Props

All the options of [React-Native-textinput](https://reactnative.dev/docs/textinput)

also:

| Property                | Type     | Default | Description                                  |
| ----------------------- | -------- | ------- | -------------------------------------------- |
| id                      | string   | ------- | Id of input value                            |
| label                   | string   | ------- | Label of input type.                         |
| required                | boolean  | false   | The input value is necessary                 |
| submit                  | function | ------- | On submit editing                            |
| minLength               | number   | ------- | Minimum digits for value                     |
| maxLength               | number   | ------- | Maximum digits for value                     |
| min                     | number   | ------- | Minimum value of input value                 |
| max                     | number   | ------- | Maximum value of input value                 |
| email                   | boolean  | false   | Input supposed to be email                   |
| maxLength               | boolean  | ------- | Maximum digits for value                     |
| maxLength               | boolean  | ------- | Maximum digits for value                     |
| maxLength               | boolean  | ------- | Maximum digits for value                     |
| contain                 | string   | ------- | Input has to contain value                   |
| errorText               | string   | ------- | Error text under the value                   |
| onInputChange           | function | ------- | Input change function                        |
| initialValue            | string   | ------- | Initial value of input                       |
| initiallyValid          | boolean  | false   | Initial value is valid                       |
| outlined                | boolean  | false   | Type of the input style                      |
| borderColor             | string   | gray    | Color of border                              |
| fontSize (for outlined) | number   | 18      | Start font size of label in input            |
| right                   | boolean  | false   | If label and error text should be right side |
| formControlStyle        | object   | ------- | Specific style of form control               |
| errorContainerStyle     | object   | ------- | Specific style of error container            |
| errorText               | object   | ------- | Specific style of error text                 |
| labelStyle              | object   | ------- | Specific style of label                      |
| inputStyle              | object   | ------- | Specific style of input                      |

## Author

Rom Ovadia

[CD-ROM](https://github.com/rom529)

## License

[MIT](https://choosealicense.com/licenses/mit/)
