---
title: Layer.Layer
second_title: Aspose.PSD per riferimento API .NET
description: Layer costruttore. Inizializza una nuova istanza diLayer classe. Costruttore per inizializzazione pigra.
type: docs
weight: 10
url: /it/net/aspose.psd.fileformats.psd.layers/layer/layer/
---
## Layer() {#constructor}

Inizializza una nuova istanza di[`Layer`](../) classe. Costruttore per inizializzazione pigra.

```csharp
public Layer()
```

### Esempi

L'esempio seguente mostra come disegnare su un livello appena creato se viene utilizzata la versione del costruttore semplice in Aspose.PSD

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

    // disegna un rettangolo con lo strumento Penna
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // disegna un altro rettangolo con Solid Brush in colore blu
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### Guarda anche

* class [Layer](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* assemblea [Aspose.PSD](../../../)

---

## Layer(RasterImage, bool) {#constructor_1}

Inizializza una nuova istanza di[`Layer`](../) classe.

```csharp
public Layer(RasterImage image, bool disposeImage = false)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | RasterImage | L'immagine. |
| disposeImage | Boolean | se impostato su`VERO` [disponi l'immagine]. |

### Esempi

Il codice seguente dimostra la possibilità di caricare file immagine JPEG/PNG/etc su PsdImage senza caricamento diretto.

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

### Guarda anche

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [Layer](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* assemblea [Aspose.PSD](../../../)

---

## Layer(Stream) {#constructor_3}

Inizializza una nuova istanza di[`Layer`](../) classe.

```csharp
public Layer(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso di immagini |

### Esempi

L'esempio seguente mostra come aggiungere immagini Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif come livelli a PsdImage

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

### Guarda anche

* class [Layer](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* assemblea [Aspose.PSD](../../../)

---

## Layer(Rectangle, byte[], byte[], byte[], string) {#constructor_2}

Inizializza una nuova istanza di[`Layer`](../) classe da array di byte.

```csharp
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, string name)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bounds | Rectangle | Il livello delimita. |
| redBytes | Byte[] | I byte rossi. |
| greenBytes | Byte[] | I byte verdi. |
| blueBytes | Byte[] | I byte blu. |
| name | String | Il nome del livello. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Gli array di byte non possono essere vuoti o La lunghezza degli array di byte deve essere uguale alle dimensioni dei limiti (bounds.Width * bounds.Height) |

### Guarda anche

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* assemblea [Aspose.PSD](../../../)


