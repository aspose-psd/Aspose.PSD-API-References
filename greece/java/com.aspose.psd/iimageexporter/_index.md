---
title: "IImageExporter"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ο εξαγωγέας εικόνας."
type: docs
weight: 121
url: /el/java/com.aspose.psd/iimageexporter/
---
```
public interface IImageExporter
```

Ο εξαγωγέας εικόνας. Μπορεί να εξάγει δεδομένα από την εσωτερική μορφή Aspose.Imaging σε μια καθορισμένη μορφή δεδομένων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Εξάγει τα καθορισμένα δεδομένα εικόνας σε καθορισμένη μορφή δεδομένων. |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Εξάγει τα καθορισμένα δεδομένα εικόνας σε καθορισμένη μορφή δεδομένων. |
### export(Image image, OutputStream stream, ImageOptionsBase optionsBase) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase)
```


Εξάγει τα καθορισμένα δεδομένα εικόνας σε καθορισμένη μορφή δεδομένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Τα δεδομένα εικόνας για εξαγωγή. |
| stream | java.io.OutputStream | Η ροή στην οποία θα εξαχθούν τα δεδομένα. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Επιλογές για εξαγωγή εικόνας |

### export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Εξάγει τα καθορισμένα δεδομένα εικόνας σε καθορισμένη μορφή δεδομένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Τα δεδομένα εικόνας για εξαγωγή. |
| stream | java.io.OutputStream | Η ροή στην οποία θα εξαχθούν τα δεδομένα. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Επιλογές για εξαγωγή εικόνας |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο περιορισμών. |

