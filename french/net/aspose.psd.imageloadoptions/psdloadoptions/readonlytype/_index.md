---
title: "PsdLoadOptions.ReadOnlyType"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété PsdLoadOptions. Obtient ou définit le mode lecture seule utilisé lors du chargement d'une image PSD"
type: docs
weight: 80
url: /fr/net/aspose.psd.imageloadoptions/psdloadoptions/readonlytype/
---
{{< psd/tize >}}
## PsdLoadOptions.ReadOnlyType property

Obtient ou définit le mode lecture seule utilisé lors du chargement d'une image PSD.

```csharp
public ReadOnlyMode ReadOnlyType { get; set; }
```

### Property Value

Une des valeurs de [`ReadOnlyMode`](../readonlymode/) :

* !:ReadOnlyMode.None – No restrictions. Image content can be modified.
* !:ReadOnlyMode.Default – The image is fully read-only.
* !:ReadOnlyMode.MetadataEdit – Only metadata can be edited (such as [`ImageResources`](../../../aspose.psd.fileformats.psd/psdimage/imageresources/)), while image pixel content remains read-only.

## Exemples

Démontre la modification et l'enregistrement des métadonnées PSD en utilisant ReadOnlyMode.MetadataEdit.

```csharp
[C#]

string sourceFile = "psdnet2382.psd";
string outputFile = "output.psd";

string testMetadata = "Updated metadata text";

using (PsdImage psdImage = (PsdImage)Aspose.PSD.Image.Load(sourceFile,
    new PsdLoadOptions() { ReadOnlyType = ReadOnlyMode.MetadataEdit })) // Sets the of ReadOnlyMode to true
{
    AssertAreNotEqual(testMetadata, psdImage.XmpData.Meta.AdobeXmpToolkit);

    // Modifier les métadonnées en ReadOnlyMode
    psdImage.XmpData.Meta.AdobeXmpToolkit = testMetadata;

    // Enregistrer les métadonnées modifiées en ReadOnlyMode
    psdImage.Save(outputFile);
}

using (PsdImage psdImage = (PsdImage)Aspose.PSD.Image.Load(outputFile)) // Sets the of ReadOnlyMode to true
{
    AssertAreEqual(testMetadata, psdImage.XmpData.Meta.AdobeXmpToolkit);
}

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects should be equal, but they don't.");
    }
}

void AssertAreNotEqual(object obj1, object obj2)
{
    if (object.Equals(obj1, obj2))
    {
        throw new Exception("Objects should not be equal, but they are equal.");
    }
}
```

### Voir aussi

* enum [ReadOnlyMode](../../readonlymode/)
* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


