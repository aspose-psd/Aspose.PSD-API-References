---
title: "IImageLoaderDescriptor"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ο περιγραφέας φορτωτή εικόνας που καθορίζει τις ιδιότητες του φορτωτή."
type: docs
weight: 124
url: /el/java/com.aspose.psd/iimageloaderdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageLoaderDescriptor extends IImageDescriptor
```

Ο περιγραφέας φορτωτή εικόνας που καθορίζει τις ιδιότητες του φορτωτή. Ο περιγραφέας φορτωτή χρησιμοποιείται για να ξεπεράσει την ανάγκη διατήρησης κάθε στιγμιοτύπου φορτωτή εικόνας στη μνήμη και τα προβλήματα πολυνηματικότητας.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [canLoad(StreamContainer streamContainer, LoadOptions loadOptions)](#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-) | Καθορίζει εάν ο φορτωτής εικόνας μπορεί να διαβάσει μια νέα εικόνα από τη συγκεκριμένη ροή και προαιρετικά χρησιμοποιώντας το loadOptions. |
| [createInstance()](#createInstance--) | Δημιουργεί ένα νέο στιγμιότυπο φορτωτή. |
### canLoad(StreamContainer streamContainer, LoadOptions loadOptions) {#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-}
```
public abstract boolean canLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```


Καθορίζει εάν ο φορτωτής εικόνας μπορεί να διαβάσει μια νέα εικόνα από τη συγκεκριμένη ροή και προαιρετικά χρησιμοποιώντας το loadOptions.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Το κοντέινερ ροής. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Οι λεπτομέρειες μορφής αρχείου που καθορίζονται από το loadOptions. Το loadOptions μπορεί να είναι null. |

**Returns:**
boolean - true εάν ο φορτωτής εικόνας που δημιουργείται από αυτόν τον περιγραφέα μπορεί να διαβάσει εικόνα από τη ροή· διαφορετικά, false.
### createInstance() {#createInstance--}
```
public abstract IImageLoader createInstance()
```


Δημιουργεί ένα νέο στιγμιότυπο φορτωτή.

**Returns:**
[IImageLoader](../../com.aspose.psd/iimageloader) - A new loader instance.
