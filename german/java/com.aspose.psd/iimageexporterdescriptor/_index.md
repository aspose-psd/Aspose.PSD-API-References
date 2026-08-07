---
title: "IImageExporterDescriptor"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt den Bildexporter-Deskriptor dar."
type: docs
weight: 122
url: /de/java/com.aspose.psd/iimageexporterdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageExporterDescriptor extends IImageDescriptor
```

Stellt den Bildexport-Deskriptor dar. Der Export-Deskriptor wird verwendet, um die Notwendigkeit zu überwinden, jede Exporter-Instanz im Speicher zu halten und Probleme mit Multithreading zu vermeiden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [canExport(Image image, ImageOptionsBase optionsBase)](#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Bestimmt, ob der Bildexporter das angegebene Bild in das durch die Speicheroptionen angegebene Bildformat exportieren kann. |
| [createInstance()](#createInstance--) | Erstellt eine neue Exporter-Instanz. |
### canExport(Image image, ImageOptionsBase optionsBase) {#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canExport(Image image, ImageOptionsBase optionsBase)
```


Bestimmt, ob der Bildexporter das angegebene Bild in das durch die Speicheroptionen angegebene Bildformat exportieren kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Das zu exportierende Bild. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Die Optionsbasis. |

**Returns:**
boolean -  true  wenn der durch diesen Deskriptor erstellte Exporter das angegebene Bild in das angegebene Dateiformat exportieren kann; andernfalls  false .
### createInstance() {#createInstance--}
```
public abstract IImageExporter createInstance()
```


Erstellt eine neue Exporter-Instanz.

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - A new exporter instance.
