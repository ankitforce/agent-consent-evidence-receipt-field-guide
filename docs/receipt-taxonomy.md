# Receipt Taxonomy

## Trace

A trace records low-level execution details. It is best for debugging.

## Audit Log

An audit log records events for governance and compliance. It is best for reconstructing who did what and when.

## Consent Record

A consent record captures permission: who approved which action under which scope.

## Evidence Bundle

An evidence bundle links claims to sources, retrieved documents, tool outputs, or replayable artifacts.

## Agent Consent And Evidence Receipt

A receipt combines the minimum useful parts of the above into one compact object:

- request
- authority
- actor
- environment
- evidence
- actions
- verification
- residual risk

The receipt is not a replacement for traces or audit archives. It is the product-facing summary that makes delegated agent action reviewable.
