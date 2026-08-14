---
title: "GdFlResource Klasse"
type: docs
weight: 330
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---

**Summary:** Class GdFlResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GdFlResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [GdFlResource()](#GdFlResource__1) | Initialisiert eine neue Instanz der GdFlResource Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der Typ-Werkzeug-Info-Schlüssel. |
| align_with_layer | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [ausrichten mit Ebene]. |
| angle | double | r/w | Liest oder setzt den Winkel. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Liefert die Farbe des RGB. |
| color_model | string | r/w | Farbmodell - RGB/HSB/LAB (\"RGBC\"/\"HSBl\"/\"LbCl\"). |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Liest die Farbpunkte. |
| dither | bool | r/w | Liest oder setzt einen Wert, der angibt, ob dieses [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) dither ist. |
| gradient_interval | double | r/w | Liest oder setzt das Gradientintervall. |
| gradient_mode | string | r/w | Modus für dieses Gradient.<br/>            Bestimmt 'Gradient Type' = 'Solid/Noise' = \"CstS\"/\"ClNs\". |
| gradient_name | string | r/w | Ruft den Namen des Verlaufs ab oder legt ihn fest. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype/) | r/w | Ruft den Typ des Verlaufs ab oder legt ihn fest. |
| horizontal_offset | double | r/w | Liest oder setzt den horizontalen Versatz. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Maximale Farbe von PixelDataFormat. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Minimale Farbe von PixelDataFormat. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| reverse | bool | r/w | Liest oder setzt einen Wert, der angibt, ob dieses [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) umgekehrt ist. |
| rnd_number_seed | int | r/w | Der Zufallszahl-Seed, der zur Erzeugung von Farben für das Noise-Gradient verwendet wird. |
| roughness | int | r/w | Rauheitsfaktor. |
| scale | int | r/w | Ruft den Maßstab ab oder legt ihn fest. |
| show_transparency | bool | r/w | Flag zum Anzeigen von Transparenz. |
| signature | int | r | Liefert die Signatur. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | Liest die Transparenzpunkte. |
| use_vector_color | bool | r/w | Flag für die Verwendung von Vektorfarbe. |
| vertical_offset | double | r/w | Liest oder setzt den vertikalen Versatz. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert die Ressource im angegebenen Stream-Container. |


### Constructor: GdFlResource() {#GdFlResource__1}


```
 GdFlResource() 
```

Initialisiert eine neue Instanz der GdFlResource Klasse

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Speichert die Ressource im angegebenen Stream-Container.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream-Container, in dem gespeichert werden soll. |
| psd_version | int | Die PSD-Version. |

