---
title: "SplitStreamContainer.Seek"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод SplitStreamContainer. Устанавливает позицию в текущем потоке"
type: docs
weight: 140
url: /ru/net/aspose.psd/splitstreamcontainer/seek/
---
{{< psd/tize >}}
## SplitStreamContainer.Seek method

Устанавливает позицию в текущем потоке.

```csharp
public override long Seek(long offset, SeekOrigin origin)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| offset | Int64 | Смещение в байтах относительно параметра *origin*. Это значение представляет собой смещение от начальной позиции потока, переданной в конструкторе StreamContainer. |
| origin | SeekOrigin | Значение типа SeekOrigin, указывающее точку отсчёта, используемую для получения новой позиции. |

### Возвращаемое значение

Новая позиция в текущем потоке.

### См. также

* enum [SeekOrigin](../../seekorigin/)
* class [SplitStreamContainer](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


