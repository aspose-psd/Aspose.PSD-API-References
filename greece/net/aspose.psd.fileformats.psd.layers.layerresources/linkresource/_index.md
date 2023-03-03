---
title: Class LinkResource
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource τάξη. Καθορίζει την κλάση LinkResource που περιέχει πληροφορίες σχετικά με συνδεδεμένα ή ενσωματωμένα αρχεία στην εικόνα μορφής PSD. Ο πόρος σύνδεσης μπορεί να περιέχει πολλάLinkDataSource στιγμιότυπα στα οποία μπορούν να προσπελαστούν οι indexers σε οποιαδήποτε παράγωγη κλάση.
type: docs
weight: 2710
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
## LinkResource class

Καθορίζει την κλάση LinkResource που περιέχει πληροφορίες σχετικά με συνδεδεμένα ή ενσωματωμένα αρχεία στην εικόνα μορφής PSD. Ο πόρος σύνδεσης μπορεί να περιέχει πολλά[`LinkDataSource`](../linkdatasource/) στιγμιότυπα στα οποία μπορούν να προσπελαστούν οι indexers σε οποιαδήποτε παράγωγη κλάση.

```csharp
public abstract class LinkResource : LayerResource
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | Λαμβάνει τον αριθμό των πηγών δεδομένων συνδέσμων στις οποίες μπορεί να προσπελαστεί ο ευρετηριαστής. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία πόρου συνδέσμου είναι κενή. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | Λαμβάνει το[`LinkDataSource`](../linkdatasource/) στο καθορισμένο ευρετήριο που είναι το μοναδικό αναγνωριστικό πηγής δεδομένων συνδέσμου.. |
| abstract [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Λαμβάνει το κλειδί πόρων επιπέδου. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | Λαμβάνει το συνολικό μήκος πόρου συνδέσμου PSD σε byte. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/psdversion/) { get; } | Λαμβάνει την έκδοση μορφής PSD. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/signature/) { get; } | Αποκτά την υπογραφή του παγκόσμιου πόρου συνδέσμου PSD. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Αποθηκεύει τα δεδομένα του μπλοκ πόρων. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Επιστρέφει αString που αντιπροσωπεύει αυτήν την περίπτωση. |

### Δείτε επίσης

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* συνέλευση [Aspose.PSD](../../)


