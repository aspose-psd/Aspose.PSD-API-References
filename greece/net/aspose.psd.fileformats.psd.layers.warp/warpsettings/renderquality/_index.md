---
title: "WarpSettings.RenderQuality"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "WarpSettings ιδιότητα. Λαμβάνει ή ορίζει την τιμή της ποιότητας απόδοσης παραμόρφωσης μεταξύ ταχύτητας και ποιότητας"
type: docs
weight: 50
url: /el/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/renderquality/
---
{{< psd/tize >}}
## WarpSettings.RenderQuality property

Λαμβάνει ή ορίζει την τιμή της ποιότητας απόδοσης παραμόρφωσης - μεταξύ ταχύτητας και ποιότητας

```csharp
public RenderQuality RenderQuality { get; set; }
```

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την ιδιότητα WarpSettings.RenderQuality για τη διαμόρφωση της παραμόρφωσης του warp.

```csharp
[C#]

string sourceFile = "Warping.psd";
List<string> outputFiles = new List<string>();

PsdLoadOptions loadOptions = new PsdLoadOptions() { LoadEffectsResource = true, AllowWarpRepaint = true };

RenderQuality[] qualityValues = { RenderQuality.Turbo, RenderQuality.Fast, RenderQuality.Normal, RenderQuality.Excellent };

for (int i = 0; i < 4; i++)
{
    using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
    {
        // Λαμβάνει το WarpSettings από το Smart Layer
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // Ορίζει το μέγεθος της περιοχής επεξεργασίας του warp
        warpSettings.RenderQuality = qualityValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + qualityValues[i].ToString() + ".png";
        outputFiles.Add(outputFile);

        // Δεν θα πρέπει να υπάρχει σφάλμα εδώ
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Δείτε επίσης

* enum [RenderQuality](../../renderquality/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


