---
title: "IAsyncTask Klasse"
type: docs
weight: 40
url: /de/python-net/aspose.psd.asynctask/iasynctask/
---

**Summary:** The asynchronous task.

**Module:** [aspose.psd.asynctask](/psd/python-net/aspose.psd.asynctask/)

**Full Name:** aspose.psd.asynctask.IAsyncTask

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| is_busy | bool | r | Gibt einen Wert zurück, der angibt, ob diese Aufgabe gerade ausgeführt wird. |
| is_canceled | bool | r | Gibt einen Wert zurück, der angibt, ob diese Aufgabe abgebrochen wurde. |
| is_faulted | bool | r | Gibt einen Wert zurück, der angibt, ob diese Aufgabe fehlerhaft war. |
| progress | [AsyncTaskProgress](/psd/python-net/aspose.psd.asynctask/asynctaskprogress) | r | Gibt den Fortschritt der asynchronen Aufgabe zurück. |
| result | object | r | Gibt das Ergebnis dieser Aufgabe zurück. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| abort() | Bricht diese Aufgabe ab.<br/>            Die Aufgabe wird sofort abgeschlossen, mit dem Risiko, interne nicht verwaltete Ressourcen nicht freizugeben. |
| cancel() | Storniert diese Aufgabe.<br/>            Die Aufgabe wird sicher abgeschlossen, indem der Algorithmus kontrolliert gestoppt wird. |
| run_async() | Führt diese Aufgabe aus. |


