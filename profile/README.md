# Qyoo

Qyoo (pronounced “Q”) is maintained by **Pushplay LLC** and connects a
recognizable visual symbol to digital experiences.
The Qyoo 4.0 product combines iOS scanning and web resolution with web content,
interactive experiences, native actions and augmented reality.

The visual carrier holds a **36-bit identifier** in a 6×6 grid. A resolver maps
that identifier to an experience; the symbol itself does not store a URL or an
experience manifest. Decimal, binary and Base36 links can represent the same ID.

## Public libraries and tools

| Repository | Purpose and status |
|---|---|
| [QyooDetector-CPP](https://github.com/qyoocode/QyooDetector-CPP) | Reference classical detector core with a public C interface and documented qualification limits. |
| [QyooDetector-iOS](https://github.com/qyoocode/QyooDetector-iOS) | Reference Swift Package wrapping the native detector. Consumer app integration is separately qualified. |
| [QyooGenerate-C](https://github.com/qyoocode/QyooGenerate-C) | Historical command-line PNG/SVG generator; reference geometry. |
| [QyooGenerate-PHP](https://github.com/qyoocode/QyooGenerate-PHP) | Historical server-side PNG generator; reference geometry. |
| [QyooGenerate-Python](https://github.com/qyoocode/QyooGenerate-Python) | Reference synthetic renderer/dataset source and experimental ML/Core ML code; unverified assets excluded from the current tree. |
| [Qyoo-Contract-Eth](https://github.com/qyoocode/Qyoo-Contract-Eth) | Experimental ERC-721 Registry/Minter protocol with a Sepolia testnet deployment. This is separate from consumer application availability. |

These repositories expose different generations of the implementation. Matching
payload ordering does not imply identical rendering or camera performance.
The Python ML demonstration is not the Qyoo 4.0 shipping scanner. The complete
hosted service and consumer application are not distributed by these six repos.

## Product, history and research

Qyoo 4.0's experience architecture uses Manifest v1 to describe web, interactive
web, redirect, native-action and AR content. Availability depends on the client,
experience and service configuration. Examples do not establish support on every
device or a scanning success rate.

Earlier Qyoo demonstrations explored contextual content and physical interactions.
They are historical evidence, not promises of current services. There is no
comparative camera benchmark or blanket privacy/personalization guarantee in this
profile. Consult the current product's privacy information before sharing data.

Future physical-symbol designs, including signature cells and CRC-10, remain
research until implemented and qualified in a published version. Sepolia ownership
and issuance experiments do not establish a Mainnet deployment, a public minting
service, a marketplace or cross-chain ownership.

## Licensing and contributions

Qyoo-owned software uses **BSD-3-Clause**, subject to each repository’s existing
copyright notices. Third-party code retains its applicable license, including
Boost, libgd and MIT notices. Previously MIT-licensed contract files keep those
grants. See each repository’s LICENSE and third-party notices for exact scope.

Qyoo is the project and product name used by Pushplay LLC. Name and branding
statements are separate from the BSD software license; this profile imposes no
additional restriction on use of the Qyoo visual shape. It makes no claim about
patent status or a patent license.

Report defects with the repository revision, reproducible input and observed
result. For suspected credentials or vulnerabilities, use GitHub's private
vulnerability reporting where available; do not post secrets in public issues.
