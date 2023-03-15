---
title: IPartialRawDataLoader.Process
second_title: Aspose.PSD für .NET-API-Referenz
description: IPartialRawDataLoader methode. Verarbeitet die geladenen Daten.
type: docs
weight: 10
url: /de/net/aspose.psd/ipartialrawdataloader/process/
---
## Process(Rectangle, byte[], Point, Point) {#process}

Verarbeitet die geladenen Daten.

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | Rectangle | Das Datenrechteck. |
| data | Byte[] | Die Rohdaten. |
| start | Point | Der Startdatenpunkt. Wenn nicht gleich (links, oben), bedeutet dies, dass es kein vollständiges Rechteck ist, das wir haben. |
| end | Point | Der Enddatenpunkt. Wenn nicht gleich (rechts, unten), bedeutet dies, dass es kein vollständiges Rechteck ist, das wir haben. |

### Siehe auch

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* interface [IPartialRawDataLoader](../)
* namensraum [Aspose.PSD](../../ipartialrawdataloader/)
* Montage [Aspose.PSD](../../../)

---

## Process(Rectangle, byte[], Point, Point, LoadOptions) {#process_1}

Verarbeitet die geladenen Daten.

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end, 
    LoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | Rectangle | Das Datenrechteck. |
| data | Byte[] | Die Rohdaten. |
| start | Point | Der Startdatenpunkt. Wenn nicht gleich (links, oben), bedeutet dies, dass es kein vollständiges Rechteck ist, das wir haben. |
| end | Point | Der Enddatenpunkt. Wenn nicht gleich (rechts, unten), bedeutet dies, dass es kein vollständiges Rechteck ist, das wir haben. |
| loadOptions | LoadOptions | Die Ladeoptionen. |

### Siehe auch

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [LoadOptions](../../loadoptions/)
* interface [IPartialRawDataLoader](../)
* namensraum [Aspose.PSD](../../ipartialrawdataloader/)
* Montage [Aspose.PSD](../../../)


