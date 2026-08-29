---
title: "Énumération ReadOnlyMode"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Énumération Aspose.PSD.ImageLoadOptions.ReadOnlyMode. Spécifie les modes lecture seule disponibles lors du chargement d'une image PSD"
type: docs
weight: 5260
url: /fr/net/aspose.psd.imageloadoptions/readonlymode/
---
{{< psd/tize >}}
## ReadOnlyMode enumeration

Spécifie les modes en lecture seule disponibles lors du chargement d'une image PSD.

```csharp
public enum ReadOnlyMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | `0` | Aucune restriction en lecture seule n'est appliquée. L'image peut être entièrement modifiée. |
| Default | `1` | Mode par défaut. L'image est entièrement en lecture seule et ne peut pas être modifiée. |
| MetadataEdit | `2` | Autorise la modification des métadonnées de l'image tout en maintenant le contenu de l'image en lecture seule. |

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

* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


