---
title: "ImageExportersRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode ImageExportersRegistry. Obtient le premier descripteur pris en charge trouvé adapté aux options d’enregistrement et à l’image spécifiées"
type: docs
weight: 40
url: /fr/net/aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## ImageExportersRegistry.GetFirstSupportedDescriptor method

Obtient le premier descripteur pris en charge trouvé adapté aux options d'enregistrement et à l'image spécifiées.

```csharp
public static IImageExporterDescriptor GetFirstSupportedDescriptor(Image image, 
    ImageOptionsBase options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| image | Image | L’image à exporter. |
| options | ImageOptionsBase | Les options. |

### Valeur de retour

Le descripteur d’exportateur qui prend en charge l’image et les options d’enregistrement spécifiées ou null si aucun tel descripteur n’est trouvé.

## Remarques

Le premier descripteur d’exportateur sera en réalité le dernier enregistré.

### Voir aussi

* interface [IImageExporterDescriptor](../../iimageexporterdescriptor/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


