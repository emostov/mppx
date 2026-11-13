---
'mppx': patch
---

Added `Signer` to `mppx/extensions/identity`, so `WebBotAuth.Client.prover` and `Tap.Client.prover` can sign with a key held outside WebCrypto, such as in a KMS, an HSM or a remote signing service.
