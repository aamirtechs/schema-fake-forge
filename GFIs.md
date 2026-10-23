## Add YAML input support
Accept OpenAPI and JSON Schema pasted as YAML in addition to JSON.
Keep parsing local and add tests for a small YAML subset.

## Add more format generators
Add date, time, hostname and ipv4 format handling in the generator.
Cover each new format with a unit test.

## Add array of schemas (oneOf) support
Support a small oneOf picker that chooses a branch with the seeded RNG.
Document the behaviour in the README.
