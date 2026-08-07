---
title: "IImageLoaderDescriptor"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Der Bildlader-Deskriptor, der die Lader-Eigenschaften angibt."
type: docs
weight: 124
url: /de/java/com.aspose.psd/iimageloaderdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageLoaderDescriptor extends IImageDescriptor
```

Der Bildlader-Deskriptor, der die Lader-Eigenschaften angibt. Der Lader-Deskriptor wird verwendet, um die Notwendigkeit zu umgehen, jede Bildlader-Instanz im Speicher zu halten und Probleme mit Multithreading zu vermeiden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [canLoad(StreamContainer streamContainer, LoadOptions loadOptions)](#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-) | Bestimmt, ob der Bildlader ein neues Bild aus dem angegebenen Stream lesen kann und optional die  loadOptions  verwendet. |
| [createInstance()](#createInstance--) | Erstellt eine neue Lader-Instanz. |
### canLoad(StreamContainer streamContainer, LoadOptions loadOptions) {#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-}
```
public abstract boolean canLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```


Bestimmt, ob der Bildlader ein neues Bild aus dem angegebenen Stream lesen kann und optional die  loadOptions  verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream-Container. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Die Dateiformatdetails, die durch  loadOptions  angegeben werden. Die  loadOptions  können null sein. |

**Returns:**
boolean -  true  wenn der durch diesen Deskriptor erstellte Bildlader das Bild aus dem Stream lesen kann; andernfalls,  false .
### createInstance() {#createInstance--}
```
public abstract IImageLoader createInstance()
```


Erstellt eine neue Lader-Instanz.

**Returns:**
[IImageLoader](../../com.aspose.psd/iimageloader) - A new loader instance.
