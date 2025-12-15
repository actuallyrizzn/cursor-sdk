**Proposed Solution:** Add tests for timeout handling to verify default and per-request timeouts work correctly.

**Implementation:**
- Created `test_timeout.py` with comprehensive timeout tests
- Tests cover default timeout, per-request timeout override, and timeout exception propagation
- Verifies that timeout exceptions are properly wrapped as `CursorNetworkError`

**Testing:** All tests pass with 100% coverage.

