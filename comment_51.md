**Proposed Solution:** Handle silent JSON parse failures by adding proper exception handling and fallback behavior.

**Implementation:**
- Added try-except for JSON parsing even when content-type indicates JSON
- Handles both `ValueError` and `TypeError` exceptions
- Falls back to text when JSON parsing fails despite content-type
- Added comments explaining the fallback behavior

**Testing:** All tests pass with 100% coverage.

