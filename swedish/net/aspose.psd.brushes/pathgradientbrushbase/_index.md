---
title: Class PathGradientBrushBase
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.Brushes.PathGradientBrushBase klass. Representerar enBrush med basbanagradientfunktion.
type: docs
weight: 180
url: /sv/net/aspose.psd.brushes/pathgradientbrushbase/
---
## PathGradientBrushBase class

Representerar en[`Brush`](../../aspose.psd/brush/) med basbanagradientfunktion.

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Hämtar eller ställer in mittpunkten för banans gradient. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Hämtar eller ställer in fokuspunkten för gradientnedgången. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | Får den grafiska vägen som denna pensel byggdes på. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Får ett värde som indikerar om transformationer har ändrats på något sätt. Till exempel att ställa in transformationsmatrisen eller anropa någon av metoderna som ändrar transformationsmatrisen. Egenskapen introduceras för bakåtkompatibilitet med GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Hämtar eller ställer in borstens opacitet. Värdet ska vara mellan 0 och 1. Värdet 0 betyder att borsten är helt synlig, värdet 1 betyder att borsten är helt ogenomskinlig. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | Får vägpunkterna som denna pensel byggdes på. |
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

### Anmärkningar

Observera att när du skapar`PathGradientBrushBase` klass bör den initialiseras med minst 2 poäng. Den interna sökvägen create kommer alltid att vara en stängd figur, den sista punkten förbinder den första punkten. Den formen är fylld med detta`PathGradientBrushBase`. GDI+-implementeringen kastar enOutOfMemoryException när du passerar i tomma arrayer eller punkter som har samma koordinater. The`PathGradientBrushBase` kastar ett undantag när poängmatrisen innehåller mindre än 2 punkter, denArgumentException is kastas i stället förOutOfMemoryException när poängmatrisen är oacceptabel. Mittpunkten beräknas som ett masscentrum för de passerade punkterna som standard. En användare kan ändra denna punkt senare. Fokusskalan är en tom punkt (0.0, 0.0) som standard.

### Se även

* class [TransformBrush](../transformbrush/)
* namnutrymme [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* hopsättning [Aspose.PSD](../../)


