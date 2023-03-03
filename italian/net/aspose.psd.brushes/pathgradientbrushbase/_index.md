---
title: Class PathGradientBrushBase
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.Brushes.PathGradientBrushBase classe. Rappresenta aBrush con funzionalità del gradiente del percorso di base.
type: docs
weight: 180
url: /it/net/aspose.psd.brushes/pathgradientbrushbase/
---
## PathGradientBrushBase class

Rappresenta a[`Brush`](../../aspose.psd/brush/) con funzionalità del gradiente del percorso di base.

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Ottiene o imposta il punto centrale del gradiente del percorso. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Ottiene o imposta il punto focale per la riduzione del gradiente. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | Ottiene il percorso grafico su cui è stato creato questo pennello. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Ottiene un valore che indica se le trasformazioni sono state modificate in qualche modo. Ad esempio impostando la matrice di trasformazione o chiamando uno qualsiasi dei metodi che alterano la matrice di trasformazione. La proprietà viene introdotta per compatibilità con le versioni precedenti con GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Ottiene o imposta l'opacità del pennello. Il valore dovrebbe essere compreso tra 0 e 1. Il valore 0 significa che il pennello è completamente visibile, il valore 1 significa che il pennello è completamente opaco. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | Ottiene i punti del percorso su cui è stato costruito questo pennello. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Ottiene o imposta una copia[`Matrix`](../../aspose.psd/matrix/) che definisce una trasformazione geometrica locale per questo[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Ottiene o imposta a[`WrapMode`](../../aspose.psd/wrapmode/) enumerazione che indica la modalità wrap per this[`TransformBrush`](../transformbrush/) . |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Crea un nuovo clone profondo della corrente[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Elimina l'istanza corrente. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | Moltiplica il[`Matrix`](../../aspose.psd/matrix/) che rappresenta la trasformata geometrica locale di this[`LinearGradientBrush`](../lineargradientbrush/) da quanto specificato[`Matrix`](../../aspose.psd/matrix/) anteponendo il specificato[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | Moltiplica il[`Matrix`](../../aspose.psd/matrix/) che rappresenta la trasformata geometrica locale di this[`LinearGradientBrush`](../lineargradientbrush/) da quanto specificato[`Matrix`](../../aspose.psd/matrix/) nell'ordine specificato. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Reimposta il[`Transform`](../transformbrush/transform/) proprietà all'identità. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | Ruota la trasformazione geometrica locale della quantità specificata. Questo metodo antepone la rotazione alla trasformazione. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | Ruota la trasformazione geometrica locale della quantità specificata nell'ordine specificato. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | Ridimensiona la trasformazione geometrica locale delle quantità specificate. Questo metodo antepone la matrice di ridimensionamento alla trasformazione. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | Ridimensiona la trasformazione geometrica locale delle quantità specificate nell'ordine specificato. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Trasla la trasformazione geometrica locale in base alle dimensioni specificate. Questo metodo antepone la traduzione alla trasformazione. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato. |

### Osservazioni

Si noti che durante la creazione del file`PathGradientBrushBase` class dovrebbe essere inizializzato con almeno 2 punti. Il percorso interno creato sarà sempre una figura chiusa, l'ultimo punto collega il primo punto. Quella forma è piena di questo`PathGradientBrushBase`. L'implementazione GDI+ genera un fileOutOfMemoryException quando si passano array vuoti o set di punti con le stesse coordinate. The`PathGradientBrushBase` genera un'eccezione quando l'array points contiene meno di 2 punti, theArgumentException is gettato piuttosto cheOutOfMemoryException quando la matrice di punti è inaccettabile. Il punto centrale viene calcolato come centro di massa per i punti passati per impostazione predefinita. Un utente può modificare questo punto in un secondo momento. Per impostazione predefinita, la scala del focus è un punto vuoto (0.0, 0.0).

### Guarda anche

* class [TransformBrush](../transformbrush/)
* spazio dei nomi [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assemblea [Aspose.PSD](../../)


