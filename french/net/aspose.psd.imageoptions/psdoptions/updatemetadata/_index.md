---
title: "PsdOptions.UpdateMetadata"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété PsdOptions. Obtient ou définit une valeur indiquant si les métadonnées doivent être mises à jour. Si la valeur est vraie, les métadonnées seront mises à jour lors de l'enregistrement d'une image."
type: docs
weight: 110
url: /fr/net/aspose.psd.imageoptions/psdoptions/updatemetadata/
---
{{< psd/tize >}}
## PsdOptions.UpdateMetadata property

Obtient ou définit une valeur indiquant si [update metadata]. Si la valeur est vraie, les métadonnées seront mises à jour lors de l'enregistrement de l'image.

```csharp
public bool UpdateMetadata { get; set; }
```

### Property Value

`true` si [update metadata] ; sinon, `false`.

## Exemples

Le code suivant montre l'utilisation de l'option UpdateMetadata pour mettre à jour la valeur CreatorTool dans les données xmp.

```csharp
[C#]

string path = "output.psd";

using (var image = new PsdImage(100, 100))
{
    // Si vous souhaitez que l'outil créateur change, assurez-vous que la propriété "UpdateMetadata" est définie sur true. Elle est définie sur true par défaut.
    var psdOptions = new PsdOptions();
    psdOptions.UpdateMetadata = true;

    // Enregistrement de l'image. 
    image.Save(path, psdOptions);

    // Vérification de l'outil créateur dans le code.
    var xmpData = image.XmpData;
    var basicPackage = image.XmpData.GetPackage(Namespaces.XmpBasic);

    // Ici seront mises à jour les informations de l'outil créateur.
    var currentCreatorTool = (string)basicPackage[":CreatorTool"];
}
```

### Voir aussi

* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


