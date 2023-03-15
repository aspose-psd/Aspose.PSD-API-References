---
title: Class TransformBrush
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.Brushes.TransformBrush classe. ABrush con capacità di trasformazione.
type: docs
weight: 220
url: /it/net/aspose.psd.brushes/transformbrush/
---
## TransformBrush class

A[`Brush`](../../aspose.psd/brush/) con capacità di trasformazione.

```csharp
public abstract class TransformBrush : Brush
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Ottiene un valore che indica se le trasformazioni sono state modificate in qualche modo. Ad esempio impostando la matrice di trasformazione o chiamando uno qualsiasi dei metodi che alterano la matrice di trasformazione. La proprietà viene introdotta per compatibilità con le versioni precedenti con GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Ottiene o imposta l'opacità del pennello. Il valore dovrebbe essere compreso tra 0 e 1. Il valore 0 significa che il pennello è completamente visibile, il valore 1 significa che il pennello è completamente opaco. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | Ottiene o imposta una copia[`Matrix`](../../aspose.psd/matrix/) che definisce una trasformazione geometrica locale per questo`TransformBrush` . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | Ottiene o imposta a[`WrapMode`](../../aspose.psd/wrapmode/) enumerazione che indica la modalità wrap per this`TransformBrush` . |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Crea un nuovo clone profondo della corrente[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Elimina l'istanza corrente. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/#multiplytransform)(Matrix) | Moltiplica il[`Matrix`](../../aspose.psd/matrix/) che rappresenta la trasformata geometrica locale di this[`LinearGradientBrush`](../lineargradientbrush/) da quanto specificato[`Matrix`](../../aspose.psd/matrix/) anteponendo il specificato[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Moltiplica il[`Matrix`](../../aspose.psd/matrix/) che rappresenta la trasformata geometrica locale di this[`LinearGradientBrush`](../lineargradientbrush/) da quanto specificato[`Matrix`](../../aspose.psd/matrix/) nell'ordine specificato. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | Reimposta il[`Transform`](./transform/) proprietà all'identità. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/#rotatetransform)(float) | Ruota la trasformazione geometrica locale della quantità specificata. Questo metodo antepone la rotazione alla trasformazione. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Ruota la trasformazione geometrica locale della quantità specificata nell'ordine specificato. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/#scaletransform)(float, float) | Ridimensiona la trasformazione geometrica locale delle quantità specificate. Questo metodo antepone la matrice di ridimensionamento alla trasformazione. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Ridimensiona la trasformazione geometrica locale delle quantità specificate nell'ordine specificato. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/#translatetransform)(float, float) | Trasla la trasformazione geometrica locale in base alle dimensioni specificate. Questo metodo antepone la traduzione alla trasformazione. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato. |

### Guarda anche

* class [Brush](../../aspose.psd/brush/)
* spazio dei nomi [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assemblea [Aspose.PSD](../../)


