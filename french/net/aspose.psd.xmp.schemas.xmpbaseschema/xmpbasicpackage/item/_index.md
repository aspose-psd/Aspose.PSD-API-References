---
title: "XmpBasicPackage.Item"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété XmpBasicPackage. Obtient ou définit l'Object avec la clé spécifiée"
type: docs
weight: 20
url: /fr/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/item/
---
{{< psd/tize >}}
## XmpBasicPackage indexer

Obtient ou définit l'Objet avec la clé spécifiée.

```csharp
public override object this[string key] { get; set; }
```

| Paramètre | Description |
| --- | --- |
| clé | La clé qui identifie la valeur. |

### Valeur de retour

Renvoie l'Object avec la clé spécifiée.

### Property Value

L'Object.

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

* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


