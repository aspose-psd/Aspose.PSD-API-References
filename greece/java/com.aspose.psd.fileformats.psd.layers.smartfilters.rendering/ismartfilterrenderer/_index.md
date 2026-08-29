---
title: "ISmartFilterRenderer"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Η διεπαφή για έναν συγκεκριμένο κατασκευαστή έξυπνων φίλτρων."
type: docs
weight: 10
url: /el/java/com.aspose.psd.fileformats.psd.layers.smartfilters.rendering/ismartfilterrenderer/
---
```
public interface ISmartFilterRenderer
```

Η διεπαφή για έναν συγκεκριμένο κατασκευαστή έξυπνων φίλτρων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [render(PixelsData pixelsData)](#render-com.aspose.psd.pixelsdatamodels.PixelsData-) | Απεικονίζει το τρέχον έξυπνο φίλτρο στα δεδομένα εικονοστοιχείων. |
### render(PixelsData pixelsData) {#render-com.aspose.psd.pixelsdatamodels.PixelsData-}
```
public abstract PixelsData render(PixelsData pixelsData)
```


Απεικονίζει το τρέχον έξυπνο φίλτρο στα δεδομένα εικονοστοιχείων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixelsData | [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) | Τα δεδομένα εικονοστοιχείων. |

**Returns:**
[PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) - Returns processed pixels data.
