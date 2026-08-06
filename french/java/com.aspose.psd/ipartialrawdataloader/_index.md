---
title: "IPartialRawDataLoader"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Le chargeur de données partielles."
type: docs
weight: 133
url: /fr/java/com.aspose.psd/ipartialrawdataloader/
---
```
public interface IPartialRawDataLoader
```

Le chargeur de données partielles.
## Méthodes

| Méthode | Description |
| --- | --- |
| [process(Rectangle rectangle, byte[] data, Point start, Point end)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-) | Traite les données chargées. |
| [process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-) | Traite les données chargées. |
### process(Rectangle rectangle, byte[] data, Point start, Point end) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end)
```


Traite les données chargées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle de données. |
| données | byte[] | Les données brutes. |
| start | [Point](../../com.aspose.psd/point) | Le point de données de départ. S'il n'est pas égal à (left,top) cela signifie que nous n'avons pas un rectangle complet. |
| end | [Point](../../com.aspose.psd/point) | Le point de données de fin. S'il n'est pas égal à (right,bottom) cela signifie que nous n'avons pas un rectangle complet. |

### process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)
```


Traite les données chargées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle de données. |
| données | byte[] | Les données brutes. |
| start | [Point](../../com.aspose.psd/point) | Le point de données de départ. S'il n'est pas égal à (left,top) cela signifie que nous n'avons pas un rectangle complet. |
| end | [Point](../../com.aspose.psd/point) | Le point de données de fin. S'il n'est pas égal à (right,bottom) cela signifie que nous n'avons pas un rectangle complet. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Les options de chargement. |

