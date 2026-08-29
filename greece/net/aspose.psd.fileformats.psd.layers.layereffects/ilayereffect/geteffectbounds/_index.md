---
title: "ILayerEffect.GetEffectBounds"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "ILayerEffect method. Υπολογίζει και λαμβάνει τα όρια των εικονοστοιχείων εφέ βάσει των ορίων των εικονοστοιχείων εισόδου της στρώσης"
type: docs
weight: 50
url: /el/net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/geteffectbounds/
---
{{< psd/tize >}}
## ILayerEffect.GetEffectBounds method

Υπολογίζει και λαμβάνει τα όρια των εικονοστοιχείων εφέ βάσει των ορίων των εικονοστοιχείων εισόδου της στρώσης.

```csharp
public Rectangle GetEffectBounds(Rectangle layerBounds, int globalAngle)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| layerBounds | Rectangle | Τα όρια των εικονοστοιχείων της στρώσης. |
| globalAngle | Int32 | Η παγκόσμια γωνία για τον υπολογισμό της παγκόσμιας γωνίας φωτός. |

### Τιμή Επιστροφής

Τα όρια των εικονοστοιχείων εφέ με βάση τα όρια των εικονοστοιχείων της εισαγόμενης στρώσης.

## Παραδείγματα

Δείχνει πώς να λάβετε τα όρια μιας στρώσης με εφέ και να τα εξάγετε με το σωστό μέγεθος.

```csharp
[C#]

string srcFile = "1958.psd";
string outputFile = "out_1958.png";

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    var layer1 = psdImage.Layers[1];

    var layerBoudns = layer1.Bounds;
    foreach (var effect in layer1.BlendingOptions.Effects)
    {
        layerBoudns = Rectangle.Union(
            layerBoudns,
            effect.GetEffectBounds(layer1.Bounds, psdImage.GlobalAngle));
    }

    Rectangle boundsToExport = Rectangle.Empty; // The default value is to save only the layer with effects.
                                                // boundsToExport = psdImage.Bounds; // Για αποθήκευση εντός των ορίων του PsdImage στην αρχική θέση της στρώσης

    layer1.Save(
        outputFile,
        new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha },
        boundsToExport);

    using (var imgStream = new FileStream(outputFile, FileMode.Open))
    {
        var loadedLayer = new Layer(imgStream);
        if (loadedLayer.Size == layerBoudns.Size)
        {
            System.Console.WriteLine("The size is calculated correctly.");
        }
    }
}
```

### Δείτε επίσης

* struct [Rectangle](../../../aspose.psd/rectangle/)
* interface [ILayerEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


