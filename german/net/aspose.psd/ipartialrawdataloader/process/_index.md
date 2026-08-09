---
title: "IPartialRawDataLoader.Process"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "IPartialRawDataLoader-Methode. Verarbeitet die geladenen Daten"
type: docs
weight: 10
url: /de/net/aspose.psd/ipartialrawdataloader/process/
---
{{< psd/tize >}}
## Process(Rectangle, byte[], Point, Point) {#process}

Verarbeitet die geladenen Daten.

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Rechteck | Rectangle | Das Datenrechteck. |
| Daten | Byte[] | Die Rohdaten. |
| start | Point | Der Startdatenpunkt. Wenn er nicht gleich (links,oben) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |
| Ende | Point | Der Enddatenpunkt. Wenn er nicht gleich (rechts,unten) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |

### Siehe auch

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* interface [IPartialRawDataLoader](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Process(Rectangle, byte[], Point, Point, LoadOptions) {#process_1}

Verarbeitet die geladenen Daten.

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end, 
    LoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Rechteck | Rectangle | Das Datenrechteck. |
| Daten | Byte[] | Die Rohdaten. |
| start | Point | Der Startdatenpunkt. Wenn er nicht gleich (links,oben) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |
| Ende | Point | Der Enddatenpunkt. Wenn er nicht gleich (rechts,unten) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |
| loadOptions | LoadOptions | Die Ladeoptionen. |

### Siehe auch

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [LoadOptions](../../loadoptions/)
* interface [IPartialRawDataLoader](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


