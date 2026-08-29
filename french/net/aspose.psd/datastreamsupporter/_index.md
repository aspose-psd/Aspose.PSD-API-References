---
title: "Classe DataStreamSupporter"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.DataStreamSupporter. Le conteneur de flux de données"
type: docs
weight: 750
url: /fr/net/aspose.psd/datastreamsupporter/
---
{{< psd/tize >}}
## DataStreamSupporter class

Le conteneur de flux de données.

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## Propriétés

| Nom | Description |
| --- | --- |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Obtient le flux de données de l'objet. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est libérée. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Obtient une valeur indiquant si les données de l'objet sont actuellement en cache et qu'aucune lecture de données n'est requise. |

## Méthodes

| Nom | Description |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Met en cache les données et garantit qu'aucun chargement de données supplémentaire ne sera effectué à partir du [`DataStreamContainer`](./datastreamcontainer/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Libère l'instance actuelle. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save)() | Enregistre les données de l'objet dans le `DataStreamSupporter` actuel. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_1)(Stream) | Enregistre les données de l'objet dans le flux spécifié. |
| [Save](../../aspose.psd/datastreamsupporter/save/#save_2)(string) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_3)(string, bool) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |

### Voir aussi

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


