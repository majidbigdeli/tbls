# transactions

## Description

## Columns

| Name | Type | Default | Nullable | Children | Parents | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- | ------- |
| timestamp | INTEGER |  | true |  |  |  |
| transaction_id | STRING |  | true | [blocks](blocks.md) |  |  |
| inputs | RECORD |  | true |  |  |  |
| inputs.input_script_bytes | BYTES |  | true |  |  |  |
| inputs.input_script_string | STRING |  | true |  |  |  |
| inputs.input_script_string_error | STRING |  | true |  |  |  |
| inputs.input_sequence_number | INTEGER |  | true |  |  |  |
| inputs.input_pubkey_base58 | STRING |  | true |  |  |  |
| inputs.input_pubkey_base58_error | STRING |  | true |  |  |  |
| outputs | RECORD |  | true |  |  |  |
| outputs.output_satoshis | INTEGER |  | true |  |  |  |
| outputs.output_script_bytes | BYTES |  | true |  |  |  |
| outputs.output_script_string | STRING |  | true |  |  |  |
| outputs.output_script_string_error | STRING |  | true |  |  |  |
| outputs.output_pubkey_base58 | STRING |  | true |  |  |  |
| outputs.output_pubkey_base58_error | STRING |  | true |  |  |  |
| block_id | STRING |  | true |  | [blocks](blocks.md) |  |
| previous_block | STRING |  | true |  |  |  |
| merkle_root | STRING |  | true |  |  |  |
| nonce | INTEGER |  | true |  |  |  |
| version | INTEGER |  | true |  |  |  |
| work_terahash | INTEGER |  | true |  |  |  |
| work_error | STRING |  | true |  |  |  |

## Relations

![er](transactions.png)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)
