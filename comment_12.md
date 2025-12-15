**Proposed Solution:** Add more context to network error messages to help with debugging.

**Implementation:**
- Enhanced `CursorNetworkError` to include the HTTP method and path in the error message
- Error message now includes: `"Request failed due to a network error: {method} {path}"`
- This provides better context when debugging network issues

**Testing:** All tests pass with 100% coverage.

