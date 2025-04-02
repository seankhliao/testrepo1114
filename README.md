# testrepo1114

This repo houses a set of go modules as a rouch simulation of the opentelemetry go modules.

- `a`, `b`, `d`, `e` are independent.
- `c` depends on `b`
- `f` depends on `e`

The `meta` module is a proposed "virtual" dependency for updating versions in sync.
See [seankhliao/testrepo1115](https://github.com/seankhliao/testrepo1115) for details.
