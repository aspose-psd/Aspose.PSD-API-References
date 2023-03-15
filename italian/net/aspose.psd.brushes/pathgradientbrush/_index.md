---
title: Class PathGradientBrush
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.Brushes.PathGradientBrush classe. Incapsula aBrush oggetto con un gradiente. Questa classe non può essere ereditata.
type: docs
weight: 170
url: /it/net/aspose.psd.brushes/pathgradientbrush/
---
## PathGradientBrush class

Incapsula a[`Brush`](../../aspose.psd/brush/) oggetto con un gradiente. Questa classe non può essere ereditata.

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PathGradientBrush](pathgradientbrush/#constructor)(GraphicsPath) | Inizializza una nuova istanza di`PathGradientBrush` classe con il percorso specificato. |
| [PathGradientBrush](pathgradientbrush/#constructor_1)(PointF[]) | Inizializza una nuova istanza di`PathGradientBrush` classe con i punti specificati. |
| [PathGradientBrush](pathgradientbrush/#constructor_3)(Point[]) | Inizializza una nuova istanza di`PathGradientBrush` classe con i punti specificati. |
| [PathGradientBrush](pathgradientbrush/#constructor_2)(PointF[], WrapMode) | Inizializza una nuova istanza di`PathGradientBrush` classe con i punti specificati e la modalità a capo. |
| [PathGradientBrush](pathgradientbrush/#constructor_4)(Point[], WrapMode) | Inizializza una nuova istanza di`PathGradientBrush` classe con i punti specificati e la modalità a capo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Blend](../../aspose.psd.brushes/pathgradientbrush/blend/) { get; set; } | Ottiene o imposta a[`Blend`](../../aspose.psd/blend/) che specifica posizioni e fattori che definiscono un decadimento personalizzato per il gradiente. |
| [CenterColor](../../aspose.psd.brushes/pathgradientbrush/centercolor/) { get; set; } | Ottiene o imposta il colore al centro del gradiente del percorso. |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | Ottiene o imposta il punto centrale del gradiente del percorso. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | Ottiene o imposta il punto focale per la riduzione del gradiente. |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | Ottiene il percorso grafico su cui è stato creato questo pennello. |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | Ottiene un valore che indica se le trasformazioni sono state modificate in qualche modo. Ad esempio impostando la matrice di trasformazione o chiamando uno qualsiasi dei metodi che alterano la matrice di trasformazione. La proprietà viene introdotta per compatibilità con le versioni precedenti con GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Ottiene o imposta l'opacità del pennello. Il valore dovrebbe essere compreso tra 0 e 1. Il valore 0 significa che il pennello è completamente visibile, il valore 1 significa che il pennello è completamente opaco. |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | Ottiene i punti del percorso su cui è stato costruito questo pennello. |
| [SurroundColors](../../aspose.psd.brushes/pathgradientbrush/surroundcolors/) { get; set; } | Ottiene o imposta una matrice di colori che corrispondono ai punti nel percorso this`PathGradientBrush` riempie. |
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
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | Crea una sfumatura con un colore centrale e una decadenza lineare rispetto a un colore circostante. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | Crea una sfumatura con un colore centrale e una decadenza lineare per ciascun colore circostante. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape)(float) | Crea un pennello sfumato che cambia colore a partire dal centro del tracciato verso l'esterno fino al limite del tracciato. La transizione da un colore all'altro si basa su una curva a campana. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | Crea un pennello sfumato che cambia colore a partire dal centro del tracciato verso l'esterno fino al limite del tracciato. La transizione da un colore all'altro si basa su una curva a campana. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | Trasla la trasformazione geometrica locale in base alle dimensioni specificate. Questo metodo antepone la traduzione alla trasformazione. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato. |

### Osservazioni

Il colore centrale è bianco per impostazione predefinita. Un utente può modificare questo valore in qualsiasi momento successivo.

L'array dei colori surround è inizializzato da un singolo elemento contenente il colore bianco per impostazione predefinita. I colori surround possono essere modificati in seguito, tuttavia è necessario almeno un singolo elemento quando si impostano i colori surround.

Vedi il[`Blend`](./blend/) per ulteriori dettagli sulla sua inizializzazione.

### Guarda anche

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* spazio dei nomi [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assemblea [Aspose.PSD](../../)


