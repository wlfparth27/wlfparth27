# Zero-Knowledge Client-Side Encrypted Vault

Status: planned

A privacy-first web architecture where encryption and decryption happen in the browser before data is sent anywhere. The backend is intended to act as a blind storage layer for opaque ciphertext.

## Security boundary

The frontend handles file selection and encrypted data flows. The cryptographic engine handles key derivation and encryption. The backend stores and serves encrypted byte streams without receiving keys or plaintext.

## Planned stack

- React frontend
- Python backend
- Web Crypto API
- PBKDF2 or Argon2 for key derivation
- AES-GCM for symmetric encryption
- C compiled to WebAssembly for a custom cipher

## Planned phases

1. Crypto foundation
2. Blind storage API
3. Frontend integration
4. WebAssembly integration

Nothing here is implemented yet. This is the starting point for the project.
