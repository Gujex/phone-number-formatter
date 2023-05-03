# phone-number-formatter

create-phone-number is a JavaScript package that provides a function for generating a formatted phone number from an array of digits. Given an array of 10 digits, the function creates a string in the format (XXX) XXX-XXXX, where X represents a digit from the input array. The package simplifies the process of generating formatted phone numbers in JavaScript projects.

## Installation

To install the package, run:  npm i phone-number-helper


## Usage

To use the package, first import the `createPhoneNumber` function:

```javascript
import {createPhoneNumber} from "phone-number-helper";

const phoneNumber = [1,2,3,4,5,6,7,8,9,0];
const formattedPhoneNumber = formatPhoneNumber(phoneNumber);

console.log(formattedPhoneNumber); // Output: (123) 456-7890
