# typepulse-alarms
This table is used to showcase the type confusion bugs detected by TypePulse.

| Bug type  | Report | Trophy | Impacts |
| ------------- | ------------- | -------- | ---------- |
| Misalign  | [Unsound implementation of `video::AssetPtr::<T>::get`](https://github.com/sciter-sdk/rust-sciter/issues/143)  | RESERVERED CVE | OOB |
| Misalign / Mismatched Scope  | [Unsound implementation in `instruction::unpack`](https://github.com/solana-labs/solana-program-library/issues/5243#issuecomment-2566105089)  | [RUSTSEC-2024-0426](https://rustsec.org/advisories/RUSTSEC-2024-0426.html) | Panic / Illegal type |
