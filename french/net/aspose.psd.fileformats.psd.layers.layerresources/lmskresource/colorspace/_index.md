---
title: "LmskResource.ColorSpace"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "LmskResource propriété. Obtient l'espace couleur"
type: docs
weight: 60
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorspace/
---
{{< psd/tize >}}
## LmskResource.ColorSpace property

Obtient l'espace colorimétrique.

```csharp
public ColorSpace ColorSpace { get; set; }
```

### Property Value

L'espace couleur.

## Exemples

Le code suivant montre comment modifier les options d'affichage du masque de calque sur des images 16 bits en modifiant les propriétés LmskResource.

```csharp
[C#]

string sourceFile = "sourceFile.psd";
string outputPsd = "sourceFile_output.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// Charger l'image 16 bits.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    // Trouver LmskResource.
    LmskResource lmskResource = new LmskResource();
    foreach (var res in image.GlobalLayerResources)
    {
        if (res is LmskResource)
        {
            lmskResource = (LmskResource)res;
            break;
        }
    }

    // Vérifier les propriétés de LmskResource.
    AssertAreEqual(lmskResource.ColorSpace, ColorSpace.RGB);
    AssertAreEqual(lmskResource.ColorComponent1, (ushort)65535);
    AssertAreEqual(lmskResource.ColorComponent2, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent3, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent4, (ushort)0);
    AssertAreEqual(lmskResource.Opacity, (short)45);
    AssertAreEqual(lmskResource.Flag, (byte)128);

    // Modifier les propriétés de LmskResource.
    lmskResource.ColorSpace = ColorSpace.HSB;
    lmskResource.ColorComponent1 = 7854;
    lmskResource.ColorComponent2 = 10;
    lmskResource.ColorComponent3 = 15484;
    lmskResource.Opacity = 85;

    // Enregistrer l'image.
    image.Save(outputPsd);
}
```

### Voir aussi

* enum [ColorSpace](../../../aspose.psd.fileformats.psd.resources.enums/colorspace/)
* class [LmskResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


