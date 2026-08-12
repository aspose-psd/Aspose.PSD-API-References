---
title: "Klass DataStreamSupporter"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.DataStreamSupporter-klass. Datastream-behållaren"
type: docs
weight: 750
url: /sv/net/aspose.psd/datastreamsupporter/
---
{{< psd/tize >}}
## DataStreamSupporter class

Datastreambehållaren.

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Hämtar objektets datastream. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Hämtar ett värde som indikerar om denna instans har frigjorts. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Hämtar ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Cachar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från den underliggande [`DataStreamContainer`](./datastreamcontainer/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Frigör den aktuella instansen. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save)() | Sparar objektets data till den aktuella `DataStreamSupporter`. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_1)(Stream) | Sparar objektets data till den angivna strömmen. |
| [Save](../../aspose.psd/datastreamsupporter/save/#save_2)(string) | Sparar objektets data till den angivna filplatsen. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_3)(string, bool) | Sparar objektets data till den angivna filplatsen. |

### Se även

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


