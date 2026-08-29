---
title: "Enum ReadOnlyMode"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Aspose.PSD.ImageLoadOptions.ReadOnlyMode enum. Especifica los modos de solo lectura disponibles al cargar una imagen PSD."
type: docs
weight: 5260
url: /es/net/aspose.psd.imageloadoptions/readonlymode/
---
{{< psd/tize >}}
## ReadOnlyMode enumeration

Especifica los modos de solo lectura disponibles al cargar una imagen PSD.

```csharp
public enum ReadOnlyMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | `0` | No se aplican restricciones de solo lectura. La imagen puede modificarse completamente. |
| Default | `1` | Modo predeterminado. La imagen es totalmente de solo lectura y no puede modificarse. |
| MetadataEdit | `2` | Permite editar los metadatos de la imagen mientras mantiene el contenido de la imagen de solo lectura. |

## Ejemplos

Demuestra la edición y guardado de metadatos PSD usando ReadOnlyMode.MetadataEdit.

```csharp
[C#]

string sourceFile = "psdnet2382.psd";
string outputFile = "output.psd";

string testMetadata = "Updated metadata text";

using (PsdImage psdImage = (PsdImage)Aspose.PSD.Image.Load(sourceFile,
    new PsdLoadOptions() { ReadOnlyType = ReadOnlyMode.MetadataEdit })) // Sets the of ReadOnlyMode to true
{
    AssertAreNotEqual(testMetadata, psdImage.XmpData.Meta.AdobeXmpToolkit);

    // Cambiar metadatos en ReadOnlyMode
    psdImage.XmpData.Meta.AdobeXmpToolkit = testMetadata;

    // Guardar metadatos modificados en ReadOnlyMode
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

### Ver también

* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


