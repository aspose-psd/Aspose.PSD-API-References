---
title: "BritResource Klasse"
type: docs
weight: 120
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---

**Summary:** Class BritResource. Resource of Brightness/Contrast Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BritResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [BritResource()](#BritResource__1) | Initialisiert eine neue Instanz der [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) Klasse. |
| [BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color)](#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2) | Initialisiert eine neue Instanz der [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) Klasse. |
| [BritResource(bytes)](#BritResource_bytes_3) | Initialisiert eine neue Instanz der [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) Klasse.<br/>            Die PSD-Format-Spezifikation enthält folgende Beschreibung:<br/>            2 Helligkeit<br/>            2 Kontrast<br/>            2 Mittelwert für Helligkeit und Kontrast<br/>            1 Nur Lab-Farbe<br/>            Sie wird in modernen PSDs (CS5 und neuer) nicht verwendet, wo CgEd zum Einsatz kommt. CgEd speichert Informations‑Eigenschaften |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| TYPE_TOOL_KEY [static] | int | r | Der Typ-Werkzeug-Info-Schlüssel. |
| Helligkeit | short | r/w | Liest oder setzt die Helligkeit. |
| Kontrast | short | r/w | Liest oder setzt den Kontrast. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| lab_color | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [lab color]. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| mean_value_for_brightness_and_contrast | short | r/w | Liest oder setzt den Mittelwert für Helligkeit und Kontrast. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| signature | int | r | Liefert die Signatur. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert die Ressource im angegebenen Stream-Container. |


### Constructor: BritResource() {#BritResource__1}


```
 BritResource() 
```

Initialisiert eine neue Instanz der [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) Klasse.

### Constructor: BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) {#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2}


```
 BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) 
```

Initialisiert eine neue Instanz der [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Helligkeit | short | Die Helligkeit. |
| Kontrast | short | Der Kontrast. |
| mean_value_for_brightness_and_contrast | short | Der Mittelwert für Helligkeit und Kontrast. |
| lab_color | bool | wenn auf <c>true</c> [lab color] gesetzt ist. |

### Constructor: BritResource(bytes) {#BritResource_bytes_3}


```
 BritResource(bytes) 
```

Initialisiert eine neue Instanz der [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) Klasse.<br/>            Die PSD-Format-Spezifikation enthält folgende Beschreibung:<br/>            2 Helligkeit<br/>            2 Kontrast<br/>            2 Mittelwert für Helligkeit und Kontrast<br/>            1 Nur Lab-Farbe<br/>            Sie wird in modernen PSDs (CS5 und neuer) nicht verwendet, wo CgEd zum Einsatz kommt. CgEd speichert Informations‑Eigenschaften

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Bytes | byte | Die Bytes. |

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

