# File-Name-Validator
Code Challenge from JP Morgan

Given a file location, the program should validate the filename. If the file is invalid, it should print the error details along with the status of the file as passed or failed. The file name format should:

**Test_<portfoliocode>_<ddmmyyyy>_<2digit-sequencenumber>.csv**
  
Where:
- Test – hardcoded string prefix
- \<portfoliocode> - can only be A, B, C
- \<ddmmyyyy>– is valuation date format dd e.g 07, mm e.g 12, yyyy e.g 1987.
- <2digit-sequencenumber> - is 2 digit sequence number

**Test Input and expected output**

| **Filename** | **Expected Output** |
|:---------|:----------------|
| Test_A_07121987.csv	| File ‘Test_A_07121987.csv’ passed validation. |
| Test_E_07121987.csv	| File ‘Test_E_07121987.csv’ failed validation. PortfolioCode should be A/B/C found E. |
| Test_A_13121987.csv	| File ‘Test_A_13121987.csv’ failed validation. Valuation Date is not a valid date format ‘ddmmyyyy’. |
| Hello_A_07121987.csv	| File ‘Hello_A_07121987.csv’ failed validation. Prefix for the file should be ‘Test’ found ‘Hello’. |
| Test_A_07121987.txt	| File ‘Test_A_07121987.txt’ failed validation. Invalid File format.Expected ‘csv’ found ‘txt’. |
| Test.txt	| File ‘Test.txt’ failed validation. File format should be ‘Test_<portfoliocode>_<ddmmyyyy>_<2digit-sequencenumber>.csv’ |
  



## Prerequisites


## How to use


## Unit Test


## Assumption & Enhencements


## Authors

* **[Hongyi Lin](https://github.com/Hongyil1)**

## License

This project is licensed under the MIT License

## Demo
