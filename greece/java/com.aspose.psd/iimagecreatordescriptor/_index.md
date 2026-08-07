---
title: "IImageCreatorDescriptor"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ο περιγραφέας δημιουργού εικόνας που καθορίζει τις ιδιότητες του δημιουργού."
type: docs
weight: 119
url: /el/java/com.aspose.psd/iimagecreatordescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageCreatorDescriptor extends IImageDescriptor
```

Ο περιγραφέας δημιουργού εικόνας που καθορίζει τις ιδιότητες του δημιουργού. Ο περιγραφέας δημιουργού χρησιμοποιείται για να ξεπεραστεί η ανάγκη να περιέχεται κάθε παρουσία δημιουργού εικόνας στη μνήμη και τα προβλήματα πολυνηματικότητας.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [canCreate(ImageOptionsBase imageOptions)](#canCreate-com.aspose.psd.ImageOptionsBase-) | Καθορίζει εάν ο δημιουργός εικόνας μπορεί να δημιουργήσει μια νέα εικόνα χρησιμοποιώντας το  imageOptions . |
| [createInstance()](#createInstance--) | Δημιουργεί μια νέα παρουσία δημιουργού. |
### canCreate(ImageOptionsBase imageOptions) {#canCreate-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canCreate(ImageOptionsBase imageOptions)
```


Καθορίζει εάν ο δημιουργός εικόνας μπορεί να δημιουργήσει μια νέα εικόνα χρησιμοποιώντας το  imageOptions .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Οι επιλογές εικόνας. |

**Returns:**
boolean -  true  εάν ο δημιουργός εικόνας που δημιουργείται από αυτόν τον περιγραφέα μπορεί να δημιουργήσει δεδομένα εικόνας χρησιμοποιώντας τις καθορισμένες  imageOptions ; διαφορετικά,  false .
### createInstance() {#createInstance--}
```
public abstract IImageCreator createInstance()
```


Δημιουργεί μια νέα παρουσία δημιουργού.

**Returns:**
[IImageCreator](../../com.aspose.psd/iimagecreator) - A new creator instance.
