---
title: "Διεπαφή IAsyncTask"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Διεπαφή Aspose.PSD.AsyncTask.IAsyncTask. Η ασύγχρονη εργασία"
type: docs
weight: 80
url: /el/net/aspose.psd.asynctask/iasynctask/
---
{{< psd/tize >}}
## IAsyncTask interface

Η ασύγχρονη εργασία.

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Error](../../aspose.psd.asynctask/iasynctask/error/) { get; } | Λαμβάνει το σφάλμα της εργασίας που είναι διαθέσιμο μετά την ολοκλήρωση της εργασίας. |
| [IsBusy](../../aspose.psd.asynctask/iasynctask/isbusy/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η εργασία εκτελείται αυτή τη στιγμή. |
| [IsCanceled](../../aspose.psd.asynctask/iasynctask/iscanceled/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η εργασία ακυρώθηκε. |
| [IsFaulted](../../aspose.psd.asynctask/iasynctask/isfaulted/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η εργασία παρουσίασε σφάλμα. |
| [Progress](../../aspose.psd.asynctask/iasynctask/progress/) { get; } | Λαμβάνει την πρόοδο της ασύγχρονης εργασίας. |
| [Result](../../aspose.psd.asynctask/iasynctask/result/) { get; } | Λαμβάνει το αποτέλεσμα αυτής της εργασίας. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Abort](../../aspose.psd.asynctask/iasynctask/abort/)() | Ακυρώνει αυτήν την εργασία. Η εργασία ολοκληρώνεται αμέσως, με τον κίνδυνο να μην ελευθερωθούν εσωτερικοί μη διαχειριζόμενοι πόροι. |
| [Cancel](../../aspose.psd.asynctask/iasynctask/cancel/)() | Ακυρώνει αυτήν την εργασία. Η εργασία ολοκληρώνεται με ασφάλεια μέσω του ελεγχόμενου τερματισμού του αλγορίθμου. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync)() | Εκτελεί αυτήν την εργασία. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | Εκτελεί αυτήν την εργασία. |
| [SetCompleteCallback](../../aspose.psd.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | Ορίζει το delegate κλήσης επιστροφής ολοκλήρωσης. |
| [SetProgressCallback](../../aspose.psd.asynctask/iasynctask/setprogresscallback/)(ProgressCallback) | Ορίζει το delegate κλήσης επιστροφής προόδου. |

### Δείτε επίσης

* namespace [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* assembly [Aspose.PSD](../../)


