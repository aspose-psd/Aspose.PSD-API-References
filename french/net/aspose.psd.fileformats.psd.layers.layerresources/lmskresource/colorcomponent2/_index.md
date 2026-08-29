---
title: "LmskResource.ColorComponent2"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété LmskResource. Obtient le composant couleur 2"
type: docs
weight: 30
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent2/
---
{{< psd/tize >}}
## LmskResource.ColorComponent2 property

Obtient le composant couleur 2.

```csharp
public ushort ColorComponent2 { get; set; }
```

### Property Value

Le composant couleur 2.

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

* class [LmskResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


