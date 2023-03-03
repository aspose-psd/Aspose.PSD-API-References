---
title: Class ImageExportersRegistry
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.ImageExportersRegistry classe. Représente le registre des exportateurs dimages.
type: docs
weight: 4630
url: /fr/net/aspose.psd/imageexportersregistry/
---
## ImageExportersRegistry class

Représente le registre des exportateurs d'images.

```csharp
public static class ImageExportersRegistry
```

## Propriétés

| Nom | La description |
| --- | --- |
| static [RegisteredExporterDescriptors](../../aspose.psd/imageexportersregistry/registeredexporterdescriptors/) { get; } | Obtient les descripteurs d'exportateurs enregistrés. |
| static [RegisteredFormats](../../aspose.psd/imageexportersregistry/registeredformats/) { get; } | Obtient les formats d'exportation enregistrés. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [CreateFirstSupportedExporter](../../aspose.psd/imageexportersregistry/createfirstsupportedexporter/)(Image, ImageOptionsBase) | Crée le premier exportateur trouvé adapté aux options d'enregistrement et à l'image spécifiées. |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/)(Image, ImageOptionsBase) | Obtient le premier descripteur pris en charge trouvé adapté aux options d'enregistrement et à l'image spécifiées. |
| static [Register](../../aspose.psd/imageexportersregistry/register/)(IImageExporterDescriptor) | Enregistre le descripteur d'exportateur d'image spécifié. |
| static [RegisterExporter](../../aspose.psd/imageexportersregistry/registerexporter/)(IImageExporterDescriptor) | Enregistre l'exportateur. |
| static [UnregisterExporter](../../aspose.psd/imageexportersregistry/unregisterexporter/)(IImageExporterDescriptor) | Désenregistre l'exportateur. |

### Voir également

* espace de noms [Aspose.PSD](../../aspose.psd/)
* Assemblée [Aspose.PSD](../../)


