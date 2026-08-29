---
title: "ImageLoadersRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode ImageLoadersRegistry. Obtient le premier descripteur pris en charge trouvé adapté au flux spécifié et éventuellement aux loadOptions"
type: docs
weight: 40
url: /fr/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

Obtient le premier descripteur pris en charge trouvé adapté au *stream* spécifié et éventuellement aux *loadOptions*.

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Le flux. |
| loadOptions | LoadOptions | Les options de chargement. |

### Valeur de retour

Le descripteur de chargeur qui prend en charge le *stream* spécifié et les *loadOptions* ou null si aucun tel descripteur n'est trouvé.

## Remarques

Le premier descripteur de chargeur sera en fait le dernier enregistré.

### Voir aussi

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


