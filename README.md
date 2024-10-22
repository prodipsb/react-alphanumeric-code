# React Unique Alphanumeric Code Generetor

react-alphanumeric-code is a simple utility to generate random alphanumeric codes of a specified length. It generates codes using uppercase letters, lowercase letters, and digits.

### Installation

1. **You can install the package using npm:**

   ```bash
   npm install react-alphanumeric-code

### Usage:

1. Import the package into your JavaScript/Node.js project.

2. Call the uniqueID function with the desired length of the random code.


## Example:

    ```bash
    // Import the package
    const uniqueID = require('react-alphanumeric-code');

    // Generate a random code of 10 characters
    const uuid = uniqueID(10);

    console.log(uuid);  // Example output: "Ab3GhL9pRt"

In this example, the uniqueID function generates a random string of 10 characters, which includes uppercase letters, lowercase letters, and numbers.

## Parameters:

length: The number of characters for the random code. Must be a positive integer.

### Output:

`A string consisting of randomly generated alphanumeric characters.`

### Features:

Supports generating random alphanumeric codes.

Configurable code length.

Lightweight and easy to use.

### License

This package is licensed under the MIT License.

### Contribution

Contributions are welcome! Please open an issue or submit a pull request for improvements and new features.

