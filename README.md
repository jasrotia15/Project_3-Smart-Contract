# Project_3-Smart-Contract(Error Handling)
This Solidity smart contract demonstrates different error handling techniques using `assert`, `revert`, and `require` functions. This Solidity smart contract provides functionality to handle weather conditions and suncreen requirements. It allows for checking the weather, changing the weather condition, getting the number of weather calls, and determining if a suncreen is needed based on the weather condition.

# Contract Details
# Prerequisites
Solidity version: 0.8.18

# Contract Variables
- **sunny (boolean)**: Represents the current weather condition. Initialized to true.
- **suncreen(boolean)**: Indicates whether a suncreen is needed. Initialized to false.
- **finalCall (uint)**: Tracks the number of times the weather function has been called. Initialized to 0.

# Contract Functions
- **weather()**: Checks the weather condition and increments the finalCall count by 3. Throws an error if the weather is not sunny.
- **weatherChanger()**: Toggles the value of the sunny variable to switch the weather condition.
- **getCal()**: Retrieves the current value of finalCall.
- **BringSuncreen()**: Checks the weather condition and sets the suncreen variable to true if it is sunny. Otherwise, reverts with an error message indicating that no suncreen is needed.

# License
This code is released under the MIT License. You can find the full license text in the SPDX-License-Identifier comment at the beginning of the contract.
