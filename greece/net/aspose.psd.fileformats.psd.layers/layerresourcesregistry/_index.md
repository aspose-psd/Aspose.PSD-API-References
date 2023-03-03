---
title: Class LayerResourcesRegistry
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResourcesRegistry τάξη. Καθορίστε το μητρώο πόρων επιπέδου για τη φόρτωση αρχείων PSD.
type: docs
weight: 3390
url: /el/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---
## LayerResourcesRegistry class

Καθορίστε το μητρώο πόρων επιπέδου για τη φόρτωση αρχείων PSD.

```csharp
public static class LayerResourcesRegistry
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registereddescriptors/) { get; } | Λαμβάνει τους καταχωρισμένους περιγραφείς. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/)(Stream, int) | Αποκτά την πρώτη υποστηριζόμενη περιγραφή ανοίγματος. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptorbytypename/)(string) | Λαμβάνει τον πρώτο υποστηριζόμενο περιγραφέα με το όνομα τύπου του. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/)(Stream, int) | Φορτία[`LayerResource`](../layerresource/) χρησιμοποιώντας το πρώτο ανοιχτήρι που βρέθηκε κατάλληλο για το καθορισμένο*stream* . |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/registeropener/)(ILayerResourceLoader) | Καταχωρεί το άνοιγμα. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers/layerresourcesregistry/unregisteropener/)(ILayerResourceLoader) | Καταργεί την εγγραφή του ανοίγματος. |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* συνέλευση [Aspose.PSD](../../)


