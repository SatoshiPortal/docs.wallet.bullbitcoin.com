+++
title = "Watch-Only Wallets"
description = "Descriptors, xpub, ypub, zpub…"
date = 2025-07-04
authors = ["ethicnology"]

[taxonomies]
categories = ["guides"]
tags = ["watch only", "ColdCard Q", "wallet"]

[extra]
toc = true
+++

`BULL` supports multiple watch-only wallet standards, including:

- **BIP44** (Legacy)
- **BIP49** (Nested SegWit)
- **BIP84** (Native SegWit)

## Supported Input Formats

You can **scan or paste** a variety of key formats:

> **Note:** The following values are someone else's keys. Do not reuse them with real funds.


- **xpub** (legacy):  
  `xpub6DJwRncrB8eNrzUq8XxgjwCZsEeWP8FeqBJbJQZ8JfuDwLdAzyjhHiHJieNuar1wjQTyihhMWtaKGE4DUd8uBgtyrNJqF5drwbNVUqb83b7`

- **ypub** (nested SegWit):  
  `ypub6XepkBPvLjJ2P2XHVUEoYfYBUaHwg39ESnmxbs6UFHwk6rRAjanUahAm6cnmEBRytL2bvE7BZ7XpyDz9DP86yaReJNRD3KfVdCQM5YZ6LEs`

- **zpub** (native SegWit):  
  `zpub6ro6vd6Cn6apSQsrXVTE8d6UkygMYj1eAoXW9yUwbE2c1sfSQw2sEMyA4gGtxMpHv64NkoJdSYR7aEnJgUNNoQw7QZnys1vZ1qefVwPVc8T`

- **Descriptor (P2PKH / BIP44):**  
  `pkh([86241f88/44h/0h/0h]xpub6DJwRncrB8eNrzUq8XxgjwCZsEeWP8FeqBJbJQZ8JfuDwLdAzyjhHiHJieNuar1wjQTyihhMWtaKGE4DUd8uBgtyrNJqF5drwbNVUqb83b7/<0;1>/*)#fzh6clmf`

- **Descriptor (P2SH-P2WPKH / BIP49):**  
  `sh(wpkh([86241f88/49h/0h/0h]xpub6CpZSWj1C3kYXjLAf7TBLaSgJc9VjR9jXgFjpUCasHZs3kbwUvcuxdWd5QqBEGn4UguoAkWd6TBH5wNaVgi6BLk3S2inTQr1MULhgxnrxKW/<0;1>/*))#6nkjq52v`

- **Descriptor (P2WPKH / BIP84):**  
  `wpkh([86241f88/84h/0h/0h]xpub6D8aKHkNUjVrjpVcrmsyiSuUR3PTfV2eLaV4bBhAqDGqug2yuchjzEet2GMixYWT6opmFr7WXDi1ofZBF5YMCwZuftQ8hCHaUPXNiqfJvLs/<0;1>/*)#ht0s3dna`

> **Note:** 
> -  [ColdCard Export Single Signature Descriptors](https://coldcard.com/docs/descriptor_export/#single-signature-descriptor-examples)



## Import Watch-Only in `BULL`

### Tap the import button in the settings
<img src="/bull/watch-only/watch-only_settings.png" alt="ColdCard Q Advanced Tools" style="max-width: 50%; height: auto;">

### Tap `Scan QR` or the `paste` button with your descriptor in clipboard
<img src="/bull/watch-only/watch-only_import.png" alt="ColdCard Q Advanced Tools" style="max-width: 50%; height: auto;">

### Review the details, add an optional label and tap `Import`
<img src="/bull/watch-only/watch-only_label.png" alt="ColdCard Q Advanced Tools" style="max-width: 50%; height: auto;">


