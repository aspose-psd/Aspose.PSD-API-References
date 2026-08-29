---
title: "XmpBasicPackage.SetValue"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode XmpBasicPackage. Définit la valeur"
type: docs
weight: 120
url: /fr/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/setvalue/
---
{{< psd/tize >}}
## XmpBasicPackage.SetValue method

Définit la valeur.

```csharp
public override void SetValue(string key, IXmlValue value)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| clé | String | La représentation sous forme de chaîne de la clé qui est identifiée avec la valeur ajoutée. |
| valeur | IXmlValue | La valeur à ajouter. |

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

* interface [IXmlValue](../../../aspose.psd.xmp/ixmlvalue/)
* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


