---
title: "LayerResourcesRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "LayerResourcesRegistry method. Λαμβάνει τον πρώτο υποστηριζόμενο περιγραφέα ανοίγματος"
type: docs
weight: 20
url: /el/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## LayerResourcesRegistry.GetFirstSupportedDescriptor method

Λαμβάνει τον πρώτο υποστηριζόμενο περιγραφέα ανοικτήρα.

```csharp
public static ILayerResourceLoader GetFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή. |
| psdVersion | Int32 | Η έκδοση PSD. |

### Τιμή Επιστροφής

Ο περιγραφέας φορτωτή πόρων στρώσης ή null εάν δεν υπάρχει περιγραφέας φορτωτή που υποστηρίζεται για τέτοια ροή.

## Σχόλια

Ο πρώτος φορτωτής θα είναι στην πραγματικότητα ο τελευταίος καταχωρημένος.

### Δείτε επίσης

* interface [ILayerResourceLoader](../../ilayerresourceloader/)
* class [LayerResourcesRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


