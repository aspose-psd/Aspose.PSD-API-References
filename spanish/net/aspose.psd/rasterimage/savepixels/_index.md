---
title: "RasterImage.SavePixels"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método RasterImage. Guarda los píxeles"
type: docs
weight: 540
url: /es/net/aspose.psd/rasterimage/savepixels/
---
{{< psd/tize >}}
## RasterImage.SavePixels method

Guarda los píxeles.

```csharp
public void SavePixels(Rectangle rectangle, Color[] pixels)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectángulo | Rectangle | El rectángulo donde guardar los píxeles. |
| píxeles | Color[] | El array de píxeles. |

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

* struct [Rectangle](../../rectangle/)
* struct [Color](../../color/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


