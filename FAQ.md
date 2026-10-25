# Frequently asked questions

### What is Qyoo?

Qyoo is a visual information system maintained by Pushplay LLC. Its recognizable
symbol carries a 36-bit identifier in a 6×6 grid. A resolver maps that identifier
to digital content or an experience.

### How does it compare with QR codes?

Qyoo’s carrier and identifier format differ from QR. Experiences can use supported
client and web capabilities; neither format guarantees static or interactive
content. These repositories provide no comparative camera-performance benchmark.

### Can I use the code in my own projects?

Qyoo-owned software uses BSD-3-Clause. Preserve existing copyright and license
notices and the applicable third-party licenses. Previously MIT-licensed contract
files retain their grants. See the individual repository for exact scope.
No additional exclusive-shape restriction is imposed by this profile.

### Which repositories are production-supported?

The public detector and generator repositories are reference implementations with
documented input, geometry and qualification limits. ML/Core ML and Ethereum work
is experimental. Their publication does not establish production camera support,
a working model distribution, a Mainnet service or consumer application support.

### Does scanning automatically share location or other device information?

The symbol stores an identifier, not personal information. A client or resolved
experience may request data under its own permissions and privacy policy. Read
those policies before sharing data; this profile makes no blanket privacy claim.

### How can I contribute or get help?

See [CONTRIBUTING.md](CONTRIBUTING.md) and [SUPPORT.md](SUPPORT.md). Include the
repository revision, reproducible input and observed result in defect reports.
Use [SECURITY.md](SECURITY.md) for sensitive reports.
