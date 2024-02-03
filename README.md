# Detergent production

## Description
The Detergent Production Contract is a smart contract written in Solidity for managing quality checks performed during the production of detergent batches. It allows for performing quality checks on specific batches and retrieving the status of quality checks for a given batch number.

## Features
- **Quality Check**: The contract provides a function `performQualityCheck` to perform a quality check for a given batch number. Once performed, the batch number is marked as having undergone a quality check.
- **Quality Check Status**: The contract offers a function `isQualityCheckPassed` to check the status of the quality check for a given batch number. It asserts that a quality check has been performed for the batch number and returns the result.

## Functions
1. **performQualityCheck**: Perform a quality check for a specified batch number.
2. **isQualityCheckPassed**: Check if a quality check has been passed for a specified batch number.

## Usage
1. **Performing Quality Check**: Call the `performQualityCheck` function with the batch number as an argument to perform a quality check.
2. **Checking Quality Check Status**: Call the `isQualityCheckPassed` function with the batch number as an argument to verify the quality check status.


## License
This contract is licensed under the MIT License.

## Author 

punithrajv13@gmail.com
