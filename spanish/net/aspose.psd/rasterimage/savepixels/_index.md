---
title: RasterImage.SavePixels
second_title: Referencia de API de Aspose.PSD para .NET
description: RasterImage método. Guarda los píxeles.
type: docs
weight: 520
url: /es/net/aspose.psd/rasterimage/savepixels/
---
## RasterImage.SavePixels method

Guarda los píxeles.

```csharp
public void SavePixels(Rectangle rectangle, Color[] pixels)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rectangle | Rectangle | El rectángulo en el que se guardarán los píxeles. |
| pixels | Color[] | La matriz de píxeles. |

### Ejemplos

Este ejemplo muestra cómo cargar información de píxeles en una matriz de color de tipo, manipular la matriz y volver a establecerla en la imagen. Para realizar estas operaciones, este ejemplo crea un nuevo archivo de imagen (en formato PSD) utilizando el objeto MemoryStream.

```csharp
[C#]

//Crear una instancia de MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Cree una instancia de PsdOptions y establezca sus diversas propiedades, incluida la propiedad Fuente
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Crear una instancia de Imagen
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Obtenga los píxeles de la imagen especificando el área como límite de la imagen
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Recorre la matriz y establece el color del píxel indexado alternativo
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Establecer el color del píxel indexado en amarillo
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Establecer el color del píxel indexado en azul
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Aplicar los cambios de píxel a la imagen
        image.SavePixels(image.Bounds, pixels);

        // guarda todos los cambios.
        image.Save();
    }

    //Escribir flujo de memoria en archivo
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### Ver también

* struct [Rectangle](../../rectangle/)
* struct [Color](../../color/)
* class [RasterImage](../)
* espacio de nombres [Aspose.PSD](../../rasterimage/)
* asamblea [Aspose.PSD](../../../)


