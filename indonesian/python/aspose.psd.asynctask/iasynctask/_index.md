---
title: "IAsyncTask Kelas"
type: docs
weight: 40
url: /id/python-net/aspose.psd.asynctask/iasynctask/
---

**Summary:** The asynchronous task.

**Module:** [aspose.psd.asynctask](/psd/python-net/aspose.psd.asynctask/)

**Full Name:** aspose.psd.asynctask.IAsyncTask

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| is_busy | bool | r | Mendapatkan nilai yang menunjukkan apakah tugas ini sedang berjalan. |
| is_canceled | bool | r | Mendapatkan nilai yang menunjukkan apakah tugas ini dibatalkan. |
| is_faulted | bool | r | Mendapatkan nilai yang menunjukkan apakah tugas ini mengalami kesalahan. |
| progress | [AsyncTaskProgress](/psd/python-net/aspose.psd.asynctask/asynctaskprogress) | r | Mendapatkan kemajuan tugas asinkron. |
| result | object | r | Mendapatkan hasil dari tugas ini. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| abort() | Menghentikan tugas ini.<br/>            Tugas selesai segera, dengan risiko tidak membebaskan sumber daya tidak terkelola internal. |
| cancel() | Membatalkan tugas ini.<br/>            Tugas selesai dengan aman melalui penghentian terkontrol dari algoritma. |
| run_async() | Menjalankan tugas ini. |


