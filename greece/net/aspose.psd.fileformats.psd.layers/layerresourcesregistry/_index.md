---
title: "Κλάση LayerResourcesRegistry"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResourcesRegistry κλάση. Ορίζει το μητρώο πόρων στρώσεων για τη φόρτωση αρχείων PSD"
type: docs
weight: 3790
url: /el/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---
{{< psd/tize >}}
## LayerResourcesRegistry class

Ορίστε το μητρώο πόρων στρώσης για τη φόρτωση αρχείων PSD.

```csharp
public static class LayerResourcesRegistry
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registereddescriptors/) { get; } | Λαμβάνει τους καταχωρημένους περιγραφείς. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/)(Stream, int) | Λαμβάνει τον πρώτο υποστηριζόμενο περιγραφέα ανοικτήρα. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptorbytypename/)(string) | Λαμβάνει τον πρώτο υποστηριζόμενο περιγραφέα με βάση το όνομα τύπου του. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/)(Stream, int) | Φορτώνει [`LayerResource`](../layerresource/) χρησιμοποιώντας τον πρώτο βρεθέντα ανοικτήρα κατάλληλο για το καθορισμένο *stream*. |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registeropener/)(ILayerResourceLoader) | Καταχωρεί τον ανοικτήρα. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/unregisteropener/)(ILayerResourceLoader) | Καταργεί την καταχώρηση του ανοικτήρα. |

### Δείτε επίσης

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


