# Error Handling Guidelines 🚦

## Introduction

This document outlines the guidelines for error messages in our code repository. We want to ensure that error messages are formatted consistently and do not include newline characters, as this can disrupt testing and matching messages.

## Error Message Format 🔍

All error messages in this code repository should follow the same format. Each error message should start with 'ERROR:', followed by the specific error description. Error descriptions should adhere to the following patterns:

- For updates, use the following format:
  - `ERROR:(.*?)Update`

- For deletions, use the following format:
  - `ERROR:(.*?)Delete`

- For employee-related errors, use the following format:
  - `ERROR:(.*?)Employee`

By adhering to these formats, we maintain consistency in our error messages and make it easier for developers to understand and handle errors.

## Handling Newline Characters ⚠️

It's crucial that error messages do not include newline characters. Newline characters can make it difficult to match messages in tests. Be sure to avoid using '\n' or any other newline character in your error messages.

## Example 📜

Here's an example of a correctly formatted error message:

'ERROR: not valid Id To Update' or 'ERROR: AN invalId Id To update'. Anything in between 'ERROR:' and 'U/update' shouldn't matter when testing with test_with_errors.yaml file.

### Responsibility Reminder 📢

It is your responsibility to edit your error messages to comply with the assignment PDF when submitting.

Please follow these guidelines when creating error messages in our codebase. Consistency in error messages enhances the debugging process and improves the overall quality of our code.

If you have any questions or need further clarification, please don't hesitate to reach out to the team.

Happy coding! 🚀
