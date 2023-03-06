---
title: Class TextureBrush
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.Brushes.TextureBrush klass. Varje egenskap iTextureBrush klass är enBrush objekt som använder en bild för att fylla det inre av en form. Denna klass kan inte ärvas.
type: docs
weight: 210
url: /sv/net/aspose.psd.brushes/texturebrush/
---
## TextureBrush class

Varje egenskap i`TextureBrush` klass är en[`Brush`](../../aspose.psd/brush/) objekt som använder en bild för att fylla det inre av en form. Denna klass kan inte ärvas.

```csharp
public sealed class TextureBrush : TransformBrush
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | Initierar en ny instans av`TextureBrush` klass som använder den angivna bilden. |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | Initierar en ny instans av`TextureBrush` klass som använder den angivna bilden och avgränsande rektangel. |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | Initierar en ny instans av`TextureBrush` klass som använder den angivna bilden och avgränsande rektangel. |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | Initierar en ny instans av`TextureBrush` klass som använder den angivna bilden och radbrytningsläget. |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | Initierar en ny instans av`TextureBrush` klass som använder den angivna bilden, begränsningsrektangeln och bildattributen. |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | Initierar en ny instans av`TextureBrush` klass som använder den angivna bilden, begränsningsrektangeln och bildattributen. |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | Initierar en ny instans av`TextureBrush`klass som använder den angivna bilden, radbrytningsläge och avgränsande rektangel. |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | Initierar en ny instans av`TextureBrush`klass som använder den angivna bilden, radbrytningsläge och avgränsande rektangel. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [Image](../../aspose.psd.brushes/texturebrush/image/) { get; } | Får[`Image`](../../aspose.psd/image/) objekt associerat med detta`TextureBrush` objekt. |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes/) { get; } | Får[`ImageAttributes`](./imageattributes/) i samband med detta`TextureBrush` . |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle/) { get; } | Får[`Rectangle`](../../aspose.psd/rectangle/) i samband med detta`TextureBrush` . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Får ett värde som indikerar om transformationer har ändrats på något sätt. Till exempel att ställa in transformationsmatrisen eller anropa någon av metoderna som ändrar transformationsmatrisen. Egenskapen introduceras för bakåtkompatibilitet med GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Hämtar eller ställer in borstens opacitet. Värdet ska vara mellan 0 och 1. Värdet 0 betyder att borsten är helt synlig, värdet 1 betyder att borsten är helt ogenomskinlig. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Hämtar eller ställer in en kopia[`Matrix`](../../aspose.psd/matrix/) som definierar en lokal geometrisk transformation för detta[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Hämtar eller sätter en[`WrapMode`](../../aspose.psd/wrapmode/) uppräkning som anger lindningsläget för detta[`TransformBrush`](../transformbrush/) . |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Skapar en ny djup klon av strömmen[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Tar bort den aktuella instansen. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Multiplicerar[`Matrix`](../../aspose.psd/matrix/) som representerar den lokala geometriska transformationen av detta[`LinearGradientBrush`](../lineargradientbrush/) av den angivna[`Matrix`](../../aspose.psd/matrix/) genom att föregå det angivna[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Multiplicerar[`Matrix`](../../aspose.psd/matrix/) som representerar den lokala geometriska transformationen av detta[`LinearGradientBrush`](../lineargradientbrush/) av den angivna[`Matrix`](../../aspose.psd/matrix/) i angiven ordning. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Återställer[`Transform`](../transformbrush/transform/) egenskap till identitet. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Roterar den lokala geometriska transformationen med angivet belopp. Denna metod förutsätter rotationen till transformationen. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Roterar den lokala geometriska transformationen med angivet belopp i angiven ordning. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Skalar den lokala geometriska transformationen med de angivna mängderna. Den här metoden lägger in skalningsmatrisen i transformationen. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Skalar den lokala geometriska transformationen med de angivna mängderna i angiven ordning. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Översätter den lokala geometriska transformationen med de angivna måtten. Denna metod lägger till översättningen till transformen. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Översätter den lokala geometriska transformationen med de angivna måtten i angiven ordning. |

### Se även

* class [TransformBrush](../transformbrush/)
* namnutrymme [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* hopsättning [Aspose.PSD](../../)


