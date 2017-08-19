# React-Native notes
Personal notes using react-native on mac

## Dependencies
* XCode
* Homebrew
* Node and Watchman (Must have Homebrew installed)
  * brew install node
  * brew install watchman
* React-Native CLI
  * npm install -g react-native-cli
* To run your react-native app
  * react-native run-ios

## Libraries
* ESLint
  * npm install --save-dev eslint-config-rallycoding
* Firebase
  * npm install --save firebase
* Axios
   * npm install --save axios

## Errors/Troubleshooting
* bundling failed: "TransformError"
  * yarn remove babel-preset-react-native
  * yarn add babel-preset-react-native@2.1.0
