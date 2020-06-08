# QFormControls

Simple Quasar components based on Quasar framework.
- QTimestampPicker realises datetimepicker for timestamp fields.

## Install
````bash
$ npm install git+https://github.com/flespi-software/QFormControls.git --save
````

## Example:
QTimestampPicker:
> import {QTimestampPicker} from 'qformcontrols'
````vue
  <QTimestampPicker
    :value="timestamp"
    @input="setTimestamp"

    :date-options-fn="funcFilterDay"
    :auto-maximized="false"
    label="label"
    format="YYYY-MM-DD HH:mm:ss"
    color="orange"

    :error="isError"
    :disable="false"
    @focus="focus"
  />
````
## Requirements:

- [Node.js](https://nodejs.org/en/) (>=9.x)
- npm version 3+ and [Git](https://git-scm.com/).
- Quasar Framework 1.5+

## Demo

In progress...

## License
[MIT](https://github.com/flespi-software/QFormControls/blob/master/LICENSE) license.
