---
title: "ImageExportersRegistry.CreateFirstSupportedExporter"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode ImageExportersRegistry. Crée le premier exportateur trouvé adapté aux options d’enregistrement et à l’image spécifiées"
type: docs
weight: 30
url: /fr/net/aspose.psd/imageexportersregistry/createfirstsupportedexporter/
---
{{< psd/tize >}}
## ImageExportersRegistry.CreateFirstSupportedExporter method

Crée le premier exportateur trouvé adapté aux options d'enregistrement et à l'image spécifiées.

```csharp
public static IImageExporter CreateFirstSupportedExporter(Image image, ImageOptionsBase options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| image | Image | L’image à exporter. |
| options | ImageOptionsBase | Les options d’enregistrement à utiliser pour l’exportation. |

### Valeur de retour

L’exportateur qui prend en charge l’image et les options d’enregistrement spécifiées ou null si aucun tel exportateur n’est trouvé.

## Remarques

Le premier exportateur sera en réalité le dernier enregistré.

### Voir aussi

* interface [IImageExporter](../../iimageexporter/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


