<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/perseo-lab/.github/raw/main/profile/perseo-lab-logo-light.svg">
    <img alt="Perseo Lab" src="https://github.com/perseo-lab/.github/raw/main/profile/perseo-lab-logo-dark.svg" height="72">
  </picture>
</p>

<p align="center"><b>Open-source tools for Bitcoin self-custody.</b><br>
Air-gapped signing, independent verification, encrypted vaults.</p>

---

| Project | What it is |
|---|---|
| [**Seed Max**](https://github.com/perseo-lab/seed-max) | Air-gapped, stateless Bitcoin signer for a touchscreen, battery-powered device. Based on SeedSigner. |
| [**Anti-Klepto Check**](https://github.com/perseo-lab/anti-klepto-check) | Offline verifier for signed transactions: checks nonces against Dark Skippy-style exfiltration, sighash flags, change addresses and tampered outputs. |
| [**Raspy Max hardware**](https://github.com/perseo-lab/raspy-max-hardware) | The device they run on: Raspberry Pi Zero, 3.5" touchscreen, UPS battery, camera, 3D-printed case. Full build guide, BOM and CAD. |
| **Vault Max** | Encrypted storage for passphrases, passwords and wallet descriptors, interoperable with Tails. *In progress.* |

### Verify before you trust

Every release image is published with its SHA-256 and signed with the PGP key **Ollen_47**:

```
513B 3583 0E4F 869E FC6D  9534 F1A0 5CB1 6C89 8D92
```

Tags and commits are signed with the same key. Check the signature and the SHA-256 before flashing any image.

### Why Perseo

Perseus beat Medusa by never looking at her directly, only at her reflection in a polished shield.
That is the idea here: don't trust the device, verify what it does.

### Support

No accounts, no tracking. Donations via Lightning (BOLT12) or Silent Payments. Details in the signed
[`DONATE.txt.asc`](https://github.com/perseo-lab/seed-max/blob/seed-max/docs/DONATE.txt.asc).

Security issues: please use *private vulnerability reporting* on the relevant repository.
