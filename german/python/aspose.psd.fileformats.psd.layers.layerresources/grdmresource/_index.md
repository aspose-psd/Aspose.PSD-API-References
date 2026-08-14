---
title: "GrdmResource Klasse"
type: docs
weight: 340
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Summary:** Class GrdmResource. Contains information about Gradient-Map layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GrdmResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [GrdmResource(psd_version)](#GrdmResource_psd_version_1) | Initialisiert eine neue Instanz der [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der Typ-Werkzeug-Info-Schlüssel. |
| color_model | short | r/w | Farbmodell.<br/>            Wenn 'Gradient type' = 'Noise', können wir 'Farbmodell' auf RGB/SHB/LAB (3/4/6) setzen. |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Liest oder setzt die Farbpunkte. |
| dither | bool | r/w | Ist der Verlauf dithered. |
| expansion_count | short | r/w | Erweiterungsanzahl ( = 2 für Photoshop 6.0). |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r/w | Modus für diesen Verlauf<br/>            Bestimmt 'Gradient Type' = 'Solid/Noise' (0/1). |
| gradient_name | string | r/w | Name des Verlaufs: Unicode‑Zeichenkette, aufgefüllt. |
| Interpolation | short | r/w | Interpolation. Bestimmt die Glätte, wenn 'Gradient Type' = 'Solid' (GradientMode = 0). |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Maximale Farbe des PixelDataFormat.Rgba64Bpp‑Formats.<br/>            Die Farbe hat ARGB‑Kanäle, jeder Kanal ist 16 Bit. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Minimale Farbe des PixelDataFormat.Rgba64Bpp‑Formats.<br/>            Die Farbe hat ARGB‑Kanäle, jeder Kanal ist 16 Bit. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| reverse | bool | r/w | Ist der Verlauf umgekehrt. |
| rnd_number_seed | int | r/w | Der Zufallszahl-Seed, der zur Erzeugung von Farben für das Noise-Gradient verwendet wird. |
| roughness | int | r/w | Rauheitsfaktor<br/>            Wenn 'Gradient type' = 'Noise', können wir 'Roughness' (0 - 2048) zuweisen. |
| show_transparency | short | r/w | Flag zum Anzeigen von Transparenz<br/>            Wenn 'Gradient type' = 'Noise', können wir 'Add transparency' auf true setzen. |
| signature | int | r | Liefert die Signatur. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | Ruft die Transparenzpunkte ab oder legt sie fest. |
| use_vector_color | short | r/w | Flag für die Verwendung von Vektorfarbe. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert Ressourcendaten im angegebenen Stream-Container. |


### Constructor: GrdmResource(psd_version) {#GrdmResource_psd_version_1}


```
 GrdmResource(psd_version) 
```

Initialisiert eine neue Instanz der [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| psd_version | int | Die PSD-Version der Ressource. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Speichert Ressourcendaten im angegebenen Stream-Container.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream‑Container. |
| psd_version | int | Die PSD-Version. |

