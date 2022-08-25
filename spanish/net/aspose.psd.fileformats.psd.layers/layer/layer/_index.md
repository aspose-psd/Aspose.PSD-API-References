---
title: Layer
second_title: Referencia de API de Aspose.PSD para .NET
description: Inicializa una nueva instancia delLayeraspose.psd.fileformats.psd.layers/layer clase. Constructor para inicialización diferida.
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd.layers/layer/layer/
---
## Layer() {#constructor}

Inicializa una nueva instancia del[`Layer`](../../layer) clase. Constructor para inicialización diferida.

```csharp
public Layer()
```

### Ejemplos

El siguiente ejemplo demuestra cómo puede dibujar en una capa recién creada si se usa la versión de constructor simple en Aspose.PSD

```csharp
[C#]

string outputFilePath = "output.psd";

int width = 100;
int height = 100;
using (var image = new PsdImage(width, height))
{
    var layer = new Layer();
    layer.Bottom = height;
    layer.Right = width;
    image.AddLayer(layer);

    Graphics graphic = new Graphics(layer);
    graphic.Clear(Color.Yellow);

    // dibujar un rectángulo con la herramienta Pluma
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // dibuja otro rectángulo con Pincel Sólido en color Azul
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### Ver también

* class [Layer](../../layer)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers](../../layer)
* asamblea [Aspose.PSD](../../../)

---

## Layer(RasterImage, bool) {#constructor_1}

Inicializa una nueva instancia del[`Layer`](../../layer) clase.

```csharp
public Layer(RasterImage image, bool disposeImage = false)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| image | RasterImage | La imagen. |
| disposeImage | Boolean | si se establece en`verdadero` [eliminar imagen]. |

### Ejemplos

El siguiente código demuestra la capacidad de cargar archivos de imagen JPEG/PNG/etc en PsdImage sin carga directa.

```csharp
[C#]

string filePath = "PsdExample.psd";
string outputFilePath = "PsdResult.psd";
using (var image = new PsdImage(200, 200))
{
    using (var im = Image.Load(filePath))
    {
        Layer layer = null;
        try
        {
            layer = new Layer((RasterImage)im);
            image.AddLayer(layer);
        }
        catch (Exception)
        {
            if (layer != null)
            {
                layer.Dispose();
            }

            throw;
        }
    }

    image.Save(outputFilePath);
}
```

### Ver también

* class [RasterImage](../../../aspose.psd/rasterimage)
* class [Layer](../../layer)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers](../../layer)
* asamblea [Aspose.PSD](../../../)

---

## Layer(Stream) {#constructor_3}

Inicializa una nueva instancia del[`Layer`](../../layer) clase.

```csharp
public Layer(Stream stream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo de imágenes |

### Ejemplos

El siguiente ejemplo demuestra cómo puede agregar imágenes Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif como capas a PsdImage

```csharp
[C#]

string outputFilePath = "PsdResult.psd";

var filesList = new string[]
{
    "PsdExample.psd",
    "BmpExample.bmp",
    "GifExample.gif",
    "Jpeg2000Example.jpf",
    "JpegExample.jpg",
    "PngExample.png",
    "TiffExample.tif",
};

using (var image = new PsdImage(200, 200))
{
    foreach (var fileName in filesList)
    {
        string filePath = fileName;
        using (var stream = new FileStream(filePath, FileMode.Open))
        {
            Layer layer = null;
            try
            {
                layer = new Layer(stream);
                image.AddLayer(layer);
            }
            catch (Exception e)
            {
                if (layer != null)
                {
                    layer.Dispose();
                }

                throw e;
            }
        }
    }

    image.Save(outputFilePath);
}
```

### Ver también

* class [Layer](../../layer)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers](../../layer)
* asamblea [Aspose.PSD](../../../)

---

## Layer(Rectangle, byte[], byte[], byte[], string) {#constructor_2}

Inicializa una nueva instancia del[`Layer`](../../layer) clase de matrices de bytes.

```csharp
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, string name)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| bounds | Rectangle | Los límites de la capa. |
| redBytes | Byte[] | Los bytes rojos. |
| greenBytes | Byte[] | Los bytes verdes. |
| blueBytes | Byte[] | Los bytes azules. |
| name | String | El nombre de la capa. |

### Excepciones

| excepción | condición |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception) | Las matrices de bytes no pueden estar vacías o La longitud de las matrices de bytes debe ser igual a las dimensiones de los límites (límites.Ancho * límites.Altura) |

### Ver también

* struct [Rectangle](../../../aspose.psd/rectangle)
* class [Layer](../../layer)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers](../../layer)
* asamblea [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
