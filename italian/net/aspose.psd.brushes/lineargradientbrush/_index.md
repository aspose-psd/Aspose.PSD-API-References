---
title: Class LinearGradientBrush
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.Brushes.LinearGradientBrush classe. Incapsula aBrush con un gradiente lineare. Questa classe non può essere ereditata.
type: docs
weight: 140
url: /it/net/aspose.psd.brushes/lineargradientbrush/
---
## LinearGradientBrush class

Incapsula a[`Brush`](../../aspose.psd/brush/) con un gradiente lineare. Questa classe non può essere ereditata.

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush/#constructor)() | Inizializza una nuova istanza di`LinearGradientBrush` class con parametri predefiniti. Il colore iniziale è nero, il colore finale è bianco, l'angolo è di 45 gradi e il rettangolo si trova in (0,0) con dimensione (1,1). |
| [LinearGradientBrush](lineargradientbrush/#constructor_1)(Point, Point, Color, Color) | Inizializza una nuova istanza di`LinearGradientBrush` classe con i punti e i colori specificati. |
| [LinearGradientBrush](lineargradientbrush/#constructor_2)(PointF, PointF, Color, Color) | Inizializza una nuova istanza di`LinearGradientBrush` classe con i punti e i colori specificati. |
| [LinearGradientBrush](lineargradientbrush/#constructor_3)(Rectangle, Color, Color, float) | Inizializza una nuova istanza di`LinearGradientBrush` classe basata su un rettangolo, colori iniziali e finali e un angolo di orientamento. |
| [LinearGradientBrush](lineargradientbrush/#constructor_5)(RectangleF, Color, Color, float) | Inizializza una nuova istanza di`LinearGradientBrush` classe basata su un rettangolo, colori iniziali e finali e un angolo di orientamento. |
| [LinearGradientBrush](lineargradientbrush/#constructor_4)(Rectangle, Color, Color, float, bool) | Inizializza una nuova istanza di`LinearGradientBrush` classe basata su un rettangolo, colori iniziali e finali e un angolo di orientamento. |
| [LinearGradientBrush](lineargradientbrush/#constructor_6)(RectangleF, Color, Color, float, bool) | Inizializza una nuova istanza di`LinearGradientBrush` classe basata su un rettangolo, colori iniziali e finali e un angolo di orientamento. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | Ottiene o imposta l'angolo del gradiente. |
| [Blend](../../aspose.psd.brushes/lineargradientbrush/blend/) { get; set; } | Ottiene o imposta a[`Blend`](../../aspose.psd/blend/) che specifica posizioni e fattori che definiscono un decadimento personalizzato per il gradiente. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [EndColor](../../aspose.psd.brushes/lineargradientbrush/endcolor/) { get; set; } | Ottiene o imposta il colore del gradiente finale. |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | Ottiene o imposta un valore che indica se la correzione gamma è abilitata per questo[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | Ottiene o imposta un valore che indica se[`Angle`](../lineargradientbrushbase/angle/) viene cambiato durante le trasformazioni con questo[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Ottiene un valore che indica se le trasformazioni sono state modificate in qualche modo. Ad esempio impostando la matrice di trasformazione o chiamando uno qualsiasi dei metodi che alterano la matrice di trasformazione. La proprietà viene introdotta per compatibilità con le versioni precedenti con GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Ottiene o imposta l'opacità del pennello. Il valore dovrebbe essere compreso tra 0 e 1. Il valore 0 significa che il pennello è completamente visibile, il valore 1 significa che il pennello è completamente opaco. |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | Ottiene o imposta un'area rettangolare che definisce i punti iniziale e finale del gradiente. |
| [StartColor](../../aspose.psd.brushes/lineargradientbrush/startcolor/) { get; set; } | Ottiene o imposta il colore del gradiente iniziale. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Ottiene o imposta una copia[`Matrix`](../../aspose.psd/matrix/) che definisce una trasformazione geometrica locale per questo[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Ottiene o imposta a[`WrapMode`](../../aspose.psd/wrapmode/) enumerazione che indica la modalità wrap per this[`TransformBrush`](../transformbrush/) . |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Crea un nuovo clone profondo della corrente[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Elimina l'istanza corrente. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Moltiplica il[`Matrix`](../../aspose.psd/matrix/) che rappresenta la trasformata geometrica locale di this`LinearGradientBrush` da quanto specificato[`Matrix`](../../aspose.psd/matrix/) anteponendo il specificato[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Moltiplica il[`Matrix`](../../aspose.psd/matrix/) che rappresenta la trasformata geometrica locale di this`LinearGradientBrush` da quanto specificato[`Matrix`](../../aspose.psd/matrix/) nell'ordine specificato. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Reimposta il[`Transform`](../transformbrush/transform/) proprietà all'identità. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Ruota la trasformazione geometrica locale della quantità specificata. Questo metodo antepone la rotazione alla trasformazione. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Ruota la trasformazione geometrica locale della quantità specificata nell'ordine specificato. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Ridimensiona la trasformazione geometrica locale delle quantità specificate. Questo metodo antepone la matrice di ridimensionamento alla trasformazione. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Ridimensiona la trasformazione geometrica locale delle quantità specificate nell'ordine specificato. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | Crea un gradiente lineare con un colore centrale e una decadenza lineare in un unico colore su entrambe le estremità. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | Crea un gradiente lineare con un colore centrale e una decadenza lineare in un unico colore su entrambe le estremità. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape)(float) | Crea un decadimento del gradiente basato su una curva a campana. |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | Crea un decadimento del gradiente basato su una curva a campana. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Trasla la trasformazione geometrica locale in base alle dimensioni specificate. Questo metodo antepone la traduzione alla trasformazione. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato. |

### Guarda anche

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* spazio dei nomi [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assemblea [Aspose.PSD](../../)


