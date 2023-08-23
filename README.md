# CMERON - Configuration Management and Extended Resource and Object Notation

CMERON is a JSON extension that offers more features while still remaining a subset of JavaScript. It aims to enhance the readability and flexibility of configuration files and data serialization by introducing additional functionalities while keeping compatibility with the JSON standard.

## Features 🔥

- ✍️ **Comments:** CMERON introduces the ability to add comments within your configuration files. Both single-line and multi-line comments are supported, allowing you to annotate your code for better understanding.

- 📜 **Final Commas:** You no longer need to worry about trailing commas in arrays and objects. CMERON allows you to include a comma after the last element, making it easier to manage and modify your data structures.

- 🗓️ **Date Objects:** CMERON extends JSON by including support for date objects. You can represent dates using the `new Date()` syntax with either milliseconds or year, month, day, hour, minute, second, and millisecond parameters.

- 📝 **Template Literals:** For multi-line strings, CMERON introduces template literals similar to those in JavaScript. This feature enhances the readability of your configuration files by allowing you to structure your strings across multiple lines.

- 🔑 **Keys Without Quotes:** CMERON provides the convenience of using unquoted keys in objects. This feature streamlines the writing process and makes your configuration files cleaner.

- 🧮 **BigInt Literals:** If you're dealing with large integer values, CMERON allows you to use BigInt literals by appending the `n` suffix. This is especially useful when precision matters.

- 🧵 **Regex Literals:** Regular expressions are a powerful tool in JavaScript, and CMERON embraces this by including support for regular expression literals in your configuration.

## Example Usage 🌟

```cmeron
{
  // CMERON example showcasing its features
  title: "CMERON Features Demo",
  created: new Date(1672812000000),
  content: `
    CMERON is amazing for writing configuration files.
    You can even use template literals for multi-line content!
    Isn't that cool?
  `,
  settings: {
    enableFeatureX: true,
    enableFeatureY: false,
    maxRequestsPerMinute: 100n,
    apiEndpoint: /\/api\/v\d+\//
  }
}
```
