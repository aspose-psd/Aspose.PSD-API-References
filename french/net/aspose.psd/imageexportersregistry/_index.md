---
title: "Classe ImageExportersRegistry"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.ImageExportersRegistry. Représente le registre des exportateurs d'images"
type: docs
weight: 5100
url: /fr/net/aspose.psd/imageexportersregistry/
---
{{< psd/tize >}}
## ImageExportersRegistry class

Représente le registre des exportateurs d'images.

```csharp
public static class ImageExportersRegistry
```

## Propriétés

| Nom | Description |
| --- | --- |
| static [RegisteredExporterDescriptors](../../aspose.psd/imageexportersregistry/registeredexporterdescriptors/) { get; } | Obtient les descripteurs d'exportateur enregistrés. |
| static [RegisteredFormats](../../aspose.psd/imageexportersregistry/registeredformats/) { get; } | Obtient les formats d'exportation enregistrés. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [CreateFirstSupportedExporter](../../aspose.psd/imageexportersregistry/createfirstsupportedexporter/)(Image, ImageOptionsBase) | Crée le premier exportateur trouvé adapté aux options d'enregistrement et à l'image spécifiées. |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/)(Image, ImageOptionsBase) | Obtient le premier descripteur pris en charge trouvé adapté aux options d'enregistrement et à l'image spécifiées. |
| static [Register](../../aspose.psd/imageexportersregistry/register/)(IImageExporterDescriptor) | Enregistre le descripteur d'exportateur d'image spécifié. |
| static [RegisterExporter](../../aspose.psd/imageexportersregistry/registerexporter/)(IImageExporterDescriptor) | Enregistre l'exportateur. |
| static [UnregisterExporter](../../aspose.psd/imageexportersregistry/unregisterexporter/)(IImageExporterDescriptor) | Désenregistre l'exportateur. |

### Voir aussi

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


