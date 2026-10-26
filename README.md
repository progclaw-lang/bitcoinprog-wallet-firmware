# BitcoinProg Wallet · Firmware

Archivos oficiales del firmware de la **BitcoinProg Wallet** (cartera física).
Official firmware files for the **BitcoinProg Wallet** hardware wallet.

| Versión | Carpeta | Edición |
|---|---|---|
| **1.0.46** | `firmware/1.0.46/estandar/` | Estándar · Standard |
| **1.0.46** | `firmware/1.0.46/firmada/` | Firmada con Secure Boot V2 · Signed (Secure Boot V2) |
| 1.0.45 | `firmware/1.0.45/estandar/` | Estándar · Standard |
| 1.0.45 | `firmware/1.0.45/firmada/` | Firmada con Secure Boot V2 · Signed (Secure Boot V2) |

## Verificar · Verify

Cada archivo tiene su huella SHA-256 en [`SHA256SUMS.txt`](SHA256SUMS.txt).
Each file's SHA-256 is listed in `SHA256SUMS.txt`.

```
shasum -a 256 -c SHA256SUMS.txt
```

No confíes, verifica. · Don't trust, verify.

---
Kit de emergencia y BóvedaProg (código abierto): https://github.com/progclaw-lang/bitcoinprog-kit-emergencia
Sitio: https://bitcoinprogwallet.com
