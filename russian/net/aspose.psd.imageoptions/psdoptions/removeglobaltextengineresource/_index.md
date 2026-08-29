---
title: "PsdOptions.RemoveGlobalTextEngineResource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство PsdOptions. Получает или задает значение, указывающее, следует ли удалять глобальный ресурс текстового движка. Используется для некоторых psd‑файлов с текстовыми слоями, когда после обработки их нельзя открыть в Adobe Photoshop из‑за отсутствия шрифтов, связанных с текстовыми слоями. После использования этой опции пользователь должен выполнить в открытом в Photoshop файле: Menu Text Process absent fonts. После этой операции весь текст появится снова. Обратите внимание, что эта операция может вызвать некоторые изменения окончательного макета."
type: docs
weight: 90
url: /ru/net/aspose.psd.imageoptions/psdoptions/removeglobaltextengineresource/
---
{{< psd/tize >}}
## PsdOptions.RemoveGlobalTextEngineResource property

Получает или задает значение, указывающее, следует ли — удалить глобальный ресурс текстового движка — используется для некоторых PSD‑файлов с текстовыми слоями, только в случае, когда после обработки их нельзя открыть в Adobe Photoshop (в основном из‑за отсутствующих шрифтов в текстовых слоях). После использования этой опции пользователю необходимо выполнить в открытом в Photoshop файле следующее: Меню "Text" -> "Process absent fonts". После этой операции весь текст появится снова. Обратите внимание, что эта операция может вызвать некоторые изменения окончательной компоновки.

```csharp
public bool RemoveGlobalTextEngineResource { get; set; }
```

### Property Value

`true` если [remove global text engine resource]; иначе, `false`.

### См. также

* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


