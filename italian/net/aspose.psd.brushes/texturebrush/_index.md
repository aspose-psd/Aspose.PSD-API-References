---
title: TextureBrush
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Ogni proprietà delTextureBrush./texturebrush la classe è aBrush../aspose.psd/brush oggetto che utilizza unimmagine per riempire linterno di una forma. Questa classe non può essere ereditata.
type: docs
weight: 210
url: /it/net/aspose.psd.brushes/texturebrush/
---
## TextureBrush class

Ogni proprietà del[`TextureBrush`](../texturebrush) la classe è a[`Brush`](../../aspose.psd/brush) oggetto che utilizza un'immagine per riempire l'interno di una forma. Questa classe non può essere ereditata.

```csharp
public sealed class TextureBrush : TransformBrush
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextureBrush](texturebrush#constructor)(Image) | Inizializza una nuova istanza di[`TextureBrush`](../texturebrush) classe che utilizza l'immagine specificata. |
| [TextureBrush](texturebrush#constructor_1)(Image, Rectangle) | Inizializza una nuova istanza di[`TextureBrush`](../texturebrush) classe che utilizza l'immagine e il rettangolo di delimitazione specificati. |
| [TextureBrush](texturebrush#constructor_3)(Image, RectangleF) | Inizializza una nuova istanza di[`TextureBrush`](../texturebrush) classe che utilizza l'immagine e il rettangolo di delimitazione specificati. |
| [TextureBrush](texturebrush#constructor_5)(Image, WrapMode) | Inizializza una nuova istanza di[`TextureBrush`](../texturebrush) classe che utilizza l'immagine e la modalità di avvolgimento specificate. |
| [TextureBrush](texturebrush#constructor_2)(Image, Rectangle, ImageAttributes) | Inizializza una nuova istanza di[`TextureBrush`](../texturebrush) classe che utilizza l'immagine, il rettangolo di delimitazione e gli attributi dell'immagine specificati. |
| [TextureBrush](texturebrush#constructor_4)(Image, RectangleF, ImageAttributes) | Inizializza una nuova istanza di[`TextureBrush`](../texturebrush) classe che utilizza l'immagine, il rettangolo di delimitazione e gli attributi dell'immagine specificati. |
| [TextureBrush](texturebrush#constructor_6)(Image, WrapMode, Rectangle) | Inizializza una nuova istanza di[`TextureBrush`](../texturebrush)classe che utilizza l'immagine, la modalità di avvolgimento e il rettangolo di delimitazione specificati. |
| [TextureBrush](texturebrush#constructor_7)(Image, WrapMode, RectangleF) | Inizializza una nuova istanza di[`TextureBrush`](../texturebrush)classe che utilizza l'immagine, la modalità di avvolgimento e il rettangolo di delimitazione specificati. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [Image](../../aspose.psd.brushes/texturebrush/image) { get; } | Ottiene il[`Image`](../../aspose.psd/image) oggetto associato a questo[`TextureBrush`](../texturebrush) oggetto. |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes) { get; } | Ottiene il[`ImageAttributes`](./imageattributes) associato a questo[`TextureBrush`](../texturebrush) . |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle) { get; } | Ottiene il[`Rectangle`](../../aspose.psd/rectangle) associato a questo[`TextureBrush`](../texturebrush) . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged) { get; } | Ottiene un valore che indica se le trasformazioni sono state modificate in qualche modo. Ad esempio, impostando la matrice di trasformazione o chiamando uno qualsiasi dei metodi che alterano la matrice di trasformazione. La proprietà è stata introdotta per la compatibilità con le versioni precedenti con GDI+. |
| [Opacity](../../aspose.psd/brush/opacity) { get; set; } | Ottiene o imposta l'opacità del pennello. Il valore deve essere compreso tra 0 e 1. Il valore 0 significa che il pennello è completamente visibile, il valore 1 significa che il pennello è completamente opaco. |
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

### Guarda anche

* class [TransformBrush](../transformbrush)
* spazio dei nomi [Aspose.PSD.Brushes](../../aspose.psd.brushes)
* assemblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
