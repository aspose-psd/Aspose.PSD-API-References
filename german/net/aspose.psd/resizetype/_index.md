---
title: "Aufzählung ResizeType"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.ResizeType Aufzählung. Gibt den Skalierungstyp an."
type: docs
weight: 5870
url: /de/net/aspose.psd/resizetype/
---
{{< psd/tize >}}
## ResizeType enumeration

Gibt den Skalierungstyp an.

```csharp
public enum ResizeType
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | `0` | Die Pixel werden während der Skalierung nicht beibehalten. |
| LeftTopToLeftTop | `1` | Der linke obere Punkt des neuen Bildes stimmt mit dem linken oberen Punkt des Originalbildes überein. Ein Beschnitt erfolgt bei Bedarf. |
| RightTopToRightTop | `2` | Der rechte obere Punkt des neuen Bildes stimmt mit dem rechten oberen Punkt des Originalbildes überein. Ein Beschnitt erfolgt bei Bedarf. |
| RightBottomToRightBottom | `3` | Der rechte untere Punkt des neuen Bildes stimmt mit dem rechten unteren Punkt des Originalbildes überein. Ein Beschnitt erfolgt bei Bedarf. |
| LeftBottomToLeftBottom | `4` | Der linke untere Punkt des neuen Bildes stimmt mit dem linken unteren Punkt des Originalbildes überein. Ein Beschnitt erfolgt bei Bedarf. |
| CenterToCenter | `5` | Das Zentrum des neuen Bildes wird mit dem Zentrum des Originalbildes übereinstimmen. Ein Beschnitt wird bei Bedarf durchgeführt. |
| LanczosResample | `6` | Neu abtasten mit dem lanczos-Algorithmus mit a=3. |
| NearestNeighbourResample | `7` | Neu abtasten mit dem Nearest‑Neighbour‑Algorithmus. |
| AdaptiveResample | `8` | Neu abtasten mit einem adaptiven Algorithmus, basierend auf gewichteten und gemischten rationalen Funktionen sowie lanczos3-Interpolationsalgorithmen. |
| BilinearResample | `9` | Neu abtasten mit bilinearer Interpolation. Bildvorfilterung ist erlaubt, um das Rauschen vor dem Neusampling zu entfernen, wenn nötig. |
| HighQualityResample | `10` | Das hochqualitative Neusampling |
| CatmullRom | `11` | Die Catmull‑Rom‑Kubikinterpolationsmethode. |
| CubicConvolution | `12` | Die Cubic Convolution Interpolationsmethode |
| CubicBSpline | `13` | Die CubicBSpline Kubikinterpolationsmethode |
| Mitchell | `14` | Die Mitchell Kubikinterpolationsmethode |
| SinC | `15` | Die Sinc (Lanczos3) Kubikinterpolationsmethode |
| Bell | `16` | Die Bell‑Interpolationsmethode |

## Beispiele

Der folgende Code demonstriert, wie man ein Bild mit einem neuen SinC‑Resize‑Typ skaliert.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Laden Sie ein vorhandenes Bild in eine Instanz der Klasse PsdImage.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

Der folgende Code demonstriert, wie man ein Bild mit einem neuen Bell‑Resize‑Typ skaliert.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// Laden Sie ein vorhandenes Bild in eine Instanz der Klasse PsdImage.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

Der folgende Code demonstriert, wie man ein Bild mit einem neuen Mitchell‑Resize‑Typ skaliert.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// Laden Sie ein vorhandenes Bild in eine Instanz der Klasse PsdImage.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

Der folgende Code demonstriert, wie man ein Bild mit einem neuen CatmullRom‑Resize‑Typ skaliert.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// Laden Sie ein vorhandenes Bild in eine Instanz der Klasse PsdImage.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

Der folgende Code demonstriert, wie man ein Bild mit einem neuen CubicBSpline‑Resize‑Typ skaliert.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// Laden Sie ein vorhandenes Bild in eine Instanz der Klasse PsdImage.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

Der folgende Code demonstriert, wie man ein Bild mit einem neuen CubicConvolution‑Resize‑Typ skaliert.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// Laden Sie ein vorhandenes Bild in eine Instanz der Klasse PsdImage.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### Siehe auch

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


