---
title: "Перечисление LayerLockType"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LayerLockType enum. Параметры блокировки слоя."
type: docs
weight: 2890
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/
---
{{< psd/tize >}}
## LayerLockType enumeration

Параметры блокировки слоя

```csharp
[Flags]
public enum LayerLockType
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | `0` | Без блокировки слоя |
| LockTransparentPixels | `1` | Частичная блокировка слоя — ограничивает редактирование непрозрачными участками слоя. Эта опция эквивалентна параметру Preserve Transparency в более ранних версиях Photoshop. |
| LockImagePixels | `2` | Частичная блокировка слоя — предотвращает изменение пикселей слоя с помощью инструментов рисования. |
| LockPosition | `4` | Частичная блокировка слоя — предотвращает перемещение пикселей слоя. |
| LockAll | `7` | Блокировать все свойства слоя |

### См. также

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


