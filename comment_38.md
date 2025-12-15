**Proposed Solution:** Add comprehensive tests for error response parsing to cover all error formats.

**Implementation:**
- Created `test_error_response_parsing.py` with tests for:
  - Error with 'message' field
  - Error with 'error' field
  - Error with both fields (message takes priority)
  - Nested error objects
  - Non-dict JSON body
  - Text body errors
  - Empty body errors
- Improved error message extraction logic with better comments

**Testing:** All tests pass with 100% coverage.

