---
title: "IPartialRawDataLoader.Process"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode IPartialRawDataLoader. Traite les données chargées"
type: docs
weight: 10
url: /fr/net/aspose.psd/ipartialrawdataloader/process/
---
{{< psd/tize >}}
## Process(Rectangle, byte[], Point, Point) {#process}

Traite les données chargées.

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | Rectangle | Le rectangle de données. |
| données | Byte[] | Les données brutes. |
| start | Point | Le point de données de départ. S'il n'est pas égal à (left,top), cela signifie que nous n'avons pas un rectangle complet. |
| fin | Point | Le point de données de fin. S'il n'est pas égal à (right,bottom), cela signifie que nous n'avons pas un rectangle complet. |

### Voir aussi

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* interface [IPartialRawDataLoader](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Process(Rectangle, byte[], Point, Point, LoadOptions) {#process_1}

Traite les données chargées.

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end, 
    LoadOptions loadOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | Rectangle | Le rectangle de données. |
| données | Byte[] | Les données brutes. |
| start | Point | Le point de données de départ. S'il n'est pas égal à (left,top), cela signifie que nous n'avons pas un rectangle complet. |
| fin | Point | Le point de données de fin. S'il n'est pas égal à (right,bottom), cela signifie que nous n'avons pas un rectangle complet. |
| loadOptions | LoadOptions | Les options de chargement. |

### Voir aussi

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [LoadOptions](../../loadoptions/)
* interface [IPartialRawDataLoader](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


