---
title: Class AiLayerSection
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Ai.AiLayerSection klas. Der Ebenenabschnitt im AiFormat
type: docs
weight: 1270
url: /de/net/aspose.psd.fileformats.ai/ailayersection/
---
## AiLayerSection class

Der Ebenenabschnitt im Ai-Format

```csharp
public sealed class AiLayerSection : AiDataSection
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Blue](../../aspose.psd.fileformats.ai/ailayersection/blue/) { get; set; } | Ruft die blaue Farbkomponente ab oder legt sie fest. |
| [ColorNumber](../../aspose.psd.fileformats.ai/ailayersection/colornumber/) { get; set; } | Holt oder setzt die Farbnummer. -1 ist der benutzerdefinierte Farbwert aus den Eigenschaften Rot, Grün, Blau. Gibt die Farbeinstellung der Ebene an. |
| [DimValue](../../aspose.psd.fileformats.ai/ailayersection/dimvalue/) { get; set; } | Ruft den Dim-Wert als Prozentsatz ab oder setzt ihn. Reduziert die Intensität von verknüpften Bildern und Bitmap-Bildern, die in der Ebene enthalten sind, auf den angegebenen Prozentsatz. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| [Green](../../aspose.psd.fileformats.ai/ailayersection/green/) { get; set; } | Ruft die grüne Farbkomponente ab oder legt sie fest. |
| [IsImagesDimmed](../../aspose.psd.fileformats.ai/ailayersection/isimagesdimmed/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob diese Ebene abgeblendet ist. Verringert die Intensität von verknüpften Bildern und Bitmap-Bildern, die in der Ebene enthalten sind. |
| [IsLocked](../../aspose.psd.fileformats.ai/ailayersection/islocked/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob diese Ebene gesperrt ist. Verhindert Änderungen am Element. |
| [IsPreview](../../aspose.psd.fileformats.ai/ailayersection/ispreview/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob es sich bei dieser Ebene um eine Vorschau handelt. Zeigt die in der Ebene enthaltenen Grafiken in Farbe statt als Umrisse an. |
| [IsPrinted](../../aspose.psd.fileformats.ai/ailayersection/isprinted/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob diese Ebene gedruckt wird. Macht das in der Ebene enthaltene Bildmaterial druckbar, wenn wahr. |
| [IsShown](../../aspose.psd.fileformats.ai/ailayersection/isshown/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob diese Ebene angezeigt wird. Zeigt alle in der Ebene enthaltenen Grafiken auf der Zeichenfläche an, falls wahr. |
| [IsTemplate](../../aspose.psd.fileformats.ai/ailayersection/istemplate/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob diese Ebene eine Vorlagenebene ist. |
| [Name](../../aspose.psd.fileformats.ai/ailayersection/name/) { get; set; } | Ruft den Ebenennamen ab oder legt ihn fest. Gibt den Namen des Elements an, wie er im Ebenenbedienfeld angezeigt wird. |
| [RasterImages](../../aspose.psd.fileformats.ai/ailayersection/rasterimages/) { get; } | Ruft die Rasterbilder ab. |
| [Red](../../aspose.psd.fileformats.ai/ailayersection/red/) { get; set; } | Ruft die rote Farbkomponente ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddRasterImage](../../aspose.psd.fileformats.ai/ailayersection/addrasterimage/)(AiRasterImageSection) | Fügt das Rasterbild hinzu. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwirft die aktuelle Instanz. |
| [GetData](../../aspose.psd.fileformats.ai/aidatasection/getdata/)() | Ruft die String-Daten ab. |

### Beispiele

Der folgende Code zeigt, wie Einstellungen von Rasterbildern in AI-Formatdateien geladen werden.

```csharp
[C#]

const double DefaultTolerance = 1e-6;

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}

string sourceFile = "sample.ai";
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    AiLayerSection layer = image.Layers[0];

    AssertIsTrue(layer.RasterImages != null, "RasterImages property should be not null");
    AssertIsTrue(layer.RasterImages.Length == 1, "RasterImages property should contain exactly one item");

    AiRasterImageSection rasterImage = layer.RasterImages[0];
    AssertIsTrue(rasterImage.Pixels != null, "rasterImage.Pixels property should be not null");
    AssertIsTrue(rasterImage.Pixels.Length == 100, "rasterImage.Pixels property should contain exactly 100 items");
    AssertIsTrue((uint)rasterImage.Pixels[99] == 0xFFB21616, "rasterImage.Pixels[99] should be 0xFFB21616");
    AssertIsTrue((uint)rasterImage.Pixels[19] == 0xFF00FF00, "rasterImage.Pixels[19] should be 0xFF00FF00");
    AssertIsTrue((uint)rasterImage.Pixels[10] == 0xFF01FD00, "rasterImage.Pixels[10] should be 0xFF01FD00");
    AssertIsTrue((uint)rasterImage.Pixels[0] == 0xFF0000FF, "rasterImage.Pixels[0] should be 0xFF0000FF");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Width) < DefaultTolerance, "rasterImage.Width should be 0.99987");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Height) < DefaultTolerance, "rasterImage.Height should be 0.99987");
    AssertIsTrue(Math.Abs(387 - rasterImage.OffsetX) < DefaultTolerance, "rasterImage.OffsetX should be 387");
    AssertIsTrue(Math.Abs(379 - rasterImage.OffsetY) < DefaultTolerance, "rasterImage.OffsetY should be 379");
    AssertIsTrue(Math.Abs(0 - rasterImage.Angle) < DefaultTolerance, "rasterImage.Angle should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.LeftBottomShift) < DefaultTolerance, "rasterImage.LeftBottomShift should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.X) < DefaultTolerance, "rasterImage.ImageRectangle.X should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.Y) < DefaultTolerance, "rasterImage.ImageRectangle.Y should be 0");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Width) < DefaultTolerance, "rasterImage.ImageRectangle.Width should be 10");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Height) < DefaultTolerance, "rasterImage.ImageRectangle.Height should be 10");
}
```

### Siehe auch

* class [AiDataSection](../aidatasection/)
* namensraum [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* Montage [Aspose.PSD](../../)


