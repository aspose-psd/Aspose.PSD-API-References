---
title: "StreamSource.StreamSource"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Constructor StreamSource. Inicializa una nueva instancia de la clase StreamSource"
type: docs
weight: 10
url: /es/net/aspose.psd.sources/streamsource/streamsource/
---
{{< psd/tize >}}
## StreamSource(Stream) {#constructor}

Inicializa una nueva instancia de la clase [`StreamSource`](../).

```csharp
public StreamSource(Stream stream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo a abrir. |

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

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

Inicializa una nueva instancia de la clase [`StreamSource`](../).

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo a abrir. |
| disposeStream | Boolean | si se establece en `true`, el flujo será descartado. |

## Ejemplos

Este ejemplo demuestra el uso de System.IO.Stream para crear un nuevo archivo Image.

```csharp
[C#]

//Crea una instancia de PsdOptions y establece sus diversas propiedades.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Crea una instancia de System.IO.Stream.
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Define la propiedad source para la instancia de PsdOptions.
//El segundo parámetro booleano determina si el Stream se elimina una vez que sale del alcance.
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Crea una instancia de Image y llama al método Create con PsdOptions como parámetro para inicializar el objeto Image.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //realiza algún procesamiento de imagen
}
```

### Ver también

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)


