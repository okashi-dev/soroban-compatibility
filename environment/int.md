# `int`

```
✅ obj_from_u64
✅ obj_to_u64
✅ obj_from_i64
✅ obj_to_i64
✅ obj_from_u128_pieces
✅ obj_to_u128_lo64
✅ obj_to_u128_hi64
✅ obj_from_i128_pieces
✅ obj_to_i128_lo64
✅ obj_to_i128_hi64
✅ obj_from_u256_pieces
✅ u256_val_from_be_bytes
✅ u256_val_to_be_bytes
🟥 obj_to_u256_hi_hi // Can't find contract code examples that produce a call to this function.
🟥 obj_to_u256_hi_lo // Can't find contract code examples that produce a call to this function.
🟥 obj_to_u256_lo_hi // Can't find contract code examples that produce a call to this function.
🟥 obj_to_u256_lo_lo // Can't find contract code examples that produce a call to this function.
✅ obj_from_i256_pieces
✅ i256_val_from_be_bytes
✅ i256_val_to_be_bytes
🟥 obj_to_i256_hi_hi // Can't find contract code examples that produce a call to this function.
🟥 obj_to_i256_hi_lo // Can't find contract code examples that produce a call to this function.
🟥 obj_to_i256_lo_hi // Can't find contract code examples that produce a call to this function.
🟥 obj_to_i256_lo_lo // Can't find contract code examples that produce a call to this function.
✅ u256_add
✅ u256_sub
✅ u256_mul
✅ u256_div
✅ u256_rem_euclid
✅ u256_pow
✅ u256_shl
✅ u256_shr
✅ i256_add
✅ i256_sub
✅ i256_mul
✅ i256_div
✅ i256_rem_euclid
✅ i256_pow
✅ i256_shl
✅ i256_shr
🟥 timepoint_obj_from_u64 // The Soroban SDK generates contract spec as scSpecTypeUdt instead of scSpecTypeTimepoint.
🟥 timepoint_obj_to_u64 // The Soroban SDK generates contract spec as scSpecTypeUdt instead of scSpecTypeTimepoint.
🟥 duration_obj_from_u64 // The Soroban SDK generates contract spec as scSpecTypeUdt instead of scSpecTypeDuration.
🟥 duration_obj_to_u64 // The Soroban SDK generates contract spec as scSpecTypeUdt instead of scSpecTypeDuration.
```

`72.73%` Completion