# Organization profile audit

Inspected public main `153098e205882f9d75859f1c49559b6ab2445d6c`.
Classification: organization documentation. Prepared on a separate audit branch.

- HIGH: prior profile asserted a Qyoo-shape restriction while software licenses
  offer BSD-3-Clause. Owner/legal review must distinguish copyright, patent and
  trademark matters; no enforceable restriction or patent status was invented.
- MEDIUM: unsupported scan-performance comparisons, blanket privacy claims,
  circuit cost, partnership assertions and blockchain rollout language lacked
  repository evidence. Replaced with bounded product/tool descriptions.
- MEDIUM: public tools represented multiple generations; profile now separates
  product capabilities, historical demonstrations, experimental contracts and
  research. It does not advertise signature-cell/CRC-10 as shipped.
- LOW: prose no longer implies these six repositories include the entire hosted
  product. Original BSD license retained.

Verification: `git diff --check` PASS. Manual review of four public-main commits,
tracked files, links and licensing language PASS within stated limits. Redacted
history pattern scan: no credential matches; this is not an exhaustive secret or
legal audit. Public target URLs are repository links; no release/push/merge was
performed. Legal approval remains a publication gate for rights statements.
