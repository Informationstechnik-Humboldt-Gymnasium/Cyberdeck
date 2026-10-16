# Cyberdeck – IT-AG Humboldt-Gymnasium

Ein tragbarer Koffer-Computer mit Kali Linux, gebaut aus einem alten Mini-PC der Schule.

**3D-Modell ansehen:** https://informationstechnik-humboldt-gymnasium.github.io/Cyberdeck/

Im Modell kann man den Koffer drehen, den Deckel öffnen, das Innenleben ausklappen und jede Komponente anklicken, um Details und Preise zu sehen.

## Hardware

| Teil | Plan | Preis ca. |
|---|---|---|
| Mini-PC | ZOTAC ZBOX CI320 nano Plus (Celeron N2930, 8 GB RAM, 250 GB SSD) | vorhanden |
| Bildschirm | 10,1" HDMI, 12 V, mind. 1280 × 800 | 45–55 € |
| Powerbank | 20.000 mAh, USB-C PD 65–100 W, 2× USB-C | 40–60 € |
| Triggerkabel PC | USB-C PD → 20 V Hohlstecker | 8–10 € |
| Triggerkabel Monitor | USB-C PD → 12 V Hohlstecker | 7–10 € |
| HDMI-Kabel | kurz, gewinkelt | 5–8 € |
| Tastatur | Mini-Tastatur mit Touchpad, kabelgebunden | 15–25 € |
| Koffer | Kunststoff-Werkzeugkoffer, innen ca. 35 × 25 × 10 cm | 15–30 € |
| Zwischenboden, Panel, Kleinkram | Sperrholz, Kippschalter, LEDs, Klett, Schrauben | 13–20 € |
| WLAN-Adapter *(optional)* | USB mit Monitor-Mode | 20–40 € |

**Gesamt ohne optionale Teile:** ca. 148–218 €

## Stromversorgung

```
Powerbank ─┬─ USB-C → Triggerkabel 20 V → ZBOX
           └─ USB-C → Triggerkabel 12 V → Monitor
```

Der ZBOX braucht im Betrieb nur ca. 10–15 W, damit hält eine 20.000-mAh-Powerbank grob 4–5 Stunden.

## Hinweis

Kali-Tools nur im eigenen Netz oder mit ausdrücklicher Erlaubnis verwenden (§ 202c StGB).

## Website bearbeiten

Die ganze Seite steckt in `index.html` (Three.js, keine Build-Schritte). Maße und Preise stehen oben im Skript im Objekt `PARTS`.
