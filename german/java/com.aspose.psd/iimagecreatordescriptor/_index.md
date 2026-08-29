---
title: "IImageCreatorDescriptor"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Der Bildgenerator-Deskriptor, der die Erzeugereigenschaften angibt."
type: docs
weight: 119
url: /de/java/com.aspose.psd/iimagecreatordescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageCreatorDescriptor extends IImageDescriptor
```

Der image creator descriptor, der die Ersteller-Eigenschaften angibt. Der image creator descriptor wird verwendet, um die Notwendigkeit zu überwinden, jede image creator Instanz im Speicher zu halten und Multithreading-Probleme zu vermeiden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [canCreate(ImageOptionsBase imageOptions)](#canCreate-com.aspose.psd.ImageOptionsBase-) | Bestimmt, ob der image creator ein neues Bild mit den  imageOptions erstellen kann. |
| [createInstance()](#createInstance--) | Erstellt eine neue Ersteller-Instanz. |
### canCreate(ImageOptionsBase imageOptions) {#canCreate-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canCreate(ImageOptionsBase imageOptions)
```


Bestimmt, ob der image creator ein neues Bild mit den  imageOptions erstellen kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Die Bildoptionen. |

**Returns:**
boolescher -  true  wenn der von diesem Deskriptor erstellte image creator Bilddaten mit den angegebenen  imageOptions erstellen kann; andernfalls  false .
### createInstance() {#createInstance--}
```
public abstract IImageCreator createInstance()
```


Erstellt eine neue Ersteller-Instanz.

**Returns:**
[IImageCreator](../../com.aspose.psd/iimagecreator) - A new creator instance.
