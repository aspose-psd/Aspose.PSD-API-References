---
title: ResizeType
second_title: Aspose.PSD für .NET-API-Referenz
description: Gibt den Größenänderungstyp an.
type: docs
weight: 5300
url: /de/net/aspose.psd/resizetype/
---
## ResizeType enumeration

Gibt den Größenänderungstyp an.

```csharp
public enum ResizeType
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | `0` | Die Pixel werden während der Größenänderung nicht beibehalten. |
| LeftTopToLeftTop | `1` | Der linke obere Punkt des neuen Bildes stimmt mit dem linken oberen Punkt des Originalbildes überein. Zuschneiden erfolgt bei Bedarf. |
| RightTopToRightTop | `2` | Der rechte obere Punkt des neuen Bildes fällt mit dem rechten oberen Punkt des Originalbildes zusammen. Zuschneiden erfolgt bei Bedarf. |
| RightBottomToRightBottom | `3` | Der rechte untere Punkt des neuen Bildes stimmt mit dem rechten unteren Punkt des Originalbildes überein. Zuschneiden erfolgt bei Bedarf. |
| LeftBottomToLeftBottom | `4` | Der linke untere Punkt des neuen Bildes stimmt mit dem linken unteren Punkt des Originalbildes überein. Zuschneiden erfolgt bei Bedarf. |
| CenterToCenter | `5` | Der Mittelpunkt des neuen Bildes fällt mit dem Mittelpunkt des Originalbildes zusammen. Zuschneiden erfolgt bei Bedarf. |
| LanczosResample | `6` | Resampling mit Lanczos-Algorithmus mit a=3. |
| NearestNeighbourResample | `7` | Resampling mit Nächster-Nachbar-Algorithmus. |
| AdaptiveResample | `8` | Resampling mit adaptivem Algorithmus basierend auf gewichteten und gemischten rationalen Funktionen und Lanczos3-Interpolationsalgorithmen. |
| BilinearResample | `9` | Resampling mit bilinearer Interpolation. Die Bildvorfilterung ist erlaubt, um das Rauschen vor dem Resampling zu entfernen, falls erforderlich |
| HighQualityResample | `10` | Das hochwertige Resample |
| CatmullRom | `11` | Die kubische Interpolationsmethode von Catmull-Rom. |
| CubicConvolution | `12` | Die Interpolationsmethode der kubischen Faltung |
| CubicBSpline | `13` | Die kubische Interpolationsmethode CubicBSpline |
| Mitchell | `14` | Die kubische Interpolationsmethode von Mitchell |
| SinC | `15` | Die Sinc (Lanczos3) kubische Interpolationsmethode |
| Bell | `16` | Die Bell-Interpolationsmethode |

### Beispiele

Der folgende Code zeigt, wie Sie die Größe eines Bildes mit einem neuen SinC-Größenänderungstyp ändern.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Ein vorhandenes Bild in eine Instanz der PsdImage-Klasse laden
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

Der folgende Code zeigt, wie Sie die Größe eines Bilds mit einem neuen Bell-Größenänderungstyp ändern.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// Ein vorhandenes Bild in eine Instanz der PsdImage-Klasse laden
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

Der folgende Code zeigt, wie Sie die Größe eines Bilds mit einem neuen Mitchell-Größenänderungstyp ändern.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// Ein vorhandenes Bild in eine Instanz der PsdImage-Klasse laden
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

Der folgende Code zeigt, wie die Größe eines Bildes mit einem neuen CatmullRom-Größenänderungstyp geändert wird.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// Ein vorhandenes Bild in eine Instanz der PsdImage-Klasse laden
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

Der folgende Code zeigt, wie Sie die Größe eines Bilds mit einem neuen CubicBSpline-Größenänderungstyp ändern.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// Ein vorhandenes Bild in eine Instanz der PsdImage-Klasse laden
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

Der folgende Code zeigt, wie Sie die Größe eines Bilds mit einem neuen CubicConvolution-Größenänderungstyp ändern.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// Ein vorhandenes Bild in eine Instanz der PsdImage-Klasse laden
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### Siehe auch

* namensraum [Aspose.PSD](../../aspose.psd)
* Montage [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
