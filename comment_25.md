**Proposed Solution:** Document that long method names are intentional for API mapping.

**Implementation:**
- Added documentation to `CursorClient` class docstring explaining the design rationale
- Added note in README.md about long method names being intentional
- Documented that this ensures 1:1 mapping with API documentation and prevents naming conflicts

**Testing:** All tests pass with 100% coverage.

