---
title: Class Region
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.Region klass. Beskriver det inre av en grafisk form som består av rektanglar och banor. Denna klass kan inte ärvas.
type: docs
weight: 5360
url: /sv/net/aspose.psd/region/
---
## Region class

Beskriver det inre av en grafisk form som består av rektanglar och banor. Denna klass kan inte ärvas.

```csharp
public sealed class Region
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Region](region/#constructor)() | Initierar en ny`Region` . |
| [Region](region/#constructor_1)(GraphicsPath) | Initierar en ny`Region` med det angivna[`GraphicsPath`](../graphicspath/) . |
| [Region](region/#constructor_2)(Rectangle) | Initierar en ny`Region` från det angivna[`Rectangle`](../rectangle/)struktur. |
| [Region](region/#constructor_3)(RectangleF) | Initierar en ny`Region` från det angivna[`RectangleF`](../rectanglef/)struktur. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Complement](../../aspose.psd/region/complement/#complement)(GraphicsPath) | Uppdaterar detta`Region` att innehålla den del av det angivna[`GraphicsPath`](../graphicspath/) som inte korsar detta`Region` . |
| [Complement](../../aspose.psd/region/complement/#complement_1)(Rectangle) | Uppdaterar detta`Region` att innehålla den del av det angivna[`Rectangle`](../rectangle/) struktur som inte korsar detta`Region` . |
| [Complement](../../aspose.psd/region/complement/#complement_2)(RectangleF) | Uppdaterar detta`Region` att innehålla den del av det angivna[`RectangleF`](../rectanglef/) struktur som inte korsar detta`Region` . |
| [Complement](../../aspose.psd/region/complement/#complement_3)(Region) | Uppdaterar detta`Region` att innehålla den del av det angivna`Region` som inte korsar detta`Region` . |
| [DeepClone](../../aspose.psd/region/deepclone/)() | Skapar en exakt djup kopia av detta`Region` . |
| [Equals](../../aspose.psd/region/equals/#equals)(Region, Graphics) | Testar om den angivna`Region` är identisk med detta`Region` på den angivna ritytan. |
| [Exclude](../../aspose.psd/region/exclude/#exclude)(GraphicsPath) | Uppdaterar detta`Region` att endast innehålla den del av dess inre som inte korsar det specificerade[`GraphicsPath`](../graphicspath/) . |
| [Exclude](../../aspose.psd/region/exclude/#exclude_1)(Rectangle) | Uppdaterar detta`Region` att endast innehålla den del av dess inre som inte korsar det specificerade[`Rectangle`](../rectangle/)struktur. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_2)(RectangleF) | Uppdaterar detta`Region` att endast innehålla den del av dess inre som inte korsar det specificerade[`RectangleF`](../rectanglef/)struktur. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_3)(Region) | Uppdaterar detta`Region` att endast innehålla den del av dess inre som inte korsar det specificerade`Region` . |
| [Intersect](../../aspose.psd/region/intersect/#intersect)(GraphicsPath) | Uppdaterar detta`Region` till skärningspunkten av sig själv med det angivna[`GraphicsPath`](../graphicspath/) . |
| [Intersect](../../aspose.psd/region/intersect/#intersect_1)(Rectangle) | Uppdaterar detta`Region` till skärningspunkten av sig själv med det angivna[`Rectangle`](../rectangle/)struktur. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_2)(RectangleF) | Uppdaterar detta`Region` till skärningspunkten av sig själv med det angivna[`RectangleF`](../rectanglef/)struktur. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_3)(Region) | Uppdaterar detta`Region` till skärningspunkten av sig själv med det angivna`Region` . |
| [IsEmpty](../../aspose.psd/region/isempty/)(Graphics) | Testar om detta`Region` har en tom interiör på den angivna ritytan. |
| [IsInfinite](../../aspose.psd/region/isinfinite/)(Graphics) | Testar om detta`Region` har en oändlig interiör på den angivna ritytan. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible)(Point) | Testar om den angivna[`Point`](../point/) strukturen finns i detta`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_2)(PointF) | Testar om den angivna[`PointF`](../pointf/) strukturen finns i detta`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_4)(Rectangle) | Testar om någon del av det angivna[`Rectangle`](../rectangle/) strukturen finns i detta`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_6)(RectangleF) | Testar om någon del av det angivna[`RectangleF`](../rectanglef/) strukturen finns i detta`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_11)(float, float) | Testar om den angivna punkten finns i denna`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_1)(Point, Graphics) | Testar om den angivna[`Point`](../point/) strukturen finns i detta`Region` när den ritas med det angivna[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_3)(PointF, Graphics) | Testar om den angivna[`PointF`](../pointf/) strukturen finns i detta`Region` när den ritas med det angivna[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_5)(Rectangle, Graphics) | Testar om någon del av det angivna[`Rectangle`](../rectangle/) strukturen finns i detta`Region` när den ritas med det angivna[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_7)(RectangleF, Graphics) | Testar om någon del av det angivna[`RectangleF`](../rectanglef/) strukturen finns i detta`Region` när den ritas med det angivna[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_12)(float, float, Graphics) | Testar om den angivna punkten finns i denna`Region` när den ritas med det angivna[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_8)(int, int, Graphics) | Testar om den angivna punkten finns i denna`Region` objekt när det ritas med det angivna[`Graphics`](../graphics/) objekt. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_13)(float, float, float, float) | Testar om någon del av den angivna rektangeln finns i denna`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_9)(int, int, int, int) | Testar om någon del av den angivna rektangeln finns i denna`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_14)(float, float, float, float, Graphics) | Testar om någon del av den angivna rektangeln finns i denna`Region` när den ritas med det angivna[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_10)(int, int, int, int, Graphics) | Testar om någon del av den angivna rektangeln finns i denna`Region` när den ritas med det angivna[`Graphics`](../graphics/) . |
| [MakeEmpty](../../aspose.psd/region/makeempty/)() | Initierar detta`Region` till en tom interiör. |
| [MakeInfinite](../../aspose.psd/region/makeinfinite/)() | Initierar detta`Region` invända mot en oändlig interiör. |
| [Transform](../../aspose.psd/region/transform/)(Matrix) | Förvandlar detta`Region` av den angivna[`Matrix`](../matrix/) . |
| [Translate](../../aspose.psd/region/translate/#translate_1)(float, float) | Förskjuter koordinaterna för detta`Region`med det angivna beloppet. |
| [Translate](../../aspose.psd/region/translate/#translate)(int, int) | Förskjuter koordinaterna för detta`Region`med det angivna beloppet. |
| [Union](../../aspose.psd/region/union/#union)(GraphicsPath) | Uppdaterar detta`Region` till föreningen av sig själv och det specificerade[`GraphicsPath`](../graphicspath/) . |
| [Union](../../aspose.psd/region/union/#union_1)(Rectangle) | Uppdaterar detta`Region` till föreningen av sig själv och det specificerade[`Rectangle`](../rectangle/)struktur. |
| [Union](../../aspose.psd/region/union/#union_2)(RectangleF) | Uppdaterar detta`Region` till föreningen av sig själv och det specificerade[`RectangleF`](../rectanglef/)struktur. |
| [Union](../../aspose.psd/region/union/#union_3)(Region) | Uppdaterar detta`Region` till föreningen av sig själv och det specificerade`Region` . |
| [Xor](../../aspose.psd/region/xor/#xor)(GraphicsPath) | Uppdaterar detta`Region` till facket minus skärningspunkten för sig själv med det angivna[`GraphicsPath`](../graphicspath/) . |
| [Xor](../../aspose.psd/region/xor/#xor_1)(Rectangle) | Uppdaterar detta`Region` till facket minus skärningspunkten för sig själv med det angivna[`Rectangle`](../rectangle/)struktur. |
| [Xor](../../aspose.psd/region/xor/#xor_2)(RectangleF) | Uppdaterar detta`Region` till facket minus skärningspunkten för sig själv med det angivna[`RectangleF`](../rectanglef/)struktur. |
| [Xor](../../aspose.psd/region/xor/#xor_3)(Region) | Uppdaterar detta`Region` till facket minus skärningspunkten för sig själv med det angivna`Region` . |

### Se även

* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


