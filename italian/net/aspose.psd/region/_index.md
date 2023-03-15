---
title: Class Region
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.Region classe. Descrive linterno di una forma grafica composta da rettangoli e tracciati. Questa classe non può essere ereditata.
type: docs
weight: 5360
url: /it/net/aspose.psd/region/
---
## Region class

Descrive l'interno di una forma grafica composta da rettangoli e tracciati. Questa classe non può essere ereditata.

```csharp
public sealed class Region
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Region](region/#constructor)() | Inizializza un nuovo`Region` . |
| [Region](region/#constructor_1)(GraphicsPath) | Inizializza un nuovo`Region` con quanto specificato[`GraphicsPath`](../graphicspath/) . |
| [Region](region/#constructor_2)(Rectangle) | Inizializza un nuovo`Region` da quanto specificato[`Rectangle`](../rectangle/)struttura. |
| [Region](region/#constructor_3)(RectangleF) | Inizializza un nuovo`Region` da quanto specificato[`RectangleF`](../rectanglef/)struttura. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Complement](../../aspose.psd/region/complement/#complement)(GraphicsPath) | Aggiorna questo`Region` per contenere la parte del specificato[`GraphicsPath`](../graphicspath/) che non si interseca con questo`Region` . |
| [Complement](../../aspose.psd/region/complement/#complement_1)(Rectangle) | Aggiorna questo`Region` per contenere la parte del specificato[`Rectangle`](../rectangle/) struttura che non si interseca con questa`Region` . |
| [Complement](../../aspose.psd/region/complement/#complement_2)(RectangleF) | Aggiorna questo`Region` per contenere la parte del specificato[`RectangleF`](../rectanglef/) struttura che non si interseca con questa`Region` . |
| [Complement](../../aspose.psd/region/complement/#complement_3)(Region) | Aggiorna questo`Region` per contenere la parte del specificato`Region` che non si interseca con questo`Region` . |
| [DeepClone](../../aspose.psd/region/deepclone/)() | Crea una copia profonda esatta di questo`Region` . |
| [Equals](../../aspose.psd/region/equals/#equals)(Region, Graphics) | Verifica se specificato`Region` è identico a questo`Region` sulla superficie di disegno specificata. |
| [Exclude](../../aspose.psd/region/exclude/#exclude)(GraphicsPath) | Aggiorna questo`Region` contenere solo la parte del suo interno che non si interseca con lo specificato[`GraphicsPath`](../graphicspath/) . |
| [Exclude](../../aspose.psd/region/exclude/#exclude_1)(Rectangle) | Aggiorna questo`Region` contenere solo la parte del suo interno che non si interseca con lo specificato[`Rectangle`](../rectangle/)struttura. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_2)(RectangleF) | Aggiorna questo`Region` contenere solo la parte del suo interno che non si interseca con lo specificato[`RectangleF`](../rectanglef/)struttura. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_3)(Region) | Aggiorna questo`Region` contenere solo la parte del suo interno che non si interseca con lo specificato`Region` . |
| [Intersect](../../aspose.psd/region/intersect/#intersect)(GraphicsPath) | Aggiorna questo`Region` all'intersezione di se stesso con lo specificato[`GraphicsPath`](../graphicspath/) . |
| [Intersect](../../aspose.psd/region/intersect/#intersect_1)(Rectangle) | Aggiorna questo`Region` all'intersezione di se stesso con lo specificato[`Rectangle`](../rectangle/)struttura. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_2)(RectangleF) | Aggiorna questo`Region` all'intersezione di se stesso con lo specificato[`RectangleF`](../rectanglef/)struttura. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_3)(Region) | Aggiorna questo`Region` all'intersezione di se stesso con lo specificato`Region` . |
| [IsEmpty](../../aspose.psd/region/isempty/)(Graphics) | Verifica se this`Region` ha un interno vuoto sulla superficie di disegno specificata. |
| [IsInfinite](../../aspose.psd/region/isinfinite/)(Graphics) | Verifica se this`Region` ha un interno infinito sulla superficie di disegno specificata. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible)(Point) | Verifica se specificato[`Point`](../point/) struttura è contenuta all'interno di questo`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_2)(PointF) | Verifica se specificato[`PointF`](../pointf/) struttura è contenuta all'interno di questo`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_4)(Rectangle) | Verifica se qualsiasi parte dell'oggetto specificato[`Rectangle`](../rectangle/) struttura è contenuta all'interno di questo`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_6)(RectangleF) | Verifica se qualsiasi parte dell'oggetto specificato[`RectangleF`](../rectanglef/) struttura è contenuta all'interno di questo`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_11)(float, float) | Verifica se il punto specificato è contenuto all'interno di questo`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_1)(Point, Graphics) | Verifica se specificato[`Point`](../point/) struttura è contenuta all'interno di questo`Region` quando disegnato utilizzando il file specificato[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_3)(PointF, Graphics) | Verifica se specificato[`PointF`](../pointf/) struttura è contenuta all'interno di questo`Region` quando disegnato utilizzando il file specificato[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_5)(Rectangle, Graphics) | Verifica se qualsiasi parte dell'oggetto specificato[`Rectangle`](../rectangle/) struttura è contenuta all'interno di questo`Region` quando disegnato utilizzando il file specificato[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_7)(RectangleF, Graphics) | Verifica se qualsiasi parte dell'oggetto specificato[`RectangleF`](../rectanglef/) struttura è contenuta all'interno di questo`Region` quando disegnato utilizzando il file specificato[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_12)(float, float, Graphics) | Verifica se il punto specificato è contenuto all'interno di questo`Region` quando disegnato utilizzando il file specificato[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_8)(int, int, Graphics) | Verifica se il punto specificato è contenuto all'interno di questo`Region` oggetto quando viene disegnato utilizzando l'oggetto specificato[`Graphics`](../graphics/) oggetto. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_13)(float, float, float, float) | Verifica se una qualsiasi parte del rettangolo specificato è contenuta all'interno di questo`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_9)(int, int, int, int) | Verifica se una qualsiasi parte del rettangolo specificato è contenuta all'interno di questo`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_14)(float, float, float, float, Graphics) | Verifica se una qualsiasi parte del rettangolo specificato è contenuta all'interno di questo`Region` quando disegnato utilizzando il file specificato[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_10)(int, int, int, int, Graphics) | Verifica se una qualsiasi parte del rettangolo specificato è contenuta all'interno di questo`Region` quando disegnato utilizzando il file specificato[`Graphics`](../graphics/) . |
| [MakeEmpty](../../aspose.psd/region/makeempty/)() | Inizializza questo`Region` a un interno vuoto. |
| [MakeInfinite](../../aspose.psd/region/makeinfinite/)() | Inizializza questo`Region` oggetto a un interno infinito. |
| [Transform](../../aspose.psd/region/transform/)(Matrix) | Trasforma questo`Region` da quanto specificato[`Matrix`](../matrix/) . |
| [Translate](../../aspose.psd/region/translate/#translate_1)(float, float) | Sposta le coordinate di questo`Region`dell'importo specificato. |
| [Translate](../../aspose.psd/region/translate/#translate)(int, int) | Sposta le coordinate di questo`Region`dell'importo specificato. |
| [Union](../../aspose.psd/region/union/#union)(GraphicsPath) | Aggiorna questo`Region` all'unione di se stesso e del specificato[`GraphicsPath`](../graphicspath/) . |
| [Union](../../aspose.psd/region/union/#union_1)(Rectangle) | Aggiorna questo`Region` all'unione di se stesso e del specificato[`Rectangle`](../rectangle/)struttura. |
| [Union](../../aspose.psd/region/union/#union_2)(RectangleF) | Aggiorna questo`Region` all'unione di se stesso e del specificato[`RectangleF`](../rectanglef/)struttura. |
| [Union](../../aspose.psd/region/union/#union_3)(Region) | Aggiorna questo`Region` all'unione di se stesso e del specificato`Region` . |
| [Xor](../../aspose.psd/region/xor/#xor)(GraphicsPath) | Aggiorna questo`Region` all'unione meno l'intersezione di se stesso con lo specificato[`GraphicsPath`](../graphicspath/) . |
| [Xor](../../aspose.psd/region/xor/#xor_1)(Rectangle) | Aggiorna questo`Region` all'unione meno l'intersezione di se stesso con lo specificato[`Rectangle`](../rectangle/)struttura. |
| [Xor](../../aspose.psd/region/xor/#xor_2)(RectangleF) | Aggiorna questo`Region` all'unione meno l'intersezione di se stesso con lo specificato[`RectangleF`](../rectanglef/)struttura. |
| [Xor](../../aspose.psd/region/xor/#xor_3)(Region) | Aggiorna questo`Region` all'unione meno l'intersezione di se stesso con lo specificato`Region` . |

### Guarda anche

* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


