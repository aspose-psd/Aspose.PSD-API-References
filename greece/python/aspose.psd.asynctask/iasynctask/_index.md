---
title: "IAsyncTask Κλάση"
type: docs
weight: 40
url: /el/python-net/aspose.psd.asynctask/iasynctask/
---

**Summary:** The asynchronous task.

**Module:** [aspose.psd.asynctask](/psd/python-net/aspose.psd.asynctask/)

**Full Name:** aspose.psd.asynctask.IAsyncTask

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| is_busy | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η εργασία εκτελείται αυτή τη στιγμή. |
| is_canceled | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η εργασία ακυρώθηκε. |
| is_faulted | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η εργασία παρουσίασε σφάλμα. |
| progress | [AsyncTaskProgress](/psd/python-net/aspose.psd.asynctask/asynctaskprogress) | r | Λαμβάνει την πρόοδο της ασύγχρονης εργασίας. |
| result | object | r | Λαμβάνει το αποτέλεσμα αυτής της εργασίας. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| abort() | Ακυρώνει αυτή την εργασία.<br/>            Η εργασία ολοκληρώνεται άμεσα, με κίνδυνο να μην ελευθερωθούν εσωτερικοί μη διαχειριζόμενοι πόροι. |
| cancel() | Ακυρώνει αυτή την εργασία.<br/>            Η εργασία ολοκληρώνεται με ασφάλεια μέσω ελεγχόμενης διακοπής του αλγορίθμου. |
| run_async() | Εκτελεί αυτή την εργασία. |


