# What is this?

Get Language name and native from language code

# installation

`npm i language-native-by-code --save`

Then...

let languageDetailByCode = require('language-native-by-code')

let languageDetail = languageDetailByCode('hi');

`{ code: 'en', name: 'English', dir: 1, native: 'English' }`