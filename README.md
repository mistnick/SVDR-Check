# SVDR-Check

SVDR-Check è il verificatore desktop dei pacchetti di export certificato di [SimpleVDR](https://www.simplevdr.com). Verifica offline integrità (hash e albero di Merkle), firma del manifest, marca temporale RFC 3161 e sigillo elettronico CAdES di un pacchetto, e produce un rapporto di verifica.

Questo repository contiene solo gli eseguibili, pubblicati come [release](https://github.com/mistnick/SVDR-Check/releases). Il codice sorgente non è qui.

## Download dell'ultima versione

| Sistema | Link fisso (sempre l'ultima versione) |
|---|---|
| macOS (Apple Silicon e Intel) | https://www.simplevdr.com/download/svdr-check/macos |
| Windows 10 o successivo (x64) | https://www.simplevdr.com/download/svdr-check/windows |
| Linux x64 (AppImage) | https://www.simplevdr.com/download/svdr-check/linux |
| Linux x64 (Debian/Ubuntu, .deb) | https://www.simplevdr.com/download/svdr-check/linux-deb |

Tutte le versioni: https://www.simplevdr.com/download/svdr-check

Ogni release contiene `SHA256SUMS.txt` con l'impronta di ogni file:

```bash
shasum -a 256 -c SHA256SUMS.txt --ignore-missing
```

## Firma degli installer

- **macOS**: firmato con il certificato Developer ID di Beatdata Srl (team U65MM47RFU) e notarizzato da Apple. Si apre senza avvisi.
- **Windows e Linux**: non ancora firmati. Su Windows, al primo avvio, SmartScreen → Ulteriori informazioni → Esegui comunque.

Supporto: legal@simplevdr.com
