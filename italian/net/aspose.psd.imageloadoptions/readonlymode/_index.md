---
title: "Enum ReadOnlyMode"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Enum Aspose.PSD.ImageLoadOptions.ReadOnlyMode. Specifica le modalità di sola lettura disponibili durante il caricamento di un'immagine PSD"
type: docs
weight: 5260
url: /it/net/aspose.psd.imageloadoptions/readonlymode/
---
{{< psd/tize >}}
## ReadOnlyMode enumeration

Specifica le modalità di sola lettura disponibili durante il caricamento di un'immagine PSD.

```csharp
public enum ReadOnlyMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | `0` | Non vengono applicate restrizioni di sola lettura. L'immagine può essere modificata completamente. |
| Default | `1` | Modalità predefinita. L'immagine è completamente di sola lettura e non può essere modificata. |
| MetadataEdit | `2` | Consente la modifica dei metadati dell'immagine mantenendo il contenuto dell'immagine in sola lettura. |

## Esempi

Dimostra la modifica e il salvataggio dei metadati PSD utilizzando ReadOnlyMode.MetadataEdit.

```csharp
[C#]

string sourceFile = "psdnet2382.psd";
string outputFile = "output.psd";

string testMetadata = "Updated metadata text";

using (PsdImage psdImage = (PsdImage)Aspose.PSD.Image.Load(sourceFile,
    new PsdLoadOptions() { ReadOnlyType = ReadOnlyMode.MetadataEdit })) // Sets the of ReadOnlyMode to true
{
    AssertAreNotEqual(testMetadata, psdImage.XmpData.Meta.AdobeXmpToolkit);

    // Modifica i metadati in ReadOnlyMode
    psdImage.XmpData.Meta.AdobeXmpToolkit = testMetadata;

    // Salva i metadati modificati in ReadOnlyMode
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

### Vedi anche

* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


