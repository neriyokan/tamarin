```
% tamarin-prover --prove --output-dot=ra.dot ra.spthy
% dot -Tpng -O ra.dot 
```

result (ra.spthy)
==============================================================================

==============================================================================
summary of summaries:

analyzed: ra.spthy

  processing time: 28.82s
  
  correctness_trace (exists-trace): verified (43 steps)

  correctness_trace_cuckoo_attack (exists-trace): verified (23 steps)

  L_no_replay_attack_on_verifier_fresh (all-traces): verified (3 steps)

  L_no_replay_attack_on_verifier_unique (all-traces): verified (14 steps)

  L_integrity1 (all-traces): verified (80 steps)

  L_integrity2 (all-traces): verified (5 steps)

  L_rollback1 (all-traces): verified (58 steps)

  L_rollback2 (all-traces): verified (88 steps)

  L_rollback3 (all-traces): verified (2 steps)

  L_rollback4 (all-traces): verified (2 steps)

  L_rollback5 (all-traces): verified (70 steps)

  L_rollback6 (all-traces): verified (19 steps)

  L_rollback7 (all-traces): verified (35 steps)
  
  L_cuckoo1 (all-traces): verified (2 steps)

  L_no_cuckoo_enclave_accept (all-traces): verified (51 steps)
  
  L_seal_key_secrecy (all-traces): verified (9 steps)

==============================================================================