```
% tamarin-prover --prove --output-dot=ra.dot ra.spthy
% dot -Tpng -O ra.dot 
```

result (ra.spthy)
==============================================================================

==============================================================================

summary of summaries:

analyzed: ra.spthy

  processing time: 36.91s
  
  correctness_trace (exists-trace): verified (45 steps)

  correctness_trace_cuckoo_attack (exists-trace): verified (19 steps)

  L_correspondence (all-traces): verified (97 steps)

  L_no_replay_attack_on_verifier_fresh (all-traces): verified (3 steps)

  L_no_replay_attack_on_verifier_unique (all-traces): verified (14 steps)

  L_no_replay_attack_on_enclave_fresh (all-traces): verified (118 steps)

  L_no_replay_attack_on_enclave_unique (all-traces): verified (20 steps)

  L_integrity (all-traces): verified (122 steps)

  L_rollback1 (all-traces): verified (62 steps)

  L_rollback2 (all-traces): verified (48 steps)

  L_rollback3 (all-traces): verified (2 steps)

  L_rollback4 (all-traces): verified (2 steps)

  L_rollback5 (all-traces): verified (49 steps)

  L_rollback6 (all-traces): verified (11 steps)

  L_rollback7 (all-traces): verified (89 steps)

  L_cuckoo1 (all-traces): verified (2 steps)

  L_no_cuckoo_enclave_accept (all-traces): verified (9 steps)
  
  L_seal_key_secrecy (all-traces): verified (11 steps)

==============================================================================