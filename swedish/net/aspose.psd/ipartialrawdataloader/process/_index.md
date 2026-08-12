---
title: "IPartialRawDataLoader.Process"
second_title: "Aspose.PSD för .NET API‑referens"
description: "IPartialRawDataLoader-metoden. Bearbetar den inlästa datan."
type: docs
weight: 10
url: /sv/net/aspose.psd/ipartialrawdataloader/process/
---
{{< psd/tize >}}
## Process(Rectangle, byte[], Point, Point) {#process}

Bearbetar den inlästa datan.

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rektangel | Rectangle | Daterektangeln. |
| data | Byte[] | Den råa datan. |
| start | Punkt | Startdatapunkten. Om den inte är lika med (left,top) betyder det att vi inte har en fullständig rektangel. |
| end | Punkt | Slutdatapunkten. Om den inte är lika med (right,bottom) betyder det att vi inte har en fullständig rektangel. |

### Se även

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* interface [IPartialRawDataLoader](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Process(Rectangle, byte[], Point, Point, LoadOptions) {#process_1}

Bearbetar den inlästa datan.

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end, 
    LoadOptions loadOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rektangel | Rectangle | Daterektangeln. |
| data | Byte[] | Den råa datan. |
| start | Punkt | Startdatapunkten. Om den inte är lika med (left,top) betyder det att vi inte har en fullständig rektangel. |
| end | Punkt | Slutdatapunkten. Om den inte är lika med (right,bottom) betyder det att vi inte har en fullständig rektangel. |
| loadOptions | LoadOptions | Laddningsalternativen. |

### Se även

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [LoadOptions](../../loadoptions/)
* interface [IPartialRawDataLoader](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


