# zynko-oracle · `php-binary-parse-binary-conformance-oracle`

**A deterministic, re-checkable conformance oracle for `binary` (php).**

## Proven
Measured on the canonical Exercism corpus — **14 input/output pairs, 11 distinct outputs** — produced by *running* the reference in a sealed sandbox, not asserted.

## Scope (declared)
The corpus is the canonical Exercism test data for `binary`. Inputs outside that set are **not covered**; this oracle decides agreement on the published corpus only and makes no claim of general correctness.

## Provenance
Reference: the Exercism reference solution for `binary` (php; MIT, Exercism), body unchanged. Proven by the exercism testsuite (pin=23d04ec1c542baf5), re-executed by harvest in a sealed sandbox (unshare -rn) before this bundle was generated.

## License
Apache-2.0 for the scaffolding; the reference body retains its upstream MIT (Exercism) license.
