---
title: FrameDisposalMethod
second_title: Справочник по Aspose.PSD для .NET API
description: Метод удаления кадров указывает следует ли отбрасывать текущий кадр перед отображением следующего кадра. Вы выбираете метод удаления для анимаций включающих прозрачность фона чтобы указать будет ли кадр current виден через прозрачные области следующего кадра.
type: docs
weight: 1840
url: /ru/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
## FrameDisposalMethod enumeration

Метод удаления кадров указывает, следует ли отбрасывать текущий кадр перед отображением следующего кадра. Вы выбираете метод удаления для анимаций, включающих прозрачность фона, чтобы указать, будет ли кадр current виден через прозрачные области следующего кадра.

```csharp
public enum FrameDisposalMethod
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| Automatic | `0` | Автоматически определяет метод удаления для текущего кадра, отбрасывая текущий кадр, если следующий кадр содержит прозрачность слоя. Для большинства анимаций параметр «Автоматически» (по умолчанию) дает желаемые результаты. |
| DoNotDispose | `1` | Сохраняет текущий кадр при добавлении следующего кадра на дисплей. Текущий кадр (и предшествующие кадры) могут отображаться сквозь прозрачные области следующего кадра. |
| Dispose | `2` | Отбрасывает текущий кадр с экрана перед отображением следующего кадра. В каждый момент времени отображается только один кадр (и текущий кадр не виден через прозрачные области следующего кадра). |

### Смотрите также

* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->