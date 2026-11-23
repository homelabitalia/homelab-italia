# Homelab Italia — Home Assistant in italiano 🇮🇹

Configurazioni e blueprint **gratuiti** per Home Assistant, pensati per le case italiane.

## Gratis in questo repository

| File | Cosa fa |
|---|---|
| [`packages/fascia_oraria.yaml`](packages/fascia_oraria.yaml) | Sensore della fascia oraria F1/F2/F3 (orari ARERA, festivi compresi) |
| [`blueprints/notifica_semplice_lavatrice.yaml`](blueprints/notifica_semplice_lavatrice.yaml) | Notifica "lavatrice finita" con una presa smart |

### Importare il blueprint

[![Importa il blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fhomelabitalia%2Fhomelab-italia%2Fblob%2Fmain%2Fblueprints%2Fnotifica_semplice_lavatrice.yaml)

### Usare il package

In `configuration.yaml`:

```yaml
homeassistant:
  packages: !include_dir_named packages
```

e copia il file nella cartella `packages`.

## Versioni complete

Su **[ko-fi.com/homelabitalia](https://ko-fi.com/homelabitalia/shop)** trovi pacchetti completi, provati in funzione, con istruzioni PDF in italiano:

- **Energia Italia**: consumi e costi per fascia, protezione contatore 3 kW
- **Fotovoltaico**: surplus, autoconsumo, scaldabagno acceso col sole
- **Allarme fai da te**, **Casa vuota & Vacanze**, **Clima & Aria**, **Luci col movimento**
- **Raccolta differenziata**, **Scadenze di casa**, **Manutenzione**
- Guida **"Casa smart self-hosted"**: Home Assistant + Docker su un mini PC (primi 2 capitoli gratis)

Comprarle supporta lo sviluppo dei contenuti gratuiti. Grazie! ☕

## Licenza

MIT per i file di questo repository.
