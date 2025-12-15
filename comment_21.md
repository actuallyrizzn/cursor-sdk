**Proposed Solution:** Document API versioning strategy and endpoint version information.

**Implementation:**
- Added API version documentation to README.md explaining:
  - `/v0/*` endpoints are part of the v0 API
  - Non-prefixed endpoints are versioned independently
- Added comprehensive docstring to `CursorClient` class explaining versioning
- Documented that method names are intentionally long for 1:1 API mapping

**Testing:** All tests pass with 100% coverage.

