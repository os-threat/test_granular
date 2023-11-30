# test_granular

This Jupyter lab notebook tests for attribute/role idempotency in two ways
1. It checks ternary relations
2. It checks has relations

The results are clear. Ternary independently named relations on attributes work correctly and are not idempotent, whereas binary, local relations, basically attribute owns attribute is idempotent and do not work