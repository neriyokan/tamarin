```
% tamarin-prover --prove --output-dot=ra.dot ra.spthy -DREPLAY -DINTEGRITY -DROLLBACK -DCUCKOO
% dot -Tpng -O ra.dot 
```

result (ra.spthy)
==============================================================================
summary of summaries:

analyzed: ra.spthy

  processing time: 21.32s
  
  correctness_trace (exists-trace): verified (57 steps)

  L_no_replay_attack_on_verifier_fresh (all-traces): verified (3 steps)

  L_no_replay_attack_on_verifier_unique (all-traces): verified (8 steps)

  L_integrity1 (all-traces): verified (25 steps)

  L_integrity2 (all-traces): verified (22 steps)

  L_rollback1 (all-traces): verified (20 steps)

  L_rollback2 (all-traces): verified (251 steps)

  L_rollback3 (all-traces): verified (2 steps)

  L_rollback4 (all-traces): verified (2 steps)

  L_rollback5 (all-traces): verified (22 steps)

  L_rollback6 (all-traces): verified (73 steps)

  L_rollback7 (all-traces): verified (19 steps)

  L_cuckoo1 (all-traces): verified (6 steps)

  L_cuckoo2 (all-traces): falsified - found trace (11 steps)
  
  L_seal_key_secrecy (all-traces): verified (6 steps)

==============================================================================