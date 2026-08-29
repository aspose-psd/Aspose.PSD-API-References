---
title: "Enumeración ColorSpace"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Aspose.PSD.FileFormats.Psd.Resources.Enums.ColorSpace enum. Los tipos de espacio de color"
type: docs
weight: 4160
url: /es/net/aspose.psd.fileformats.psd.resources.enums/colorspace/
---
{{< psd/tize >}}
## ColorSpace enumeration

Los tipos de espacio de color.

```csharp
public enum ColorSpace : ushort
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| RGB | `0` | El espacio de color RGB. |
| HSB | `1` | El espacio de color HSB. |
| CMYK | `2` | El espacio de color CMYK. |
| Lab | `7` | El espacio de color Lab. |
| GrayScale | `8` | El espacio de color en escala de grises. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Resources.Enums](../../aspose.psd.fileformats.psd.resources.enums/)
* assembly [Aspose.PSD](../../)


