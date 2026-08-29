---
title: "RasterImage.LoadPixels"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método RasterImage. Carga píxeles"
type: docs
weight: 410
url: /es/net/aspose.psd/rasterimage/loadpixels/
---
{{< psd/tize >}}
## RasterImage.LoadPixels method

Carga píxeles.

```csharp
public Color[] LoadPixels(Rectangle rectangle)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectángulo | Rectangle | El rectángulo del cual cargar los píxeles. |

### Valor devuelto

La matriz de píxeles cargada.

## Ejemplos

Este ejemplo muestra cómo cargar información de píxeles en una matriz del tipo Color, manipular la matriz y volver a establecerla en la imagen. Para realizar estas operaciones, este ejemplo crea un nuevo archivo Image (en formato PSD) usando el objeto MemoryStream.

```csharp
[C#]

//Cree una instancia de MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Cree una instancia de PsdOptions y establezca sus diversas propiedades, incluida la propiedad Source
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Cree una instancia de Image
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Obtén los píxeles de la imagen especificando el área como límite de la imagen
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Recorre el Array y establece el color del píxel indexado alternativo
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Establece el color del píxel indexado a amarillo
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Establece el color del píxel indexado a azul
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Aplica los cambios de píxeles a la imagen
        image.SavePixels(image.Bounds, pixels);

        // Guarda todos los cambios.
        image.Save();
    }

    //Escribe MemoryStream a Archivo
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### Ver también

* struct [Color](../../color/)
* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


