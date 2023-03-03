---
title: Layer.Layer
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Layer नर्मत. क एक नय उदहरण प्ररंभ करत हैLayer कक्ष आलस आरंभकरण के लए नर्मत
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers/layer/layer/
---
## Layer() {#constructor}

का एक नया उदाहरण प्रारंभ करता है[`Layer`](../) कक्षा। आलसी आरंभीकरण के लिए निर्माता।

```csharp
public Layer()
```

### उदाहरण

निम्न उदाहरण प्रदर्शित करता है कि यदि Aspose.PSD में सरल कन्स्ट्रक्टर संस्करण का उपयोग किया जाता है तो आप नई बनाई गई परत पर कैसे आकर्षित कर सकते हैं

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

    // पेन टूल के साथ एक आयत बनाएं
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // सॉलिड ब्रश के साथ नीले रंग में एक और आयत बनाएं
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### यह सभी देखें

* class [Layer](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* सभा [Aspose.PSD](../../../)

---

## Layer(RasterImage, bool) {#constructor_1}

का एक नया उदाहरण प्रारंभ करता है[`Layer`](../) वर्ग.

```csharp
public Layer(RasterImage image, bool disposeImage = false)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | RasterImage | छवि। |
| disposeImage | Boolean | अगर सेट है`सत्य` [निपटान छवि]। |

### उदाहरण

निम्न कोड जेपीईजी/पीएनजी/आदि छवि फ़ाइलों को सीधे लोड किए बिना PsdImage में लोड करने की क्षमता प्रदर्शित करता है।

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

### यह सभी देखें

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [Layer](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* सभा [Aspose.PSD](../../../)

---

## Layer(Stream) {#constructor_3}

का एक नया उदाहरण प्रारंभ करता है[`Layer`](../) वर्ग.

```csharp
public Layer(Stream stream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | छवि धारा |

### उदाहरण

निम्न उदाहरण दर्शाता है कि कैसे आप Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif छवियों को PsdImage में परतों के रूप में जोड़ सकते हैं

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

### यह सभी देखें

* class [Layer](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* सभा [Aspose.PSD](../../../)

---

## Layer(Rectangle, byte[], byte[], byte[], string) {#constructor_2}

का एक नया उदाहरण प्रारंभ करता है[`Layer`](../) बाइट सरणियों से वर्ग.

```csharp
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, string name)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bounds | Rectangle | परत सीमा। |
| redBytes | Byte[] | लाल बाइट्स। |
| greenBytes | Byte[] | हरी बाइट्स। |
| blueBytes | Byte[] | ब्लू बाइट्स। |
| name | String | परत का नाम। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | बाइट सरणियाँ खाली नहीं हो सकतीं or बाइट सरणियों की लंबाई सीमा आयामों के बराबर होनी चाहिए (सीमा। चौड़ाई * सीमा। ऊँचाई) |

### यह सभी देखें

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* सभा [Aspose.PSD](../../../)


