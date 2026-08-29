---
title: "Layer.Layer"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Layer कंस्ट्रक्टर। Layer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। लेज़ी इनिशियलाइज़ेशन के लिए कंस्ट्रक्टर"
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers/layer/layer/
---
{{< psd/tize >}}
## Layer() {#constructor}

[`Layer`](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। लेज़ी इनिशियलाइज़ेशन के लिए कंस्ट्रक्टर।

```csharp
public Layer()
```

## उदाहरण

निम्न उदाहरण दर्शाता है कि आप Aspose.PSD में सरल कंस्ट्रक्टर संस्करण का उपयोग करने पर नए बनाए गए लेयर पर कैसे ड्रॉ कर सकते हैं

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

    // Pen टूल से एक आयत बनाएं
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // नीले रंग में Solid Brush से एक और आयत बनाएं
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### देखें भी

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(RasterImage, bool) {#constructor_1}

[`Layer`](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Layer(RasterImage image, bool disposeImage = false)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| छवि | RasterImage | छवि। |
| disposeImage | बूलियन | यदि `true` पर सेट किया गया हो तो [dispose image]. |

## उदाहरण

निम्नलिखित कोड JPEG/PNG/इत्यादि इमेज फ़ाइलों को सीधे लोड किए बिना PsdImage में लोड करने की क्षमता दर्शाता है।

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

### देखें भी

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(Stream) {#constructor_3}

[`Layer`](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Layer(Stream stream)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | छवि स्ट्रीम |

## उदाहरण

निम्न उदाहरण दर्शाता है कि आप Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif छवियों को PsdImage में लेयर्स के रूप में कैसे जोड़ सकते हैं

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

### देखें भी

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(Rectangle, byte[], byte[], byte[], string) {#constructor_2}

बाइट एरेज़ से [`Layer`](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, string name)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| सीमाएँ | Rectangle | लेयर की सीमाएँ। |
| redBytes | Byte[] | लाल बाइट्स। |
| greenBytes | Byte[] | हरी बाइट्स। |
| blueBytes | Byte[] | नीली बाइट्स। |
| नाम | String | लेयर नाम। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | बाइट एरेज़ खाली नहीं हो सकते या बाइट एरेज़ की लंबाई को सीमाओं के आयामों (bounds.Width * bounds.Height) के बराबर होना चाहिए। |

### देखें भी

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


