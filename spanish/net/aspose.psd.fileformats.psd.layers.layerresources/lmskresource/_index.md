---
title: "Clase LmskResource"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LmskResource. El recurso LMsk"
type: docs
weight: 3020
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---
{{< psd/tize >}}
## LmskResource class

El recurso LMsk.

```csharp
public class LmskResource : LayerResource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LmskResource](lmskresource/)() | Inicializa una nueva instancia de la clase `LmskResource`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ColorComponent1](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent1/) { get; set; } | Obtiene el componente de color 1. |
| [ColorComponent2](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent2/) { get; set; } | Obtiene el componente de color 2. |
| [ColorComponent3](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent3/) { get; set; } | Obtiene el componente de color 3. |
| [ColorComponent4](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent4/) { get; set; } | Obtiene el componente de color 4. |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorspace/) { get; set; } | Obtiene el espacio de color. |
| [Flag](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/flag/) { get; } | Obtiene la bandera. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtiene la clave del recurso de capa. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/length/) { get; } | Obtiene la longitud del recurso de capa en bytes. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/opacity/) { get; set; } | Obtiene la opacidad. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtiene la firma. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/save/)(StreamContainer, int) | Guarda el recurso en el contenedor de flujo especificado. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Devuelve una String que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/typetoolkey/) | La clave de información de la herramienta de tipo. |

## Observaciones

Este recurso contiene el ID del espacio de color, que se refiere a un tipo específico de espacio de color, y 4 componentes de color. Dependiendo del ID, los componentes de color tienen diferentes significados. Si el tipo de espacio de color no requiere cuatro valores, los componentes adicionales son indefinidos y siempre se escriben como ceros. Componentes de color por tipo de espacio de color: RGB - los tres primeros componentes son rojo, verde y azul. HSB - los tres primeros componentes son tono, saturación y brillo. CMYK - los cuatro componentes son cian, magenta, amarillo y negro. Lab - los tres primeros componentes son luminosidad, crominancia a y crominancia b. Grayscale - el primer componente es el valor gris, de 0...10000.

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


