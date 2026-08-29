---
title: "Klass Region"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Region-klass. Beskriver innanmätet av en grafisk form som består av rektanglar och banor. Denna klass kan inte ärvas."
type: docs
weight: 5860
url: /sv/net/aspose.psd/region/
---
{{< psd/tize >}}
## Region class

Beskriver insidan av en grafisk form bestående av rektanglar och banor. Denna klass kan inte ärvas.

```csharp
public sealed class Region
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Region](region/#constructor)() | Initierar en ny `Region`. |
| [Region](region/#constructor_1)(GraphicsPath) | Initierar en ny `Region` med den angivna [`GraphicsPath`](../graphicspath/). |
| [Region](region/#constructor_2)(Rectangle) | Initierar en ny `Region` från den angivna [`Rectangle`](../rectangle/) strukturen. |
| [Region](region/#constructor_3)(RectangleF) | Initierar en ny `Region` från den angivna [`RectangleF`](../rectanglef/) strukturen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Complement](../../aspose.psd/region/complement/#complement)(GraphicsPath) | Uppdaterar detta `Region` så att det innehåller den del av den angivna [`GraphicsPath`](../graphicspath/) som inte skär detta `Region`. |
| [Complement](../../aspose.psd/region/complement/#complement_1)(Rectangle) | Uppdaterar detta `Region` så att det innehåller den del av den angivna [`Rectangle`](../rectangle/) strukturen som inte skär detta `Region`. |
| [Complement](../../aspose.psd/region/complement/#complement_2)(RectangleF) | Uppdaterar detta `Region` så att det innehåller den del av den angivna [`RectangleF`](../rectanglef/) strukturen som inte skär detta `Region`. |
| [Complement](../../aspose.psd/region/complement/#complement_3)(Region) | Uppdaterar detta `Region` så att det innehåller den del av det angivna `Region` som inte skär detta `Region`. |
| [DeepClone](../../aspose.psd/region/deepclone/)() | Skapar en exakt djupkopiering av detta `Region`. |
| override [Equals](../../aspose.psd/region/equals/#equals_1)(object) | Kontrollera om objekt är lika. |
| [Equals](../../aspose.psd/region/equals/#equals)(Region, Graphics) | Testar om det angivna `Region` är identiskt med detta `Region` på den angivna ritytan. |
| [Exclude](../../aspose.psd/region/exclude/#exclude)(GraphicsPath) | Uppdaterar detta `Region` så att det endast innehåller den del av dess innandöme som inte skär den angivna [`GraphicsPath`](../graphicspath/). |
| [Exclude](../../aspose.psd/region/exclude/#exclude_1)(Rectangle) | Uppdaterar detta `Region` så att det endast innehåller den del av dess innandöme som inte skär den angivna [`Rectangle`](../rectangle/) strukturen. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_2)(RectangleF) | Uppdaterar detta `Region` så att det endast innehåller den del av dess innandöme som inte skär den angivna [`RectangleF`](../rectanglef/) strukturen. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_3)(Region) | Uppdaterar detta `Region` så att det endast innehåller den del av dess innandöme som inte skär det angivna `Region`. |
| override [GetHashCode](../../aspose.psd/region/gethashcode/)() | Hämta hashkod för det aktuella objektet. |
| [Intersect](../../aspose.psd/region/intersect/#intersect)(GraphicsPath) | Uppdaterar detta `Region` till skärningen av sig själv med den angivna [`GraphicsPath`](../graphicspath/). |
| [Intersect](../../aspose.psd/region/intersect/#intersect_1)(Rectangle) | Uppdaterar detta `Region` till skärningen av sig själv med den angivna [`Rectangle`](../rectangle/) strukturen. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_2)(RectangleF) | Uppdaterar detta `Region` till skärningen av sig själv med den angivna [`RectangleF`](../rectanglef/) strukturen. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_3)(Region) | Uppdaterar detta `Region` till skärningen av sig själv med det angivna `Region`. |
| [IsEmpty](../../aspose.psd/region/isempty/)(Graphics) | Testar om detta `Region` har ett tomt innandöme på den angivna ritytan. |
| [IsInfinite](../../aspose.psd/region/isinfinite/)(Graphics) | Testar om detta `Region` har ett oändligt innandöme på den angivna ritytan. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible)(Point) | Testar om den angivna [`Point`](../point/) strukturen finns inom denna `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_2)(PointF) | Testar om den angivna [`PointF`](../pointf/) strukturen finns inom denna `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_4)(Rectangle) | Testar om någon del av den angivna [`Rectangle`](../rectangle/) strukturen finns inom denna `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_6)(RectangleF) | Testar om någon del av den angivna [`RectangleF`](../rectanglef/) strukturen finns inom denna `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_11)(float, float) | Testar om den angivna punkten finns inom denna `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_1)(Point, Graphics) | Testar om den angivna [`Point`](../point/) strukturen finns inom denna `Region` när den ritas med den angivna [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_3)(PointF, Graphics) | Testar om den angivna [`PointF`](../pointf/) strukturen finns inom denna `Region` när den ritas med den angivna [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_5)(Rectangle, Graphics) | Testar om någon del av den angivna [`Rectangle`](../rectangle/) strukturen finns inom denna `Region` när den ritas med den angivna [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_7)(RectangleF, Graphics) | Testar om någon del av den angivna [`RectangleF`](../rectanglef/) strukturen finns inom denna `Region` när den ritas med den angivna [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_12)(float, float, Graphics) | Testar om den angivna punkten finns inom denna `Region` när den ritas med den angivna [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_8)(int, int, Graphics) | Testar om den angivna punkten finns inom detta `Region`-objekt när den ritas med det angivna [`Graphics`](../graphics/)-objektet. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_13)(float, float, float, float) | Testar om någon del av den angivna rektangeln finns inom denna `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_9)(int, int, int, int) | Testar om någon del av den angivna rektangeln finns inom denna `Region`. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_14)(float, float, float, float, Graphics) | Testar om någon del av den angivna rektangeln finns inom denna `Region` när den ritas med den angivna [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_10)(int, int, int, int, Graphics) | Testar om någon del av den angivna rektangeln finns inom denna `Region` när den ritas med den angivna [`Graphics`](../graphics/). |
| [MakeEmpty](../../aspose.psd/region/makeempty/)() | Initierar detta `Region` med ett tomt inre. |
| [MakeInfinite](../../aspose.psd/region/makeinfinite/)() | Initierar detta `Region`-objekt till ett oändligt inre. |
| [Transform](../../aspose.psd/region/transform/)(Matrix) | Transformerar detta `Region` med den angivna [`Matrix`](../matrix/). |
| [Translate](../../aspose.psd/region/translate/#translate_1)(float, float) | Förskjuter koordinaterna för detta `Region` med den angivna mängden. |
| [Translate](../../aspose.psd/region/translate/#translate)(int, int) | Förskjuter koordinaterna för detta `Region` med den angivna mängden. |
| [Union](../../aspose.psd/region/union/#union)(GraphicsPath) | Uppdaterar detta `Region` till unionen av sig själv och den angivna [`GraphicsPath`](../graphicspath/). |
| [Union](../../aspose.psd/region/union/#union_1)(Rectangle) | Uppdaterar detta `Region` till unionen av sig själv och den angivna [`Rectangle`](../rectangle/) strukturen. |
| [Union](../../aspose.psd/region/union/#union_2)(RectangleF) | Uppdaterar detta `Region` till unionen av sig själv och den angivna [`RectangleF`](../rectanglef/) strukturen. |
| [Union](../../aspose.psd/region/union/#union_3)(Region) | Uppdaterar detta `Region` till unionen av sig själv och den angivna `Region`. |
| [Xor](../../aspose.psd/region/xor/#xor)(GraphicsPath) | Uppdaterar detta `Region` till unionen minus skärningen av sig själv med den angivna [`GraphicsPath`](../graphicspath/). |
| [Xor](../../aspose.psd/region/xor/#xor_1)(Rectangle) | Uppdaterar detta `Region` till unionen minus skärningen av sig själv med den angivna [`Rectangle`](../rectangle/) strukturen. |
| [Xor](../../aspose.psd/region/xor/#xor_2)(RectangleF) | Uppdaterar detta `Region` till unionen minus skärningen av sig själv med den angivna [`RectangleF`](../rectanglef/) strukturen. |
| [Xor](../../aspose.psd/region/xor/#xor_3)(Region) | Uppdaterar detta `Region` till unionen minus skärningen av sig själv med den angivna `Region`. |

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


