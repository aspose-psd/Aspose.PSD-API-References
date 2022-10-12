---
title: PathGradientBrushBase
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Rappresenta aBrush../aspose.psd/brush con funzionalità di gradiente del percorso di base.
type: docs
weight: 180
url: /it/net/aspose.psd.brushes/pathgradientbrushbase/
---
## PathGradientBrushBase class

Rappresenta a[`Brush`](../../aspose.psd/brush) con funzionalità di gradiente del percorso di base.

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint) { get; set; } | Ottiene o imposta il punto centrale del gradiente del percorso. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales) { get; set; } | Ottiene o imposta il punto focale per la diminuzione del gradiente. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath) { get; } | Ottiene il percorso grafico su cui è stato creato questo pennello. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged) { get; } | Ottiene un valore che indica se le trasformazioni sono state modificate in qualche modo. Ad esempio, impostando la matrice di trasformazione o chiamando uno qualsiasi dei metodi che alterano la matrice di trasformazione. La proprietà è stata introdotta per la compatibilità con le versioni precedenti con GDI+. |
| [Opacity](../../aspose.psd/brush/opacity) { get; set; } | Ottiene o imposta l'opacità del pennello. Il valore deve essere compreso tra 0 e 1. Il valore 0 significa che il pennello è completamente visibile, il valore 1 significa che il pennello è completamente opaco. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints) { get; } | Ottiene i punti del percorso su cui è stato creato questo pennello. |
| [Transform](../../aspose.psd.brushes/transformbrush/transform) { get; set; } | Ottiene o imposta una copia[`Matrix`](../../aspose.psd/matrix) che definisce una trasformata geometrica locale per questo[`TransformBrush`](../transformbrush) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode) { get; set; } | Ottiene o imposta a[`WrapMode`](../../aspose.psd/wrapmode) enumerazione che indica la modalità di avvolgimento per questo[`TransformBrush`](../transformbrush) . |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone)() | Crea un nuovo clone profondo della corrente[`Brush`](../../aspose.psd/brush) . |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Elimina l'istanza corrente. |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform)(Matrix) | Moltiplica il[`Matrix`](../../aspose.psd/matrix) che rappresenta la trasformata geometrica locale di questo[`LinearGradientBrush`](../lineargradientbrush) dal specificato[`Matrix`](../../aspose.psd/matrix) anteponendo quello specificato[`Matrix`](../../aspose.psd/matrix) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform)(Matrix, MatrixOrder) | Moltiplica il[`Matrix`](../../aspose.psd/matrix) che rappresenta la trasformata geometrica locale di questo[`LinearGradientBrush`](../lineargradientbrush) dal specificato[`Matrix`](../../aspose.psd/matrix) nell'ordine specificato. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform)() | Reimposta il[`Transform`](../transformbrush/transform) proprietà su identità. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform)(float) | Ruota la trasformazione geometrica locale della quantità specificata. Questo metodo antepone la rotazione alla trasformazione. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform)(float, MatrixOrder) | Ruota la trasformazione geometrica locale della quantità specificata nell'ordine specificato. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform)(float, float) | Ridimensiona la trasformazione geometrica locale degli importi specificati. Questo metodo antepone la matrice di ridimensionamento alla trasformazione. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform)(float, float, MatrixOrder) | Ridimensiona la trasformazione geometrica locale degli importi specificati nell'ordine specificato. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform)(float, float) | Converte la trasformazione geometrica locale in base alle dimensioni specificate. Questo metodo antepone la traduzione alla trasformazione. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Converte la trasformazione geometrica locale in base alle dimensioni specificate nell'ordine specificato. |

### Osservazioni

Si noti che durante la creazione del file[`PathGradientBrushBase`](../pathgradientbrushbase) classe dovrebbe essere inizializzato con almeno 2 punti. Il percorso interno creato sarà sempre una figura chiusa, l'ultimo punto collega il primo punto. Quella forma è piena di questo[`PathGradientBrushBase`](../pathgradientbrushbase). L'implementazione GDI+ genera unOutOfMemoryException quando si passano in array vuoti o punti impostati con le stesse coordinate. Il[`PathGradientBrushBase`](../pathgradientbrushbase) genera un'eccezione quando l'array di punti contiene meno di 2 punti, ilArgumentException is lanciato anzichéOutOfMemoryException quando l'array di punti è inaccettabile. Il punto centrale viene calcolato come centro di massa per i punti passati per impostazione predefinita. Un utente può modificare questo punto in un secondo momento. La scala di messa a fuoco è un punto vuoto (0.0, 0.0) per impostazione predefinita.

### Guarda anche

* class [TransformBrush](../transformbrush)
* spazio dei nomi [Aspose.PSD.Brushes](../../aspose.psd.brushes)
* assemblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
