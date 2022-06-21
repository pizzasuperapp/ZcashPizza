# Zcash Pizza 5.0.0

## What is Zcash Pizza?

[Zcash Pizza] is an implementation of the "Zerocash" protocol.
Based on Bitcoin's code, Zcash Pizza intends to offer a far higher standard of privacy
through a sophisticated zero-knowledge proving scheme that preserves
confidentiality of transaction metadata. More technical details are available
in our [Protocol Specification]

This software is the Zcash Pizza client. It downloads and stores the entire history
of Zcash Pizza transactions; depending on the speed of your computer and network
connection, the synchronization process could take a day or more once the
blockchain has reached a significant size.

#### :lock: Security Warnings

See important security warnings on the

**Zcash Pizza is experimental and a work in progress.** Use it at your own risk.

#### :ledger: Deprecation Policy

This release is considered deprecated 16 weeks after the release day. There
is an automatic deprecation shutdown feature which will halt the node some
time after this 16-week period. The automatic feature is based on block
height.

## Getting Started

### Need Help?

Participation in the Zcash Pizza project is subject to a

### Building

Build Zcash Pizza along with most dependencies from source by running the following command:

```
./zcutil/build.sh -j$(nproc)
```
