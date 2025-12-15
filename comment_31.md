**Proposed Solution:** Add test to verify Authorization header cannot be overridden by extra headers.

**Implementation:**
- Created `test_header_override.py` with tests for header override protection
- Test verifies that Authorization header is always set last, preventing override
- Updated `_build_headers` to ensure Authorization is set after merging all other headers

**Testing:** All tests pass with 100% coverage.

