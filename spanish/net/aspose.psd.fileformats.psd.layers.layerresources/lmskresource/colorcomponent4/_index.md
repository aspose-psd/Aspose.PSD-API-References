---
title: "LmskResource.ColorComponent4"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "LmskResource propiedad. Obtiene el componente de color 4"
type: docs
weight: 50
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent4/
---
{{< psd/tize >}}
## LmskResource.ColorComponent4 property

Obtiene el componente de color 4.

```csharp
public ushort ColorComponent4 { get; set; }
```

### Property Value

El componente de color 4.

## Ejemplos

El siguiente código demuestra cómo cambiar las opciones de visualización de la máscara de capa en imágenes de 16 bits mediante la modificación de las propiedades de LmskResource.

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

// Cargar imagen de 16 bits.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    // Buscar LmskResource.
    LmskResource lmskResource = new LmskResource();
    foreach (var res in image.GlobalLayerResources)
    {
        if (res is LmskResource)
        {
            lmskResource = (LmskResource)res;
            break;
        }
    }

    // Comprobar propiedades de LmskResource.
    AssertAreEqual(lmskResource.ColorSpace, ColorSpace.RGB);
    AssertAreEqual(lmskResource.ColorComponent1, (ushort)65535);
    AssertAreEqual(lmskResource.ColorComponent2, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent3, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent4, (ushort)0);
    AssertAreEqual(lmskResource.Opacity, (short)45);
    AssertAreEqual(lmskResource.Flag, (byte)128);

    // Cambiar propiedades de LmskResource.
    lmskResource.ColorSpace = ColorSpace.HSB;
    lmskResource.ColorComponent1 = 7854;
    lmskResource.ColorComponent2 = 10;
    lmskResource.ColorComponent3 = 15484;
    lmskResource.Opacity = 85;

    // Guardar la imagen.
    image.Save(outputPsd);
}
```

### Ver también

* class [LmskResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


