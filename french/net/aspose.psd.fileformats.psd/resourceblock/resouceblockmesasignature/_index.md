---
title: ResourceBlock.ResouceBlockMeSaSignature
second_title: Référence de l'API Aspose.PSD pour .NET
description: ResourceBlock champ. La signature de ressource de ImageReady.
type: docs
weight: 90
url: /fr/net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
## ResourceBlock.ResouceBlockMeSaSignature field

La signature de ressource de ImageReady.

```csharp
public const int ResouceBlockMeSaSignature;
```

### Exemples

L'exemple de code suivant montre la capacité de corriger le chargement et d'enregistrer des fichiers PSD avec des ressources avec la signature MeSa.

```csharp
[C#]

void AreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Values are not equal.");
    }
}

string srcFile = "GST-CHALLAN(21..psd");
string output = "output.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(srcFile))
{
    AreEqual(ResourceBlock.ResouceBlockMeSaSignature, psdImage.ImageResources[23].Signature);
    AreEqual(ResourceBlock.ResouceBlockMeSaSignature, psdImage.ImageResources[24].Signature);
    psdImage.Save(output);
}
```

### Voir également

* class [ResourceBlock](../)
* espace de noms [Aspose.PSD.FileFormats.Psd](../../resourceblock/)
* Assemblée [Aspose.PSD](../../../)


