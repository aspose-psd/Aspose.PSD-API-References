---
title: "AiLayerSection Klasse"
type: docs
weight: 50
url: /de/python-net/aspose.psd.fileformats.ai/ailayersection/
---

**Summary:** The Ai format Layer Section

**Module:** [aspose.psd.fileformats.ai](/psd/python-net/aspose.psd.fileformats.ai/)

**Full Name:** aspose.psd.fileformats.ai.AiLayerSection

**Inheritance:** AiDataSection

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| blau | int | r/w | Liest oder schreibt die blaue Farbkomponente. |
| color_index | int | r/w | Liest oder schreibt den Index der Farbe.<br/>            Dieses Argument kann Werte zwischen –1 und 26 annehmen. Jeder Integer<br/>            stellt eine Farbe dar, die dem Layer für Benutzer<br/>            Identifikationszwecke zugewiesen werden kann. |
| color_number | int | r/w | Liest oder legt die Farbnumer fest. -1 ist der benutzerdefinierte Farbwert aus den Eigenschaften Rot, Grün, Blau.<br/>            Gibt die Farbeinstellung der Ebene an. |
| dim_value | int | r/w | Liest oder legt den Dim-Wert als Prozentsatz fest.<br/>            Reduziert die Intensität verknüpfter Bilder und Bitmap-Bilder, die in der Ebene enthalten sind, auf den angegebenen Prozentsatz. |
| disposed | bool | r | Ruft einen Wert ab, der angibt, ob diese Instanz freigegeben wurde. |
| grün | int | r/w | Liest oder legt die grüne Farbkomponente fest. |
| has_multi_layer_masks | bool | r/w | Liest oder legt einen Wert fest, der angibt, ob diese Instanz Mehrschichtmasken hat. |
| is_images_dimmed | bool | r/w | Liest oder legt einen Wert fest, der angibt, ob diese Ebene abgedimmt ist.<br/>            Reduziert die Intensität verknüpfter Bilder und Bitmap-Bilder, die in der Ebene enthalten sind. |
| is_locked | bool | r/w | Liest oder legt einen Wert fest, der angibt, ob diese Ebene gesperrt ist.<br/>            Verhindert Änderungen am Element. |
| is_preview | bool | r/w | Liest oder legt einen Wert fest, der angibt, ob diese Ebene in der Vorschau ist.<br/>            Zeigt die in der Ebene enthaltenen Kunstwerke in Farbe anstelle von Konturen. |
| is_printed | bool | r/w | Liest oder legt einen Wert fest, der angibt, ob diese Ebene gedruckt wird.<br/>            Macht die in der Ebene enthaltenen Kunstwerke druckbar, wenn wahr. |
| is_shown | bool | r/w | Liest oder legt einen Wert fest, der angibt, ob diese Ebene angezeigt wird.<br/>            Zeigt alle in der Ebene enthaltenen Kunstwerke auf dem Zeichenbrett an, wenn wahr. |
| is_template | bool | r/w | Liest oder legt einen Wert fest, der angibt, ob diese Ebene eine Vorlagenebene ist. |
| name | string | r/w | Liest oder legt den Ebenennamen fest.<br/>            Gibt den Namen des Elements an, wie er im Ebenen‑Panel erscheint. |
| raster_images | [AiRasterImageSection[]](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | r | Liest die Rasterbilder. |
| rot | int | r/w | Liest oder legt die rote Farbkomponente fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_raster_image(raster_image)](#add_raster_image_raster_image_1) | Fügt das Rasterbild hinzu. |
| [get_data()](#get_data__2) | Ermittelt die Zeichenkettendaten. |


### Method: add_raster_image(raster_image) {#add_raster_image_raster_image_1}


```
 add_raster_image(raster_image) 
```

Fügt das Rasterbild hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| raster_image | [AiRasterImageSection](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | Das Rasterbild. |

### Method: get_data() {#get_data__2}


```
 get_data() 
```

Ermittelt die Zeichenkettendaten.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Die Zeichenkettendaten des Abschnitts |


