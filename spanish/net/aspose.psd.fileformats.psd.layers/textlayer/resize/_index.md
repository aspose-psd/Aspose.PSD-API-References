---
title: TextLayer.Resize
second_title: Referencia de API de Aspose.PSD para .NET
description: TextLayer método. Cambia el tamaño de la imagen. El valor por defectoLeftTopToLeftTopse usa.
type: docs
weight: 90
url: /es/net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
## TextLayer.Resize method

Cambia el tamaño de la imagen. El valor por defectoLeftTopToLeftTopse usa.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| newWidth | Int32 | El nuevo ancho. |
| newHeight | Int32 | La nueva altura. |
| resizeType | ResizeType | El tipo de transformación de cambio de tamaño[`ResizeType`](../../../aspose.psd/resizetype/) |

### Ejemplos

El código siguiente muestra la función TextLayer.Resize con el parámetro para elegir el mecanismo de cambio de tamaño.

```csharp
[C#]

string sourceFileName = "TextLayer.psd";
string outputFile = "TextLayerResized_output.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    TextLayer textLayer = (TextLayer)image.Layers[1];

    // Establece el nuevo tamaño de la capa de texto
    const int NewWidth = 250;
    const int NewHeight = 250;

    // Establece el mecanismo de cómo la función de cambio de tamaño cambiará el tamaño de la capa (valor predeterminado)
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // Nuevo mecanismo de cambio de tamaño para la capa de texto usando aquí
    // No solo se cambiará la capa sino también la matriz de transformación de la capa de texto
    textLayer.Resize(NewWidth, NewHeight, resizeType);

    image.Save(outputFile, new PsdOptions(image));
}

using (PsdImage image = (PsdImage)Image.Load(outputFile, new PsdLoadOptions()))
{
    TextLayer txtLayer = (TextLayer)image.Layers[1];

    // El motivo del delta es una fuente predeterminada diferente
    if (txtLayer.TransformMatrix[4] >= 65 
        && txtLayer.TransformMatrix[4] <= 67
        && txtLayer.TransformMatrix[5] >= 234
        && txtLayer.TransformMatrix[5] <= 237)
    {
        // Todo está bien
    }
    else
    {
        throw new Exception("Location point is wrong");
    }
}
```

### Ver también

* enum [ResizeType](../../../aspose.psd/resizetype/)
* class [TextLayer](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* asamblea [Aspose.PSD](../../../)


