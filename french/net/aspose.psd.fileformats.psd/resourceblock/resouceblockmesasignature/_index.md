---
title: "ResourceBlock.ResouceBlockMeSaSignature"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Champ ResourceBlock. La signature de la ressource d'ImageReady"
type: docs
weight: 90
url: /fr/net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
{{< psd/tize >}}
## ResourceBlock.ResouceBlockMeSaSignature field

La signature de ressource d'ImageReady.

```csharp
public const int ResouceBlockMeSaSignature;
```

## Exemples

L'exemple de code suivant démontre la capacité de charger et d'enregistrer correctement des fichiers PSD avec des ressources portant la signature MeSa.

```csharp
[C#]

void AreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Values are not equal.");
    }
}

string srcFile = "GST-CHALLAN(2)1..psd";
string output = "output.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(srcFile))
{
    AreEqual(ResourceBlock.ResouceBlockMeSaSignature, psdImage.ImageResources[23].Signature);
    AreEqual(ResourceBlock.ResouceBlockMeSaSignature, psdImage.ImageResources[24].Signature);
    psdImage.Save(output);
}
```

### Voir aussi

* class [ResourceBlock](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


