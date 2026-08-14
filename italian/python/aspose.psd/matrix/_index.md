---
title: "Classe Matrix"
type: docs
weight: 3000
url: /it/python-net/aspose.psd/matrix/
---

**Summary:** Replaces the GDI+ Matrix.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Matrix

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Matrix()](#Matrix__1) | Inizializza una nuova istanza della classe Matrix come matrice identità. |
| [Matrix(m11, m12, m21, m22, m31, m32)](#Matrix_m11_m12_m21_m22_m31_m32_2) | Inizializza una nuova istanza della classe [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [Matrix(origin)](#Matrix_origin_3) | Crea una copia della classe [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_4) | Inizializza una nuova istanza della classe [Matrix](/psd/python-net/aspose.psd/matrix/) alla trasformazione geometrica definita dal rettangolo specificato e dall'array di punti. |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_5) | Inizializza una nuova istanza della classe [Matrix](/psd/python-net/aspose.psd/matrix/) alla trasformazione geometrica definita dal rettangolo specificato e dall'array di punti. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| TYPE_FLIP [static] | int | r | Questo bit di flag indica che la trasformazione definita da questo oggetto<br/> esegue un ribaltamento a immagine speculare attorno a qualche asse che trasforma il<br/> normale sistema di coordinate destro in un sistema di coordinate sinistro<br/> oltre alle conversioni indicate da altri bit di flag.<br/> Un sistema di coordinate destro è quello in cui l'asse X positivo<br/> ruota in senso antiorario per sovrapporsi all'asse Y positivo<br/> simile alla direzione in cui le dita della tua mano destra<br/> si avvolgono quando guardi di profilo il tuo pollice.<br/> Un sistema di coordinate sinistro è quello in cui l'asse X positivo<br/> ruota in senso orario per sovrapporsi all'asse Y positivo simile<br/> alla direzione in cui le dita della tua mano sinistra si avvolgono.<br/> Non esiste un modo matematico per determinare l'angolo della<br/> trasformazione originale di ribaltamento o specchiatura poiché tutti gli angoli<br/> di ribaltamento sono identici dato un'adeguata rotazione di aggiustamento.<br/> NOTA: TypeFlip è stato aggiunto dopo che GENERAL_TRANSFORM era in pubblico<br/> circolazione e i bit di flag non potevano più essere rinumerati comodamente<br/> senza introdurre incompatibilità binaria nel codice esterno. |
| TYPE_GENERAL_ROTATION [static] | int | r | Questo bit di flag indica che la trasformazione definita da questo oggetto<br/> esegue una rotazione di un angolo arbitrario oltre alle<br/> conversioni indicate da altri bit di flag.<br/> Una rotazione cambia gli angoli dei vettori della stessa quantità<br/> indipendentemente dalla direzione originale del vettore e senza<br/> modificare la lunghezza del vettore.<br/> Questo bit di flag è mutuamente esclusivo con il |
| TYPE_GENERAL_SCALE [static] | int | r | Una scala generale moltiplica la lunghezza dei vettori di valori diversi<br/> nelle direzioni x e y senza cambiare l'angolo<br/> tra vettori perpendicolari.<br/> Questo bit di flag è mutuamente esclusivo con il flag TypeUniformScale. |
| TYPE_GENERAL_TRANSFORM [static] | int | r | Questa costante indica che la trasformazione definita da questo oggetto<br/> esegue una conversione arbitraria delle coordinate di input.<br/> Se questa trasformazione può essere classificata da una delle costanti sopra,<br/> il tipo sarà o la costante TypeIdentity o una<br/> combinazione dei bit di flag appropriati per le varie conversioni di coordinate<br/> che questa trasformazione esegue. |
| TYPE_IDENTITY [static] | int | r | Una trasformazione identità è quella in cui le coordinate di output sono<br/> sempre le stesse delle coordinate di input.<br/> Se questa trasformazione è diversa dalla trasformazione identità,<br/> il tipo sarà o la costante GENERAL_TRANSFORM o una<br/> combinazione dei bit di flag appropriati per le varie conversioni di coordinate<br/> che questa trasformazione esegue. |
| TYPE_MASK_ROTATION [static] | int | r | Questa costante è una maschera di bit per qualsiasi dei bit di flag di rotazione. |
| TYPE_MASK_SCALE [static] | int | r | Questa costante è una maschera di bit per qualsiasi dei bit di flag di scala. |
| TYPE_QUADRANT_ROTATION [static] | int | r | Questo bit di flag indica che la trasformazione definita da questo oggetto<br/> esegue una rotazione di quadrante di un multiplo di 90 gradi in<br/> aggiunta alle conversioni indicate da altri bit di flag.<br/> Una rotazione cambia gli angoli dei vettori della stessa quantità<br/> indipendentemente dalla direzione originale del vettore e senza<br/> modificare la lunghezza del vettore.<br/> Questo bit di flag è mutuamente esclusivo con il flag TypeGeneralRotation. |
| TYPE_TRANSLATION [static] | int | r | Una traslazione sposta le coordinate di una quantità costante in x<br/> e y senza cambiare la lunghezza o l'angolo dei vettori. |
| TYPE_UNIFORM_SCALE [static] | int | r | Una scala uniforme moltiplica la lunghezza dei vettori della stessa quantità<br/>            in entrambe le direzioni x e y senza cambiare l'angolo tra<br/>            i vettori.<br/>            Questo bit di flag è mutuamente esclusivo con il flag TypeGeneralScale. |
| elements | float | r | Ottiene un array di valori a virgola mobile che rappresenta gli elementi di questa [Matrix](/psd/python-net/aspose.psd/matrix/). |
| m11 | float | r | Ottiene l'elemento della matrice alla prima riga prima colonna. Rappresenta la scala lungo l'asse X. |
| m12 | float | r | Ottiene l'elemento della matrice alla prima riga seconda colonna. Rappresenta lo shear lungo l'asse Y. |
| m21 | float | r | Ottiene l'elemento della matrice alla seconda riga prima colonna. Rappresenta lo shear lungo l'asse X. |
| m22 | float | r | Ottiene l'elemento della matrice alla seconda riga seconda colonna. Rappresenta la scala lungo l'asse Y. |
| m31 | float | r | Ottiene l'elemento della matrice alla terza riga prima colonna. Rappresenta la traslazione lungo l'asse X. |
| m32 | float | r | Ottiene l'elemento della matrice alla terza riga prima colonna. Rappresenta la traslazione lungo l'asse Y. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_elements()](#get_elements__1) | Ottiene una copia degli elementi della matrice. |
| [multiply(tx)](#multiply_tx_2) | Moltiplica questa Matrix per la matrice specificata nel parametro matrix usando l'ordine (predefinito) Prepend. |
| [multiply(tx, order)](#multiply_tx_order_3) | Moltiplica questa Matrix per la matrice specificata nel parametro matrix, nell'ordine specificato nel parametro order. |
| reset() | Reimposta questa Matrix affinché contenga gli elementi della matrice identità. |
| [rotate(angle)](#rotate_angle_4) | Applica una rotazione in senso orario di un valore specificato nel parametro angle, attorno all'origine (coordinate x e y zero) per questa Matrix nell'ordine predefinito (Prepend). |
| [rotate(angle, order)](#rotate_angle_order_5) | Applica una rotazione in senso orario di un valore specificato nel parametro angle, attorno all'origine (coordinate x e y zero) per questa Matrix nell'ordine specificato. |
| [rotate_at(angle, point)](#rotate_at_angle_point_6) | Applica una rotazione in senso orario intorno al punto specificato a questa Matrix nell'ordine predefinito (Prepend). |
| [rotate_at(angle, point, order)](#rotate_at_angle_point_order_7) | Applica una rotazione in senso orario intorno al punto specificato a questa Matrix nell'ordine specificato. |
| [scale(scale_x, scale_y, order)](#scale_scale_x_scale_y_order_8) | Applica il vettore di scala specificato (scaleX e scaleY) a questa [Matrix](/psd/python-net/aspose.psd/matrix/) usando l'ordine specificato. |
| [scale(sx, sy)](#scale_sx_sy_9) | Applica il vettore di scala specificato (scaleX e scaleY) a questa Matrix usando l'ordine (predefinito) Prepend. |
| [transform_points(points)](#transform_points_points_10) | Applica la trasformazione geometrica rappresentata da questa [Matrix](/psd/python-net/aspose.psd/matrix/) a un array di punti specificato. |
| [translate(offset_x, offset_y, order)](#translate_offset_x_offset_y_order_11) | Applica il vettore di traslazione specificato a questa Matrice nell'ordine specificato. |
| [translate(tx, ty)](#translate_tx_ty_12) | Applica il vettore di traslazione specificato a questa [Matrix](/psd/python-net/aspose.psd/matrix/) usando l'ordine Prepend (predefinito). |


### Constructor: Matrix() {#Matrix__1}


```
 Matrix() 
```

Inizializza una nuova istanza della classe Matrix come matrice identità.

### Constructor: Matrix(m11, m12, m21, m22, m31, m32) {#Matrix_m11_m12_m21_m22_m31_m32_2}


```
 Matrix(m11, m12, m21, m22, m31, m32) 
```

Inizializza una nuova istanza della classe [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| m11 | float | m00     M11     Scala X |
| m12 | float | m10     M12     Taglio Y |
| m21 | float | m01     M21     Taglio X |
| m22 | float | m11     M22     Scala Y |
| m31 | float | m02     M31     Trasla X |
| m32 | float | m12     M32     Trasla Y |

### Constructor: Matrix(origin) {#Matrix_origin_3}


```
 Matrix(origin) 
```

Crea una copia della classe [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| origin | [Matrix](/psd/python-net/aspose.psd/matrix) | Una matrice di base per la gestione |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_4}


```
 Matrix(rect, plgpts) 
```

Inizializza una nuova istanza della classe [Matrix](/psd/python-net/aspose.psd/matrix/) alla trasformazione geometrica definita dal rettangolo specificato e dall'array di punti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che rappresenta il rettangolo da trasformare. |
| plgpts | [PointF[]](/psd/python-net/aspose.psd/pointf) | Un array di tre strutture [PointF](/psd/python-net/aspose.psd/pointf/) che rappresentano i punti di un parallelogramma a cui devono essere trasformati gli angoli superiore sinistro, superiore destro e inferiore sinistro del rettangolo. L'angolo inferiore destro del parallelogramma è implicito nei primi tre angoli. |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_5}


```
 Matrix(rect, plgpts) 
```

Inizializza una nuova istanza della classe [Matrix](/psd/python-net/aspose.psd/matrix/) alla trasformazione geometrica definita dal rettangolo specificato e dall'array di punti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che rappresenta il rettangolo da trasformare. |
| plgpts | [Point[]](/psd/python-net/aspose.psd/point) | Un array di tre strutture [PointF](/psd/python-net/aspose.psd/pointf/) che rappresentano i punti di un parallelogramma a cui devono essere trasformati gli angoli superiore sinistro, superiore destro e inferiore sinistro del rettangolo. L'angolo inferiore destro del parallelogramma è implicito nei primi tre angoli. |

### Method: get_elements() {#get_elements__1}


```
 get_elements() 
```

Ottiene una copia degli elementi della matrice.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| float | Una copia degli elementi della matrice. |


### Method: multiply(tx) {#multiply_tx_2}


```
 multiply(tx) 
```

Moltiplica questa Matrix per la matrice specificata nel parametro matrix usando l'ordine (predefinito) Prepend.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | La matrice con cui moltiplicare. |

### Method: multiply(tx, order) {#multiply_tx_order_3}


```
 multiply(tx, order) 
```

Moltiplica questa Matrix per la matrice specificata nel parametro matrix, nell'ordine specificato nel parametro order.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | Il tx. Il tx. Il tx. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | L'ordine. L'ordine. L'ordine. |

### Method: rotate(angle) {#rotate_angle_4}


```
 rotate(angle) 
```

Applica una rotazione in senso orario di un valore specificato nel parametro angle, attorno all'origine (coordinate x e y zero) per questa Matrix nell'ordine predefinito (Prepend).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angolo | float | L'angolo di rotazione. |

### Method: rotate(angle, order) {#rotate_angle_order_5}


```
 rotate(angle, order) 
```

Applica una rotazione in senso orario di un valore specificato nel parametro angle, attorno all'origine (coordinate x e y zero) per questa Matrix nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angolo | float | L'angolo di rotazione. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | L'ordine della matrice. |

### Method: rotate_at(angle, point) {#rotate_at_angle_point_6}


```
 rotate_at(angle, point) 
```

Applica una rotazione in senso orario intorno al punto specificato a questa Matrix nell'ordine predefinito (Prepend).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angolo | float | L'angolo. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Il punto. |

### Method: rotate_at(angle, point, order) {#rotate_at_angle_point_order_7}


```
 rotate_at(angle, point, order) 
```

Applica una rotazione in senso orario intorno al punto specificato a questa Matrix nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angolo | float | L'angolo. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Il punto. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | L'ordine. |

### Method: scale(scale_x, scale_y, order) {#scale_scale_x_scale_y_order_8}


```
 scale(scale_x, scale_y, order) 
```

Applica il vettore di scala specificato (scaleX e scaleY) a questa [Matrix](/psd/python-net/aspose.psd/matrix/) usando l'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| scale_x | float | La scala X. |
| scale_y | float | La scala Y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | L'ordine. |

### Method: scale(sx, sy) {#scale_sx_sy_9}


```
 scale(sx, sy) 
```

Applica il vettore di scala specificato (scaleX e scaleY) a questa Matrix usando l'ordine (predefinito) Prepend.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sx | float | Il sx. Il sx. Il sx. |
| sy | float | Il sy. Il sy. Il sy. |

### Method: transform_points(points) {#transform_points_points_10}


```
 transform_points(points) 
```

Applica la trasformazione geometrica rappresentata da questa [Matrix](/psd/python-net/aspose.psd/matrix/) a un array di punti specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | I punti. |

### Method: translate(offset_x, offset_y, order) {#translate_offset_x_offset_y_order_11}


```
 translate(offset_x, offset_y, order) 
```

Applica il vettore di traslazione specificato a questa Matrice nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| offset_x | float | L'offset X. |
| offset_y | float | L'offset Y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | L'ordine. |

### Method: translate(tx, ty) {#translate_tx_ty_12}


```
 translate(tx, ty) 
```

Applica il vettore di traslazione specificato a questa [Matrix](/psd/python-net/aspose.psd/matrix/) usando l'ordine Prepend (predefinito).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tx | float | Il tx. Il tx. Il tx. |
| ty | float | Il ty. Il ty. Il ty. |

