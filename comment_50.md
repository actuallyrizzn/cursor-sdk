**Proposed Solution:** Improve generic exception catching to include more context in error messages.

**Implementation:**
- Enhanced network error messages to include HTTP method and path
- Error message format: `"Request failed due to a network error: {method} {path}"`
- This provides better debugging context when network errors occur

**Testing:** All tests pass with 100% coverage.

