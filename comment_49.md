**Proposed Solution:** Convert ENDPOINT_SPECS from tuple of tuples to NamedTuple for better type safety.

**Implementation:**
- Created `EndpointSpec` NamedTuple with fields: `method`, `path`, `method_name`
- Converted all ENDPOINT_SPECS entries to use `EndpointSpec` instances
- Updated integration test to use named attributes instead of tuple unpacking
- Provides better type safety and IDE autocomplete support

**Testing:** All tests pass with 100% coverage.

