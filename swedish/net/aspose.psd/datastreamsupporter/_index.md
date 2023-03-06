---
title: Class DataStreamSupporter
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.DataStreamSupporter klass. Dataströmsbehållaren.
type: docs
weight: 740
url: /sv/net/aspose.psd/datastreamsupporter/
---
## DataStreamSupporter class

Dataströmsbehållaren.

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Hämtar objektets dataström. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Får ett värde som indikerar om objektets data är cachad för närvarande och ingen dataläsning krävs. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Cachelagrar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från det underliggande[`DataStreamContainer`](./datastreamcontainer/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Tar bort den aktuella instansen. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save)() | Sparar objektets data till den aktuella`DataStreamSupporter` . |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_1)(Stream) | Sparar objektets data till den angivna strömmen. |
| [Save](../../aspose.psd/datastreamsupporter/save/#save_2)(string) | Sparar objektets data till den angivna filplatsen. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_3)(string, bool) | Sparar objektets data till den angivna filplatsen. |

### Se även

* class [DisposableObject](../disposableobject/)
* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


