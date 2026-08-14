---
title: "TypeToolInfoResource Klasse"
type: docs
weight: 1000
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Summary:** The type tool information. For PSD version lower than 6.0.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.TypeToolInfoResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [TypeToolInfoResource()](#TypeToolInfoResource__1) | Initialisiert eine neue Instanz der TypeToolInfoResource Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| a_component | short | r/w | Liest oder setzt eine Komponente. |
| b_component | short | r/w | Liest oder setzt die b-Komponente. |
| character_count | int | r/w | Liest oder setzt die Zeichenanzahl. |
| color_space_value | short | r/w | Liest oder setzt den Farbraumwert. |
| font_version | short | r/w | Liest oder setzt die Schriftversion. |
| fonts | [TypeToolFontInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) | r/w | Liest oder setzt die Schriftarten. |
| fonts_count | short | r | Liest die Anzahl der Schriftarten. |
| g_component | short | r/w | Liest oder setzt die g-Komponente. |
| horizontal_placement | int | r/w | Liest oder setzt die horizontale Platzierung. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| line_count | short | r | Liest die Zeilenzahl. |
| lines | [TypeToolLineInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) | r/w | Liest oder setzt die Zeilen. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| r_component | short | r/w | Liest oder setzt die r-Komponente. |
| scale_factor | int | r/w | Liest oder setzt den Skalierungsfaktor. |
| selection_end | int | r/w | Liest oder setzt das Auswahlende. |
| selection_start | int | r/w | Liest oder setzt den Auswahlbeginn. |
| signature | int | r | Liefert die Signatur. |
| styles | [TypeToolStyleInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) | r/w | Liest oder setzt die Schriftstile. |
| styles_count | short | r | Liest die Stilanzahl. |
| transform_matrix | double | r/w | Liest oder setzt die Transformationsmatrix. |
| type_value | short | r/w | Liest oder setzt den Typwert. |
| version | short | r/w | Liest oder setzt die Version. |
| vertical_placement | int | r/w | Liest oder setzt die vertikale Platzierung. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert den angegebenen Stream-Container. |


### Constructor: TypeToolInfoResource() {#TypeToolInfoResource__1}


```
 TypeToolInfoResource() 
```

Initialisiert eine neue Instanz der TypeToolInfoResource Klasse

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Speichert den angegebenen Stream-Container.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream‑Container. |
| psd_version | int | Die PSD-Version. |

