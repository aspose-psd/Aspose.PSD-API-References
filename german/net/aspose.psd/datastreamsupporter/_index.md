---
title: "Klasse DataStreamSupporter"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.DataStreamSupporter Klasse. Der Datenstrom-Container"
type: docs
weight: 750
url: /de/net/aspose.psd/datastreamsupporter/
---
{{< psd/tize >}}
## DataStreamSupporter class

Der Datenstrom-Container.

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Liest den Datenstrom des Objekts. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Liest einen Wert, der angibt, ob diese Instanz freigegeben wurde. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Liest einen Wert, der angibt, ob die Daten des Objekts derzeit im Cache sind und kein Datenlesen erforderlich ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Puffert die Daten und stellt sicher, dass keine zusätzlichen Datenladungen vom zugrunde liegenden [`DataStreamContainer`](./datastreamcontainer/) durchgeführt werden. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Gibt die aktuelle Instanz frei. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save)() | Speichert die Daten des Objekts im aktuellen `DataStreamSupporter`. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_1)(Stream) | Speichert die Objektdaten in den angegebenen Stream. |
| [Save](../../aspose.psd/datastreamsupporter/save/#save_2)(string) | Speichert die Objektdaten am angegebenen Speicherort. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_3)(string, bool) | Speichert die Objektdaten am angegebenen Speicherort. |

### Siehe auch

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


