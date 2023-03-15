---
title: Class Matrix
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.Matrix classe. Sostituisce la matrice GDI.
type: docs
weight: 5090
url: /it/net/aspose.psd/matrix/
---
## Matrix class

Sostituisce la matrice GDI+.

```csharp
public class Matrix
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Matrix](matrix/#constructor)() | Inizializza una nuova istanza della classe Matrix come matrice identità. |
| [Matrix](matrix/#constructor_1)(Matrix) | Crea una copia del file`Matrix` classe. |
| [Matrix](matrix/#constructor_2)(Rectangle, Point[]) | Inizializza una nuova istanza di`Matrix` class alla trasformazione geometrica definita dal rettangolo e dall'array di punti specificati. |
| [Matrix](matrix/#constructor_3)(RectangleF, PointF[]) | Inizializza una nuova istanza di`Matrix` class alla trasformazione geometrica definita dal rettangolo e dall'array di punti specificati. |
| [Matrix](matrix/#constructor_4)(float, float, float, float, float, float) | Inizializza una nuova istanza di`Matrix` classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Elements](../../aspose.psd/matrix/elements/) { get; } | Ottiene una matrice di valori a virgola mobile che rappresenta gli elementi di this`Matrix` . |
| [M11](../../aspose.psd/matrix/m11/) { get; } | Ottiene l'elemento della matrice nella prima riga prima colonna. Rappresenta la scala lungo l'asse X. |
| [M12](../../aspose.psd/matrix/m12/) { get; } | Ottiene l'elemento della matrice nella prima riga della seconda colonna. Rappresenta il taglio lungo l'asse Y. |
| [M21](../../aspose.psd/matrix/m21/) { get; } | Ottiene l'elemento della matrice nella prima riga della seconda colonna. Rappresenta il taglio lungo l'asse X. |
| [M22](../../aspose.psd/matrix/m22/) { get; } | Ottiene l'elemento della matrice nella seconda riga della seconda colonna. Rappresenta la scala lungo l'asse Y. |
| [M31](../../aspose.psd/matrix/m31/) { get; } | Ottiene l'elemento della matrice nella prima colonna della terza riga. Rappresenta la traslazione lungo l'asse X. |
| [M32](../../aspose.psd/matrix/m32/) { get; } | Ottiene l'elemento della matrice nella prima colonna della terza riga. Rappresenta la traslazione lungo l'asse Y. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Equals](../../aspose.psd/matrix/equals/)(object) | Determina se specificatoObject è uguale a questa istanza. |
| [GetElements](../../aspose.psd/matrix/getelements/)() | Ottiene la copia degli elementi della matrice. |
| override [GetHashCode](../../aspose.psd/matrix/gethashcode/)() | Restituisce un codice hash per questa istanza. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply)(Matrix) | Moltiplica questa matrice per la matrice specificata nel parametro matrice utilizzando (predefinito) Prepend order. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply_1)(Matrix, MatrixOrder) | Moltiplica questa matrice per la matrice specificata nel parametro matrice e nell'ordine specificato nel parametro ordine. |
| [Reset](../../aspose.psd/matrix/reset/)() | Reimposta questa matrice per avere gli elementi della matrice identità. |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate)(float) | Applica una rotazione in senso orario di una quantità specificata nel parametro angolo, attorno all'origine (zero coordinate x e y) per questa matrice nell'ordine predefinito (Prepend). |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate_1)(float, MatrixOrder) | Applica una rotazione in senso orario di una quantità specificata nel parametro angolo, attorno all'origine (zero coordinate x e y) per questa matrice nell'ordine specificato. |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat)(float, PointF) | Applica una rotazione in senso orario attorno al punto specificato a questa matrice nell'ordine predefinito (prepend). |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat_1)(float, PointF, MatrixOrder) | Applica una rotazione in senso orario attorno al punto specificato a questa matrice nell'ordine specificato. |
| [Scale](../../aspose.psd/matrix/scale/#scale)(float, float) | Applica il vettore di scala specificato (scaleX e scaleY) a questa matrice utilizzando (predefinito) Prepend order. |
| [Scale](../../aspose.psd/matrix/scale/#scale_1)(float, float, MatrixOrder) | Applica a questo il vettore di scala specificato (scaleX e scaleY).`Matrix` utilizzando l'ordine specificato. |
| override [ToString](../../aspose.psd/matrix/tostring/)() | Restituisce aString che rappresenta questa istanza. |
| [TransformPoints](../../aspose.psd/matrix/transformpoints/)(PointF[]) | Applica la trasformazione geometrica rappresentata da this`Matrix` a una matrice di punti specificata. |
| [Translate](../../aspose.psd/matrix/translate/#translate)(float, float) | Applica a questo il vettore di traduzione specificato`Matrix` utilizzando (predefinito) Anteponi ordine. |
| [Translate](../../aspose.psd/matrix/translate/#translate_1)(float, float, MatrixOrder) | Applica il vettore di traslazione specificato a questa matrice nell'ordine specificato. |
| static [Equals](../../aspose.psd/matrix/equals/)(Matrix, Matrix) | Determina se due matrici sono uguali. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [TypeFlip](../../aspose.psd/matrix/typeflip/) | Questo flag bit indica che la trasformazione definita da questo oggetto esegue un'immagine speculare capovolta attorno ad un asse che cambia il sistema di coordinate normalmente destrorso in un sistema mancino oltre alle conversioni indicate da altri flag bit. Un sistema di coordinate destrorso è quello in cui l'asse X positivo ruota in senso antiorario per sovrapporsi all'asse Y positivo simile alla direzione in cui le dita della tua mano destra si arricciano quando fissi il pollice. Un sistema di coordinate mancino è quello in cui ruota l'asse X positivo in senso orario per sovrapporre l'asse Y positivo simile alla direzione in cui si arricciano le dita della mano sinistra. Non esiste un modo matematico per determinare l'angolo del originale capovolgimento o trasformazione speculare poiché tutti gli angoli del capovolgimento sono identici data un'appropriata rotazione di regolazione. NOTA: TypeFlip è stato aggiunto dopo GENERAL_TRANSFORM era in public circolazione e i flag bit non potevano più essere convenientemente rinumerati senza introdurre incompatibilità binaria nel codice outside . |
| const [TypeGeneralRotation](../../aspose.psd/matrix/typegeneralrotation/) | Questo flag bit indica che la trasformazione definita da questo oggetto esegue una rotazione di un angolo arbitrario oltre alle conversioni indicate da altri flag bit. Una rotazione modifica gli angoli dei vettori della stessa quantità indipendentemente dalla direzione originale del vettore e senza cambiare la lunghezza del vettore. Questo flag bit si esclude a vicenda con the |
| const [TypeGeneralScale](../../aspose.psd/matrix/typegeneralscale/) | Una scala generale moltiplica la lunghezza dei vettori per diverse quantità nelle direzioni x e y senza modificare l'angolo tra i vettori perpendicolari. Questo flag bit si esclude a vicenda con il flag TypeUniformScale. |
| const [TypeGeneralTransform](../../aspose.psd/matrix/typegeneraltransform/) | Questa costante indica che la trasformazione definita da questo oggetto esegue una conversione arbitraria delle coordinate di input. Se questa trasformazione può essere classificata da una qualsiasi delle costanti di cui sopra, il tipo sarà la costante TypeIdentity o una combinazione del flag appropriato bit per le varie conversioni di coordinate eseguite da questa trasformazione. |
| const [TypeIdentity](../../aspose.psd/matrix/typeidentity/) | Una trasformazione di identità è quella in cui le coordinate di output sono sempre le stesse delle coordinate di input. Se questa trasformazione è qualcosa di diverso dalla trasformazione di identità, il tipo sarà la costante GENERAL_TRANSFORM o una combinazione dei bit flag appropriati per le varie conversioni di coordinate eseguite da questa trasformazione. |
| const [TypeMaskRotation](../../aspose.psd/matrix/typemaskrotation/) | Questa costante è una maschera di bit per qualsiasi bit del flag di rotazione. |
| const [TypeMaskScale](../../aspose.psd/matrix/typemaskscale/) | Questa costante è una maschera di bit per qualsiasi bit del flag di scala. |
| const [TypeQuadrantRotation](../../aspose.psd/matrix/typequadrantrotation/) | Questo flag bit indica che la trasformazione definita da questo oggetto esegue una rotazione del quadrante di qualche multiplo di 90 gradi in oltre alle conversioni indicate da altri flag bit. Una rotazione modifica gli angoli dei vettori della stessa quantità indipendentemente dalla direzione originale del vettore e senza modificare la lunghezza del vettore. Questo flag bit si esclude a vicenda con il flag TypeGeneralRotation. |
| const [TypeTranslation](../../aspose.psd/matrix/typetranslation/) | Una traslazione sposta le coordinate di una quantità costante in x e y senza modificare la lunghezza o l'angolo dei vettori. |
| const [TypeUniformScale](../../aspose.psd/matrix/typeuniformscale/) | Una scala uniforme moltiplica la lunghezza dei vettori per la stessa quantità in entrambe le direzioni x e y senza modificare l'angolo tra vettori. Questo flag bit si esclude a vicenda con il flag TypeGeneralScale. |

### Osservazioni

La maggior parte degli algoritmi presi da AffineTransform.java di Sun. Nomi di Java per gli elementi della matrice usati internamente. Mappa dei nomi java in quelli .net alla descrizione: m00 M11 Scala X m10 M12 Taglio Y m01 M21 Taglio X m11 M203 Scala Y_x02 M01 Traduci X m12 M32 Traduci Y

### Guarda anche

* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


