## Myanmar Mobile Phone Number Validator

**Description:**
This project validates Myanmar mobile phone numbers and returns information about them.

**Features:**

* Validates Myanmar mobile phone numbers.
* Returns detailed information about the validated number, including:
    * Operator code
    * Operator name

**Example Usage:**

```javascript
import Validator from 'myanmar-mobile-validator';

const number1 = '+95 09 294 293 134';
const number2 = '၉၅ ၀၉ ၂၉၄ ၂၉၃ ၁၃၄'; // Myanmar Unicode

const info1 = Validator(number1);
const info2 = Validator(number2);

console.log(info1); // Object containing information about the number
console.log(info2); // Object containing information about the number (if valid)

if (!info1 || !info2) {
  console.log('Invalid Myanmar mobile phone number');
}
```

## Refrence
https://www.ptd.gov.mm/LicenseslistDetail.aspx?id=P3KMgPdor32H5hDW/BFdTw==
