---
title: Interface IAsyncTask
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.AsyncTask.IAsyncTask διεπαφή. Η ασύγχρονη εργασία.
type: docs
weight: 80
url: /el/net/aspose.psd.asynctask/iasynctask/
---
## IAsyncTask interface

Η ασύγχρονη εργασία.

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Error](../../aspose.psd.asynctask/iasynctask/error/) { get; } | Λαμβάνει το σφάλμα εργασίας που είναι διαθέσιμο μετά την ολοκλήρωση της εργασίας. |
| [IsBusy](../../aspose.psd.asynctask/iasynctask/isbusy/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η εργασία εκτελείται αυτήν τη στιγμή. |
| [IsCanceled](../../aspose.psd.asynctask/iasynctask/iscanceled/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η εργασία ακυρώθηκε. |
| [IsFaulted](../../aspose.psd.asynctask/iasynctask/isfaulted/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η εργασία ήταν σφάλμα. |
| [Progress](../../aspose.psd.asynctask/iasynctask/progress/) { get; } | Λαμβάνει την πρόοδο της ασύγχρονης εργασίας. |
| [Result](../../aspose.psd.asynctask/iasynctask/result/) { get; } | Λαμβάνει το αποτέλεσμα αυτής της εργασίας. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Abort](../../aspose.psd.asynctask/iasynctask/abort/)() | Ματαιώνει αυτήν την εργασία. Η εργασία ολοκληρώνεται αμέσως, με κίνδυνο να μην απελευθερωθούν εσωτερικοί μη διαχειριζόμενοι πόροι. |
| [Cancel](../../aspose.psd.asynctask/iasynctask/cancel/)() | Ακυρώνει αυτήν την εργασία. Η εργασία ολοκληρώνεται με ασφάλεια με την ελεγχόμενη διακοπή του αλγορίθμου. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync)() | Εκτελεί αυτήν την εργασία. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | Εκτελεί αυτήν την εργασία. |
| [SetCompleteCallback](../../aspose.psd.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | Ορίζει τον πλήρη εκπρόσωπο επανάκλησης. |
| [SetProgressCallback](../../aspose.psd.asynctask/iasynctask/setprogresscallback/)(ProgressCallback) | Ορίζει τον εκπρόσωπο επανάκλησης προόδου. |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* συνέλευση [Aspose.PSD](../../)


