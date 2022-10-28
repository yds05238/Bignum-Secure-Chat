# RSA

RSA packages to support key-generation, encryption, and decryption. RSA is configured to be 4096 bits and PKCS1 OAEP.

## Sections

- basic: slow, unoptimized RSA package
- fast: fast, performance-optimized RSA package
- lib: built header-only RSA library for external use
- test: code to unit test + performance test 

## Functionalities

- generate_keys(): generate rsa private, public keys (4096 bits)
- encrypt(public key, message)
- decrypt(private key, message)

## TODO

- Add OAEP padding 
    - hash algorithm/function: SHA-1 (minimum SHA-256)
    - mask generation function (MFG): MGF1
    - label (L: used in OAEP encoding): "" (empty string)
    
