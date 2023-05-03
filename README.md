# phone-number-formatter

A JavaScript package for formatting phone numbers.

## Installation

To install the package, run:  npm i phone-number-helper


## Usage

To use the package, first import the `createPhoneNumber` function:

```javascript
import {createPhoneNumber} from "phone-number-helper";

const phoneNumber = [1,2,3,4,5,6,7,8,9,0];
const formattedPhoneNumber = formatPhoneNumber(phoneNumber);

console.log(formattedPhoneNumber); // Output: (123) 456-7890
