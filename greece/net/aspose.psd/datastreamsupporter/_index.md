---
title: "Κλάση DataStreamSupporter"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.DataStreamSupporter. Ο κοντέινερ ροής δεδομένων"
type: docs
weight: 750
url: /el/net/aspose.psd/datastreamsupporter/
---
{{< psd/tize >}}
## DataStreamSupporter class

Το δοχείο ροής δεδομένων.

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Λαμβάνει τη ροή δεδομένων του αντικειμένου. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα του αντικειμένου είναι προσωρινά αποθηκευμένα αυτή τη στιγμή και δεν απαιτείται ανάγνωση δεδομένων. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Αποθηκεύει στην κρυφή μνήμη τα δεδομένα και εξασφαλίζει ότι δεν θα γίνει επιπλέον φόρτωση δεδομένων από το υποκείμενο [`DataStreamContainer`](./datastreamcontainer/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Αποδεσμεύει την τρέχουσα παρουσία. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save)() | Αποθηκεύει τα δεδομένα του αντικειμένου στον τρέχον `DataStreamSupporter`. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_1)(Stream) | Αποθηκεύει τα δεδομένα του αντικειμένου στο καθορισμένο ρεύμα. |
| [Save](../../aspose.psd/datastreamsupporter/save/#save_2)(string) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_3)(string, bool) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |

### Δείτε επίσης

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


