# AES 

AES packages to support key-generation, encryption, and decryption. AES is configured to run in either GCM or CBC (with changing IV).

## Sections

- basic: slow, unoptimized AES package
- fast: fast, performance-optimized AES package
- lib: built header-only AES library for external use
- test: code to unit test + performance test

## Functionalities

- generate_keys(): generate aes key (256 bits)
- encrypt(key, message) 
- decrypt(key, message)

## TODO

- Add GCM or CBC configuration 
