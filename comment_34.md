**Proposed Solution:** Add tests for content-type edge cases to ensure robust response parsing.

**Implementation:**
- Created `test_content_type_edge_cases.py` with tests for:
  - Missing content-type header
  - Malformed content-type
  - Content-type with charset parameter
  - Various JSON content-type variants
  - Invalid JSON fallback to text
- Enhanced JSON parsing to handle `TypeError` in addition to `ValueError`

**Testing:** All tests pass with 100% coverage.

