---
title: "IImageExporterDescriptor"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αντιπροσωπεύει τον περιγραφέα εξαγωγέα εικόνας."
type: docs
weight: 122
url: /el/java/com.aspose.psd/iimageexporterdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageExporterDescriptor extends IImageDescriptor
```

Αντιπροσωπεύει την περιγραφή του εξαγωγέα εικόνας. Η περιγραφή του εξαγωγέα χρησιμοποιείται για να ξεπεραστεί η ανάγκη διατήρησης κάθε στιγμιότυπου του εξαγωγέα στη μνήμη και τα προβλήματα πολυνηματικότητας.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [canExport(Image image, ImageOptionsBase optionsBase)](#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Καθορίζει εάν ο εξαγωγέας εικόνας μπορεί να εξάγει την καθορισμένη εικόνα στην καθορισμένη μορφή εικόνας που ορίζεται από τις επιλογές αποθήκευσης. |
| [createInstance()](#createInstance--) | Δημιουργεί ένα νέο στιγμιότυπο εξαγωγέα. |
### canExport(Image image, ImageOptionsBase optionsBase) {#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canExport(Image image, ImageOptionsBase optionsBase)
```


Καθορίζει εάν ο εξαγωγέας εικόνας μπορεί να εξάγει την καθορισμένη εικόνα στην καθορισμένη μορφή εικόνας που ορίζεται από τις επιλογές αποθήκευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Η εικόνα προς εξαγωγή. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Η βάση των επιλογών. |

**Returns:**
boolean -  true  εάν ο εξαγωγέας που δημιουργείται από αυτήν την περιγραφή μπορεί να εξάγει την καθορισμένη εικόνα στην καθορισμένη μορφή αρχείου· διαφορετικά,  false .
### createInstance() {#createInstance--}
```
public abstract IImageExporter createInstance()
```


Δημιουργεί ένα νέο στιγμιότυπο εξαγωγέα.

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - A new exporter instance.
