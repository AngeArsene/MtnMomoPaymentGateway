# Changelog

All notable changes to this project will be documented in this file.

## [1.0.0] - 2025-04-15

### Added

- Implemented the `request_to_pay` functionality, which allows making payment requests to a specified customer number.
  - Generates a unique transaction ID for each payment request.
  - Sends a POST request to the MTN MoMo API with the required headers and body.
  - Handles HTTP responses and exceptions, returning either the `ApiUserService` instance or the HTTP status code.
