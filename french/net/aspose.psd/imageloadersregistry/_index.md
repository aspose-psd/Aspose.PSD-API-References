---
title: "Classe ImageLoadersRegistry"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.ImageLoadersRegistry. Représente le registre des chargeurs d'images."
type: docs
weight: 5270
url: /fr/net/aspose.psd/imageloadersregistry/
---
{{< psd/tize >}}
## ImageLoadersRegistry class

Représente le registre des chargeurs d'images.

```csharp
public static class ImageLoadersRegistry
```

## Propriétés

| Nom | Description |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imageloadersregistry/registereddescriptors/) { get; } | Obtient les descripteurs enregistrés. |
| static [RegisteredFormats](../../aspose.psd/imageloadersregistry/registeredformats/) { get; } | Obtient les formats de chargement d'images enregistrés. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.psd/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | Crée le premier chargeur trouvé adapté au *stream* spécifié et éventuellement aux *loadOptions*. |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | Obtient le premier descripteur pris en charge trouvé adapté au *stream* spécifié et éventuellement aux *loadOptions*. |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | Obtient le premier format de fichier pris en charge par son nom de type. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | Obtient le premier descripteur pris en charge par son nom de type. |
| static [Register](../../aspose.psd/imageloadersregistry/register/)(IImageLoaderDescriptor) | Enregistre le descripteur de chargeur d'images spécifié. |
| static [RegisterLoader](../../aspose.psd/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | Enregistre le chargeur. |
| static [UnregisterLoader](../../aspose.psd/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | Désenregistre le chargeur. |

### Voir aussi

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


