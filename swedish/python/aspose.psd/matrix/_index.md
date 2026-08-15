---
title: "Matrix-klass"
type: docs
weight: 3000
url: /sv/python-net/aspose.psd/matrix/
---

**Summary:** Replaces the GDI+ Matrix.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Matrix

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [Matrix()](#Matrix__1) | Initierar en ny instans av Matrix-klassen som identitetsmatrisen. |
| [Matrix(m11, m12, m21, m22, m31, m32)](#Matrix_m11_m12_m21_m22_m31_m32_2) | Initierar en ny instans av klassen [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [Matrix(origin)](#Matrix_origin_3) | Skapar en kopia av klassen [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_4) | Initierar en ny instans av klassen [Matrix](/psd/python-net/aspose.psd/matrix/) till den geometriska transformationen som definieras av den angivna rektangeln och punktarrayen. |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_5) | Initierar en ny instans av klassen [Matrix](/psd/python-net/aspose.psd/matrix/) till den geometriska transformationen som definieras av den angivna rektangeln och punktarrayen. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| TYPE_FLIP [static] | int | r | Denna flaggbits indikerar att den transformation som definieras av detta objekt<br/>            utför en spegelvändning kring någon axel som förändrar det<br/>            normalt högervriddna koordinatsystemet till ett vänstervridd<br/>            system utöver de konverteringar som anges av andra flaggbitar.<br/>            Ett högervridet koordinatsystem är ett där den positiva X<br/>            axeln roterar moturs för att överlappa den positiva Y-axeln<br/>            liknande den riktning som fingrarna på din högra hand<br/>            kröker sig när du tittar rakt på tummen.<br/>            Ett vänstervridet koordinatsystem är ett där den positiva X<br/>            axeln roterar medurs för att överlappa den positiva Y-axeln liknande<br/>            den riktning som fingrarna på din vänstra hand kröker sig.<br/>            Det finns inget matematiskt sätt att bestämma vinkeln för den<br/>            ursprungliga vändnings- eller speglingstransformeringen eftersom alla vinklar<br/>            av vändning är identiska givet en lämplig justerande rotation.<br/>            OBS: TypeFlip lades till efter att GENERAL_TRANSFORM var i offentlig<br/>            cirkulation och flaggbitarna kunde inte längre renumreras på ett bekvämt<br/>            sätt utan att introducera binär inkompatibilitet i extern<br/>            kod. |
| TYPE_GENERAL_ROTATION [static] | int | r | Denna flaggbits indikerar att den transformation som definieras av detta objekt<br/>            utför en rotation med en godtycklig vinkel utöver de<br/>            konverteringar som anges av andra flaggbitar.<br/>            En rotation ändrar vektorns vinklar med samma mängd<br/>            oavsett vektorns ursprungliga riktning och utan att<br/>            förändra vektorns längd.<br/>            Denna flaggbits är ömsesidigt uteslutande med den |
| TYPE_GENERAL_SCALE [static] | int | r | En allmän skalning multiplicerar längden på vektorer med olika<br/>            mängder i x- och y-riktningarna utan att ändra vinkeln<br/>            mellan ortogonala vektorer.<br/>            Denna flaggbits är ömsesidigt uteslutande med flaggan TypeUniformScale. |
| TYPE_GENERAL_TRANSFORM [static] | int | r | Denna konstant indikerar att den transformation som definieras av detta objekt<br/>            utför en godtycklig konvertering av inmatningskoordinaterna.<br/>            Om denna transformation kan klassificeras av någon av ovanstående konstanter,<br/>            kommer typen antingen att vara konstanten TypeIdentity eller en<br/>            kombination av de lämpliga flaggbitarna för de olika koordinat<br/>            konverteringarna som denna transformation utför. |
| TYPE_IDENTITY [static] | int | r | En identitetstransform är en där utdata-koordinaterna alltid är desamma som indata-koordinaterna.<br/>            Om denna transform är något annat än identitetstransformen,<br/>            kommer typen antingen att vara konstanten GENERAL_TRANSFORM eller en<br/>            kombination av de lämpliga flaggbitarna för de olika koordinat<br/>            konverteringarna som denna transform utför. |
| TYPE_MASK_ROTATION [static] | int | r | Denna konstant är en bitmask för någon av rotationsflaggbitarna. |
| TYPE_MASK_SCALE [static] | int | r | Denna konstant är en bitmask för någon av skalningsflaggbitarna. |
| TYPE_QUADRANT_ROTATION [static] | int | r | Denna flaggbit indikerar att transformen som definieras av detta objekt<br/>            utför en kvadrantrotation med någon multipel av 90 grader i<br/>            tillägg till de konverteringar som anges av andra flaggbitar.<br/>            En rotation förändrar vektorns vinklar med samma mängd<br/>            oavsett den ursprungliga riktningen på vektorn och utan<br/>            att förändra vektorns längd.<br/>            Denna flaggbit är ömsesidigt uteslutande med flaggan TypeGeneralRotation. |
| TYPE_TRANSLATION [static] | int | r | En translation flyttar koordinaterna med ett konstant värde i x<br/>            och y utan att förändra vektorns längd eller vinkel. |
| TYPE_UNIFORM_SCALE [static] | int | r | En enhetlig skalning multiplicerar vektorns längd med samma mängd<br/>            i både x- och y-riktningarna utan att förändra vinkeln mellan<br/>            vektorer.<br/>            Denna flaggbit är ömsesidigt uteslutande med flaggan TypeGeneralScale. |
| elements | float | r | Hämtar en array av flyttal som representerar elementen i denna [Matrix](/psd/python-net/aspose.psd/matrix/). |
| m11 | float | r | Hämtar matriselementet i första raden första kolumnen. Representerar skalning längs X-axeln. |
| m12 | float | r | Hämtar matriselementet i första raden andra kolumnen. Representerar skevning längs Y-axeln. |
| m21 | float | r | Hämtar matriselementet i andra raden första kolumnen. Representerar skevning längs X-axeln. |
| m22 | float | r | Hämtar matriselementet i andra raden andra kolumnen. Representerar skalning längs Y-axeln. |
| m31 | float | r | Hämtar matriselementet i tredje raden första kolumnen. Representerar translation längs X-axeln. |
| m32 | float | r | Hämtar matriselementet i tredje raden första kolumnen. Representerar translation längs Y-axeln. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_elements()](#get_elements__1) | Hämtar en kopia av matrisens element. |
| [multiply(tx)](#multiply_tx_2) | Multiplicerar denna Matrix med matrisen som anges i matrix‑parametern med (standard) Prepend‑ordning. |
| [multiply(tx, order)](#multiply_tx_order_3) | Multiplicerar denna Matrix med matrisen som anges i matrix‑parametern, och i den ordning som anges i order‑parametern. |
| reset() | Återställer denna Matrix så att den har elementen i identitetsmatrisen. |
| [rotate(angle)](#rotate_angle_4) | Tillämpar en medursrotation med ett värde som anges i vinkel‑parametern, runt origo (noll x‑ och y‑koordinater) för denna Matrix i standard (Prepend)-ordning. |
| [rotate(angle, order)](#rotate_angle_order_5) | Tillämpar en medursrotation med ett värde som anges i vinkel‑parametern, runt origo (noll x‑ och y‑koordinater) för denna Matrix i den angivna ordningen. |
| [rotate_at(angle, point)](#rotate_at_angle_point_6) | Tillämpar en medursrotation kring den angivna punkten på denna Matrix i standard (Prepend)-ordning. |
| [rotate_at(angle, point, order)](#rotate_at_angle_point_order_7) | Tillämpar en medursrotation kring den angivna punkten på denna Matrix i den angivna ordningen. |
| [scale(scale_x, scale_y, order)](#scale_scale_x_scale_y_order_8) | Tillämpar den angivna skalvektorn (scaleX och scaleY) på denna [Matrix](/psd/python-net/aspose.psd/matrix/) med den angivna ordningen. |
| [scale(sx, sy)](#scale_sx_sy_9) | Tillämpar den angivna skalvektorn (scaleX och scaleY) på denna Matrix med (standard) Prepend‑ordning. |
| [transform_points(points)](#transform_points_points_10) | Tillämpar den geometriska transformen som representeras av denna [Matrix](/psd/python-net/aspose.psd/matrix/) på en angiven punktarray. |
| [translate(offset_x, offset_y, order)](#translate_offset_x_offset_y_order_11) | Tillämpar den angivna translationsvektorn på denna Matrix i den angivna ordningen. |
| [translate(tx, ty)](#translate_tx_ty_12) | Tillämpar den angivna translationsvektorn på denna [Matrix](/psd/python-net/aspose.psd/matrix/) med (standard) Prepend‑ordning. |


### Constructor: Matrix() {#Matrix__1}


```
 Matrix() 
```

Initierar en ny instans av Matrix-klassen som identitetsmatrisen.

### Constructor: Matrix(m11, m12, m21, m22, m31, m32) {#Matrix_m11_m12_m21_m22_m31_m32_2}


```
 Matrix(m11, m12, m21, m22, m31, m32) 
```

Initierar en ny instans av klassen [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| m11 | float | m00     M11     Skala X |
| m12 | float | m10     M12     Skev Y |
| m21 | float | m01     M21     Skev X |
| m22 | float | m11     M22     Skala Y |
| m31 | float | m02     M31     Translera X |
| m32 | float | m12     M32     Translera Y |

### Constructor: Matrix(origin) {#Matrix_origin_3}


```
 Matrix(origin) 
```

Skapar en kopia av klassen [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| origin | [Matrix](/psd/python-net/aspose.psd/matrix) | En basmatris för coping |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_4}


```
 Matrix(rect, plgpts) 
```

Initierar en ny instans av klassen [Matrix](/psd/python-net/aspose.psd/matrix/) till den geometriska transformationen som definieras av den angivna rektangeln och punktarrayen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | En [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som representerar rektangeln som ska transformeras. |
| plgpts | [PointF[]](/psd/python-net/aspose.psd/pointf) | En array av tre [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som representerar punkterna i ett parallellogram till vilket det övre vänstra, övre högra och nedre vänstra hörnet av rektangeln ska transformeras. Det nedre högra hörnet av parallellogrammet är underförstått av de första tre hörnen. |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_5}


```
 Matrix(rect, plgpts) 
```

Initierar en ny instans av klassen [Matrix](/psd/python-net/aspose.psd/matrix/) till den geometriska transformationen som definieras av den angivna rektangeln och punktarrayen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | En [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som representerar rektangeln som ska transformeras. |
| plgpts | [Point[]](/psd/python-net/aspose.psd/point) | En array av tre [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som representerar punkterna i ett parallellogram till vilket det övre vänstra, övre högra och nedre vänstra hörnet av rektangeln ska transformeras. Det nedre högra hörnet av parallellogrammet är underförstått av de första tre hörnen. |

### Method: get_elements() {#get_elements__1}


```
 get_elements() 
```

Hämtar en kopia av matrisens element.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| float | En kopia av matrisens element. |


### Method: multiply(tx) {#multiply_tx_2}


```
 multiply(tx) 
```

Multiplicerar denna Matrix med matrisen som anges i matrix‑parametern med (standard) Prepend‑ordning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | Matrisen att multiplicera med. |

### Method: multiply(tx, order) {#multiply_tx_order_3}


```
 multiply(tx, order) 
```

Multiplicerar denna Matrix med matrisen som anges i matrix‑parametern, och i den ordning som anges i order‑parametern.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | Tx‑värdet. Tx‑värdet. Tx‑värdet. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ordningen. Ordningen. Ordningen. |

### Method: rotate(angle) {#rotate_angle_4}


```
 rotate(angle) 
```

Tillämpar en medursrotation med ett värde som anges i vinkel‑parametern, runt origo (noll x‑ och y‑koordinater) för denna Matrix i standard (Prepend)-ordning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln. |

### Method: rotate(angle, order) {#rotate_angle_order_5}


```
 rotate(angle, order) 
```

Tillämpar en medursrotation med ett värde som anges i vinkel‑parametern, runt origo (noll x‑ och y‑koordinater) för denna Matrix i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Matrisordningen. |

### Method: rotate_at(angle, point) {#rotate_at_angle_point_6}


```
 rotate_at(angle, point) 
```

Tillämpar en medursrotation kring den angivna punkten på denna Matrix i standard (Prepend)-ordning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Vinkeln. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Punkten. |

### Method: rotate_at(angle, point, order) {#rotate_at_angle_point_order_7}


```
 rotate_at(angle, point, order) 
```

Tillämpar en medursrotation kring den angivna punkten på denna Matrix i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Vinkeln. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Punkten. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ordningen. |

### Method: scale(scale_x, scale_y, order) {#scale_scale_x_scale_y_order_8}


```
 scale(scale_x, scale_y, order) 
```

Tillämpar den angivna skalvektorn (scaleX och scaleY) på denna [Matrix](/psd/python-net/aspose.psd/matrix/) med den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scale_x | float | Skalan X. |
| scale_y | float | Skalan Y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ordningen. |

### Method: scale(sx, sy) {#scale_sx_sy_9}


```
 scale(sx, sy) 
```

Tillämpar den angivna skalvektorn (scaleX och scaleY) på denna Matrix med (standard) Prepend‑ordning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sx | float | sx. sx. sx. |
| sy | float | sy. sy. sy. |

### Method: transform_points(points) {#transform_points_points_10}


```
 transform_points(points) 
```

Tillämpar den geometriska transformen som representeras av denna [Matrix](/psd/python-net/aspose.psd/matrix/) på en angiven punktarray.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Punkterna. |

### Method: translate(offset_x, offset_y, order) {#translate_offset_x_offset_y_order_11}


```
 translate(offset_x, offset_y, order) 
```

Tillämpar den angivna translationsvektorn på denna Matrix i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| offset_x | float | Offset X. |
| offset_y | float | Offset Y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ordningen. |

### Method: translate(tx, ty) {#translate_tx_ty_12}


```
 translate(tx, ty) 
```

Tillämpar den angivna translationsvektorn på denna [Matrix](/psd/python-net/aspose.psd/matrix/) med (standard) Prepend‑ordning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tx | float | Tx‑värdet. Tx‑värdet. Tx‑värdet. |
| ty | float | ty. ty. ty. |

