---
title: "IInterruptMonitor"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет информацию о прерывании."
type: docs
weight: 11
url: /ru/java/com.aspose.psd.multithreading/iinterruptmonitor/
---
```
public interface IInterruptMonitor
```

Представляет информацию о прерывании.
## Методы

| Метод | Описание |
| --- | --- |
| [interrupt()](#interrupt--) | Отправляет запрос на прерывание операций. |
| [isInterrupted()](#isInterrupted--) | Получает значение, указывающее, следует ли прерывать операции. |
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```


Отправляет запрос на прерывание операций.

### isInterrupted() {#isInterrupted--}
```
public abstract boolean isInterrupted()
```


Получает значение, указывающее, следует ли прерывать операции.

**Returns:**
boolean - значение, указывающее, следует ли прерывать операции.
