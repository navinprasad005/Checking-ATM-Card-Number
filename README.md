Checking-ATM-Card-Number:

* For an online payment Customers need to provide their Debit Card Number. The transactional site receives only a special type of Cards. Cards which possess following Criterion, through those only payment is possible.
  -	Criterion 1: It should be a 14-digit number.
  -	Criterion 2: 3 Digits- 4 Digits - 4 Digits - 3 Digits
  -	Criterion 3: There should not be any special characters apart for "-" or letters.
  -	Criterion 4: There should not be any 3 consecutive repeated digits.
  -	Criterion 5: There should not be any 0 in first three digits.
  -	Criterion 6: Alternative group must end with same Digit. As in the first and third group of numbers must end with same digit and the second and forth group of numbers must end     with same digits.
* If any of the Criterion does not get satisfied show the "Card number is Invalid" otherwise show "Card number is valid"

Example:
Input: Provide the Card Number: 123-2345-2343-235
Output: Card number is valid
