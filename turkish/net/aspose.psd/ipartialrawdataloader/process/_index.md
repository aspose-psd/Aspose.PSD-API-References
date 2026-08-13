---
title: "IPartialRawDataLoader.Process"
second_title: "Aspose.PSD for .NET API Referansı"
description: "IPartialRawDataLoader yöntemi. Yüklenen veriyi işler"
type: docs
weight: 10
url: /tr/net/aspose.psd/ipartialrawdataloader/process/
---
{{< psd/tize >}}
## Process(Rectangle, byte[], Point, Point) {#process}

Yüklenen verileri işler.

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dikdörtgen | Rectangle | Veri dikdörtgeni. |
| veri | Byte[] | Ham veri. |
| başlangıç | Point | Başlangıç veri noktası. (sol,üst) ile eşit değilse, tam bir dikdörtgen olmadığını ifade eder. |
| son | Point | Bitiş veri noktası. (right,bottom) değerine eşit değilse, bunun tam bir dikdörtgen olmadığı anlamına gelir. |

### Ayrıca Bakınız

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* interface [IPartialRawDataLoader](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Process(Rectangle, byte[], Point, Point, LoadOptions) {#process_1}

Yüklenen verileri işler.

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end, 
    LoadOptions loadOptions)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dikdörtgen | Rectangle | Veri dikdörtgeni. |
| veri | Byte[] | Ham veri. |
| başlangıç | Point | Başlangıç veri noktası. (sol,üst) ile eşit değilse, tam bir dikdörtgen olmadığını ifade eder. |
| son | Point | Bitiş veri noktası. (right,bottom) değerine eşit değilse, bunun tam bir dikdörtgen olmadığı anlamına gelir. |
| loadOptions | LoadOptions | Yükleme seçenekleri. |

### Ayrıca Bakınız

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [LoadOptions](../../loadoptions/)
* interface [IPartialRawDataLoader](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


