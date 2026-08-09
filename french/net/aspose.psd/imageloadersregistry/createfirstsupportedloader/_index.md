---
title: "ImageLoadersRegistry.CreateFirstSupportedLoader"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode ImageLoadersRegistry. Crée le premier chargeur trouvé compatible avec le flux spécifié et éventuellement les loadOptions"
type: docs
weight: 30
url: /fr/net/aspose.psd/imageloadersregistry/createfirstsupportedloader/
---
{{< psd/tize >}}
## ImageLoadersRegistry.CreateFirstSupportedLoader method

Crée le premier chargeur trouvé adapté au *stream* spécifié et éventuellement aux *loadOptions*.

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Le flux. |
| loadOptions | LoadOptions | Les options de chargement. |

### Valeur de retour

Le chargeur qui prend en charge le *stream* spécifié et les *loadOptions* ou null si aucun chargeur de ce type n'est trouvé.

## Remarques

Le premier chargeur sera en fait le dernier enregistré.

### Voir aussi

* interface [IImageLoader](../../iimageloader/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


