# (Mis)Binding Raw Public Keys with Identities in TLS
---

This repository contains the ProVerif models of TLS with raw public key (RPK), TLS with self-signed certificates, and WireGuard protocols. The protocols use public keys that are not authenticated or verified by certificate authorities (CA). The purpose of the models is to check whether there are attacks on server or client authentication when there are no CAs. The models follow the standards and specifications closely. This work pertains to the paper titled (Mis)Binding Raw Public Keys with Identities in TLS.

## Models

### TLS RPK

- [Server authentication and key exchange with DANE](models/TLS-RPK-DANE.pv)
- [Mutual authentication and key exchange with DANE](models/mTLS-RPK-DANE.pv)
- [Mutual authentication and key exchange with pre-configured keys](models/mTLS-RPK-trusted-keys.pv)

### TLS with self-signed certificates

- [Server authentication and key exchange with DANE](models/TLS-SSC-DANE.pv)

### WireGuard

- [Mutual authentication between initiator and responder using pre-configured keys in cryptokey routing table](models/WG.pv)



