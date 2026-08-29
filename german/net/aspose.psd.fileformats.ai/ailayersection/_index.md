---
title: "Klasse AiLayerSection"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Ai.AiLayerSection Klasse. Der Ai format Layer Section"
type: docs
weight: 1280
url: /de/net/aspose.psd.fileformats.ai/ailayersection/
---
{{< psd/tize >}}
## AiLayerSection class

Der Ai-Format-Ebenenabschnitt

```csharp
public sealed class AiLayerSection : AiDataSection
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Blue](../../aspose.psd.fileformats.ai/ailayersection/blue/) { get; set; } | Liest oder setzt die blaue Farbkomponente. |
| [ColorIndex](../../aspose.psd.fileformats.ai/ailayersection/colorindex/) { get; set; } | Liest oder setzt den Index der Farbe. Dieses Argument kann Werte zwischen –1 und 26 annehmen. Jeder Integer stellt eine Farbe dar, die der Ebene zur Benutzeridentifikation zugewiesen werden kann. |
| [ColorNumber](../../aspose.psd.fileformats.ai/ailayersection/colornumber/) { get; set; } | Liest oder setzt die Farbnummer. -1 ist der benutzerdefinierte Farbwert aus den Eigenschaften Rot, Grün, Blau. Gibt die Farbeinstellung der Ebene an. |
| [DimValue](../../aspose.psd.fileformats.ai/ailayersection/dimvalue/) { get; set; } | Liest oder setzt den Dimmwert als Prozentsatz. Reduziert die Intensität verknüpfter Bilder und Bitmap‑Bilder, die in der Ebene enthalten sind, auf den angegebenen Prozentsatz. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Liest einen Wert, der angibt, ob diese Instanz freigegeben wurde. |
| [Green](../../aspose.psd.fileformats.ai/ailayersection/green/) { get; set; } | Liest oder setzt die grüne Farbkomponente. |
| [HasMultiLayerMasks](../../aspose.psd.fileformats.ai/ailayersection/hasmultilayermasks/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob diese Instanz Mehrschichtmasken hat. |
| [IsImagesDimmed](../../aspose.psd.fileformats.ai/ailayersection/isimagesdimmed/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob diese Ebene abgedunkelt ist. Reduziert die Intensität von verknüpften Bildern und Bitmap‑Bildern, die in der Ebene enthalten sind. |
| [IsLocked](../../aspose.psd.fileformats.ai/ailayersection/islocked/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob diese Ebene gesperrt ist. Verhindert Änderungen am Element. |
| [IsPreview](../../aspose.psd.fileformats.ai/ailayersection/ispreview/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob diese Ebene eine Vorschau ist. Zeigt die in der Ebene enthaltenen Grafiken in Farbe anstelle von Konturen. |
| [IsPrinted](../../aspose.psd.fileformats.ai/ailayersection/isprinted/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob diese Ebene gedruckt wird. Macht die in der Ebene enthaltenen Grafiken druckbar, wenn wahr. |
| [IsShown](../../aspose.psd.fileformats.ai/ailayersection/isshown/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob diese Ebene angezeigt wird. Zeigt alle in der Ebene enthaltenen Grafiken auf dem Zeichenbrett an, wenn wahr. |
| [IsTemplate](../../aspose.psd.fileformats.ai/ailayersection/istemplate/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob diese Ebene eine Vorlagenebene ist. |
| [Name](../../aspose.psd.fileformats.ai/ailayersection/name/) { get; set; } | Liest oder setzt den Ebenennamen. Gibt den Namen des Elements an, wie er im Ebenen‑Panel erscheint. |
| [RasterImages](../../aspose.psd.fileformats.ai/ailayersection/rasterimages/) { get; } | Liest die Rasterbilder. |
| [Red](../../aspose.psd.fileformats.ai/ailayersection/red/) { get; set; } | Liest oder setzt die rote Farbkomponente. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddRasterImage](../../aspose.psd.fileformats.ai/ailayersection/addrasterimage/)(AiRasterImageSection) | Fügt das Rasterbild hinzu. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Gibt die aktuelle Instanz frei. |
| [GetData](../../aspose.psd.fileformats.ai/aidatasection/getdata/)() | Gibt die Zeichenkettendaten zurück. |

## Beispiele

Der folgende Code demonstriert, wie Einstellungen von Rasterbildern in AI‑Formatdateien geladen werden.

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
* namespace [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../)


