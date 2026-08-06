---
title: "IAsyncTask"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "La tâche asynchrone."
type: docs
weight: 16
url: /fr/java/com.aspose.psd.asynctask/iasynctask/
---

**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult, com.aspose.ms.System.IDisposable
```
public interface IAsyncTask extends System.IAsyncResult, System.IDisposable
```

La tâche asynchrone.
## Méthodes

| Méthode | Description |
| --- | --- |
| [abort()](#abort--) | Interrompt cette tâche. |
| [cancel()](#cancel--) | Annule cette tâche. |
| [getError()](#getError--) | Obtient l'erreur de la tâche qui est disponible après que la tâche est terminée. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Obtient le gestionnaire d'événement de progression de la tâche asynchrone. |
| [getResult()](#getResult--) | Obtient le résultat de cette tâche. |
| [isBusy()](#isBusy--) | Obtient une valeur indiquant si cette tâche est actuellement en cours d'exécution. |
| [isCanceled()](#isCanceled--) | Obtient une valeur indiquant si cette tâche a été annulée. |
| [isFaulted()](#isFaulted--) | Obtient une valeur indiquant si cette tâche a échoué. |
| [runAsync()](#runAsync--) | Exécute cette tâche. |
| [runAsync(int priority)](#runAsync-int-) | Exécute cette tâche. |
| [setCompleteCallback(CompleteCallback completeCallback)](#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-) | Définit le délégué de rappel complet. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Définit le gestionnaire d'événement de progression de la tâche asynchrone. |
### abort() {#abort--}
```
public abstract void abort()
```


Interrompt cette tâche. La tâche est terminée immédiatement, avec le risque de ne pas libérer les ressources internes non gérées.

### cancel() {#cancel--}
```
public abstract void cancel()
```


Annule cette tâche. La tâche est terminée en toute sécurité par l'arrêt contrôlé de l'algorithme.

### getError() {#getError--}
```
public abstract Throwable getError()
```


Obtient l'erreur de la tâche qui est disponible après que la tâche est terminée.

Valeur : L'erreur de la tâche.

**Returns:**
java.lang.Throwable - l'erreur de la tâche qui est disponible après que la tâche est terminée.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public abstract ProgressEventHandler getProgressEventHandler()
```


Obtient le gestionnaire d'événement de progression de la tâche asynchrone.

Valeur : Le gestionnaire d'événement de progression de la tâche asynchrone.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler of the asynchronous task.
### getResult() {#getResult--}
```
public abstract Object getResult()
```


Obtient le résultat de cette tâche.

Valeur : Le résultat de cette tâche.

**Returns:**
java.lang.Object - le résultat de cette tâche.
### isBusy() {#isBusy--}
```
public abstract boolean isBusy()
```


Obtient une valeur indiquant si cette tâche est actuellement en cours d'exécution.

Valeur :  true  si cette tâche est actuellement en cours d'exécution ; sinon,  false .

**Returns:**
booléen - une valeur indiquant si cette tâche est actuellement en cours d'exécution.
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Obtient une valeur indiquant si cette tâche a été annulée.

Valeur :  true  si cette tâche a été annulée ; sinon,  false .

**Returns:**
booléen - une valeur indiquant si cette tâche a été annulée.
### isFaulted() {#isFaulted--}
```
public abstract boolean isFaulted()
```


Obtient une valeur indiquant si cette tâche a échoué.

Valeur :  true  si cette tâche a échoué ; sinon,  false .

**Returns:**
booléen - une valeur indiquant si cette tâche a échoué.
### runAsync() {#runAsync--}
```
public abstract void runAsync()
```


Exécute cette tâche.

### runAsync(int priority) {#runAsync-int-}
```
public abstract void runAsync(int priority)
```


Exécute cette tâche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| priorité | int | La priorité du thread. |

### setCompleteCallback(CompleteCallback completeCallback) {#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-}
```
public abstract void setCompleteCallback(CompleteCallback completeCallback)
```


Définit le délégué de rappel complet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| completeCallback | [CompleteCallback](../../com.aspose.psd.asynctask/completecallback) | Le rappel complet. |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public abstract void setProgressEventHandler(ProgressEventHandler value)
```


Définit le gestionnaire d'événement de progression de la tâche asynchrone.

Valeur : Le gestionnaire d'événement de progression de la tâche asynchrone.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | le gestionnaire d'événement de progression de la tâche asynchrone. |

