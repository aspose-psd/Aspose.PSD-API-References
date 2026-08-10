---
title: "Κλάση LinkResource"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource κλάση. Ορίζει την κλάση LinkResource που περιέχει πληροφορίες σχετικά με συνδεδεμένα ή ενσωματωμένα αρχεία στην εικόνα μορφής PSD. Ο πόρος συνδέσμου μπορεί να περιέχει αρκετές εμφανίσεις του LinkDataSource που μπορούν να προσπελαστούν μέσω δεικτών σε οποιαδήποτε κληρονομημένη κλάση."
type: docs
weight: 3010
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
{{< psd/tize >}}
## LinkResource class

Ορίζει την κλάση LinkResource που περιέχει πληροφορίες σχετικά με συνδεδεμένα ή ενσωματωμένα αρχεία στην εικόνα μορφής PSD. Ο πόρος συνδέσμου μπορεί να περιέχει αρκετές εμφανίσεις του [`LinkDataSource`](../linkdatasource/) που μπορούν να προσπελαστούν μέσω δεικτών σε οποιαδήποτε κληρονομημένη κλάση.

```csharp
public abstract class LinkResource : LayerResource
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | Ανακτά τον αριθμό των πηγών δεδομένων σύνδεσης που μπορούν να προσπελαστούν μέσω του δείκτη. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Ανακτά μια τιμή που υποδεικνύει εάν αυτό το στιγμιότυπο πόρου σύνδεσης είναι κενό. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | Λαμβάνει το [`LinkDataSource`](../linkdatasource/) στο καθορισμένο δείκτη που είναι το μοναδικό αναγνωριστικό της πηγής δεδομένων συνδέσμου. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Λαμβάνει το κλειδί πόρου του επιπέδου. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | Ανακτά το συνολικό μήκος του πόρου σύνδεσης PSD σε bytes. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Λαμβάνει την υπογραφή. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Αποθηκεύει τα δεδομένα του μπλοκ πόρου. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτήν την περίπτωση. |

### Δείτε επίσης

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


