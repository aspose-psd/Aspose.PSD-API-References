---
title: "Matrix"
second_title: "Aspose.PSD för Java API-referens"
description: "Ersätter GDI‑matrisen."
type: docs
weight: 69
url: /sv/java/com.aspose.psd/matrix/
---

**Inheritance:**
java.lang.Object
```
public class Matrix
```

Ersätter GDI+ Matrix.

De flesta algoritmer är hämtade från Suns AffineTransform.java. Javas namn för matriselement som används internt. Karta över java‑namn till .net‑namn med beskrivning: m00 M11 Skala X m10 M12 Skjuv Y m01 M21 Skjuv X m11 M22 Skala Y m02 M31 Översätt X m12 M32 Översätt Y
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Matrix()](#Matrix--) | Initierar en ny instans av Matrix‑klassen som identitetsmatris. |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | Initierar en ny instans av  Matrix  klassen. |
| [Matrix(Matrix origin)](#Matrix-com.aspose.psd.Matrix-) | Skapar en kopia av  Matrix  klassen. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---) | Initierar en ny instans av  Aspose.Imaging.Matrix  klassen till den geometriska transformen som definieras av den angivna rektangeln och punktarrayen. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---) | Initierar en ny instans av  Aspose.Imaging.Matrix  klassen till den geometriska transformen som definieras av den angivna rektangeln och punktarrayen. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [TYPE_FLIP](#TYPE-FLIP) | Denna flaggbit indikerar att den transformering som definieras av detta objekt utför en spegelvändning kring någon axel som förändrar det normala högra‑handade koordinatsystemet till ett vänster‑handat system, utöver de konverteringar som anges av andra flaggbitar. |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | Denna flaggbit indikerar att den transformering som definieras av detta objekt utför en rotation med en godtycklig vinkel, utöver de konverteringar som anges av andra flaggbitar. |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | En allmän skalning multiplicerar vektorlängden med olika faktorer i x‑ och y‑riktningarna utan att förändra vinkeln mellan vinkelräta vektorer. |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | Denna konstant indikerar att den transformering som definieras av detta objekt utför en godtycklig konvertering av indata‑koordinaterna. |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | En identitetstransform är en där utdata‑koordinaterna alltid är desamma som indata‑koordinaterna. |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | Denna konstant är en bitmask för någon av rotations‑flaggbitarna. |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | Denna konstant är en bitmask för någon av skalnings‑flaggbitarna. |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | Denna flaggbit indikerar att den transformering som definieras av detta objekt utför en kvadrantrotation med någon multipel av 90 grader, utöver de konverteringar som anges av andra flaggbitar. |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | En translation förflyttar koordinaterna med ett konstant värde i x och y utan att förändra vektorlängden eller vinkeln. |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | En enhetlig skalning multiplicerar vektorlängden med samma faktor i både x‑ och y‑riktningarna utan att förändra vinkeln mellan vektorerna. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om det angivna  System.Object  är lika med denna instans. |
| [getClass()](#getClass--) |  |
| [getElements()](#getElements--) | Hämtar en kopia av matrisens element. |
| [getM11()](#getM11--) | Hämtar matriselementet i första raden, första kolumnen. |
| [getM12()](#getM12--) | Hämtar matriselementet i första raden, andra kolumnen. |
| [getM21()](#getM21--) | Hämtar matriselementet i andra raden, första kolumnen. |
| [getM22()](#getM22--) | Hämtar matriselementet i andra raden, andra kolumnen. |
| [getM31()](#getM31--) | Hämtar matriselementet i tredje raden, första kolumnen. |
| [getM32()](#getM32--) | Hämtar matriselementet i tredje raden, första kolumnen. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för den här instansen. |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-) | Bestämmer om två matriser är lika. |
| [isIdentity()](#isIdentity--) | Returnerar `true` om detta `AffineTransform` är en identitetstransform. |
| [multiply(Matrix Tx)](#multiply-com.aspose.psd.Matrix-) | Multiplicerar denna Matrix med matrisen som anges i matris‑parametern med (standard) Prepend‑ordning. |
| [multiply(Matrix Tx, int order)](#multiply-com.aspose.psd.Matrix-int-) | Multiplicerar denna Matrix med matrisen som anges i matris‑parametern, i den ordning som anges i order‑parametern. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | Återställer denna Matrix så att den har elementen i identitetsmatrisen. |
| [rotate(float angle)](#rotate-float-) | Applicerar en medursrotation med ett värde som anges i vinkel‑parametern, kring origo (noll‑x‑ och y‑koordinater) för denna Matrix i standard‑ (Prepend)‑ordning. |
| [rotate(float angle, int order)](#rotate-float-int-) | Applicerar en medursrotation med ett värde som anges i vinkel‑parametern, kring origo (noll‑x‑ och y‑koordinater) för denna Matrix i den angivna ordningen. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.psd.PointF-) | Applicerar en medursrotation kring den angivna punkten på denna Matrix i standard‑ (Prepend)‑ordning. |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.psd.PointF-int-) | Applicerar en medursrotation kring den angivna punkten på denna Matrix i den angivna ordningen. |
| [scale(float sx, float sy)](#scale-float-float-) | Tillämpar den specificerade skalvektorn (scaleX och scaleY) på denna Matrix med (standard) Prepend order. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Tillämpar den specificerade skalvektorn (scaleX och scaleY) på denna Matrix med den specificerade ordningen. |
| [toString()](#toString--) | Returnerar en  System.String  som representerar detta objekt. |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.psd.PointF---) | Tillämpar den geometriska transformationen som representeras av denna Matrix på en specificerad punktarray. |
| [translate(float tx, float ty)](#translate-float-float-) | Tillämpar den specificerade transvektorn på denna Matrix med (standard) Prepend order. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Tillämpar den specificerade transvektorn på denna Matrix i den specificerade ordningen. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix() {#Matrix--}
```
public Matrix()
```


Initierar en ny instans av Matrix‑klassen som identitetsmatris.

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


Initierar en ny instans av  Matrix  klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| m11 | float | m00 M11 Skala X |
| m12 | float | m10 M12 Skev Y |
| m21 | float | m01 M21 Skev X |
| m22 | float | m11 M22 Skala Y |
| m31 | float | m02 M31 Translatera X |
| m32 | float | m12 M32 Translatera Y |

### Matrix(Matrix origin) {#Matrix-com.aspose.psd.Matrix-}
```
public Matrix(Matrix origin)
```


Skapar en kopia av  Matrix  klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.psd/matrix) | basmatrisen för coping |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Initierar en ny instans av  Aspose.Imaging.Matrix  klassen till den geometriska transformen som definieras av den angivna rektangeln och punktarrayen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | En  Aspose.Imaging.RectangleF  struktur som representerar rektangeln som ska transformeras. |
| plgpts | [PointF\[\]](../../com.aspose.psd/pointf) | En array av tre  Aspose.Imaging.PointF  strukturer som representerar punkterna i ett parallellogram till vilket de övre vänstra, övre högra och nedre vänstra hörnen av rektangeln ska transformeras. Det nedre högra hörnet av parallellogrammet är underförstått av de första tre hörnen. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Initierar en ny instans av  Aspose.Imaging.Matrix  klassen till den geometriska transformen som definieras av den angivna rektangeln och punktarrayen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | En  Aspose.Imaging.Rectangle  struktur som representerar rektangeln som ska transformeras. |
| plgpts | [Point\[\]](../../com.aspose.psd/point) | En array av tre  Aspose.Imaging.Point  strukturer som representerar punkterna i ett parallellogram till vilket de övre vänstra, övre högra och nedre vänstra hörnen av rektangeln ska transformeras. Det nedre högra hörnet av parallellogrammet är underförstått av de första tre hörnen. |

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


Denna flaggbit indikerar att den transformation som definieras av detta objekt utför en spegelvändning kring någon axel, vilket förändrar det normalt högervriddna koordinatsystemet till ett vänstervridd system, utöver de konverteringar som anges av andra flaggbitar. Ett högervridet koordinatsystem är ett där den positiva X‑axeln roterar moturs för att överlappa den positiva Y‑axeln, likt den riktning som fingrarna på din högra hand kröker sig när du tittar rakt på tummen. Ett vänstervridet koordinatsystem är ett där den positiva X‑axeln roterar medurs för att överlappa den positiva Y‑axeln, likt den riktning som fingrarna på din vänstra hand kröker sig. Det finns inget matematiskt sätt att bestämma vinkeln för den ursprungliga vändnings- eller speglingstransformeringen eftersom alla vändningsvinklar är identiska när en lämplig justeringsrotation appliceras. OBS: TypeFlip lades till efter att GENERAL\\_TRANSFORM var i offentlig cirkulation och flaggbitarna kunde inte längre enkelt omnumreras utan att introducera binär inkompatibilitet i extern kod.

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


Denna flaggbit indikerar att den transformation som definieras av detta objekt utför en rotation med en godtycklig vinkel utöver de konverteringar som anges av andra flaggbitar. En rotation förändrar vektorns vinklar med samma mängd oavsett vektorns ursprungliga riktning och utan att ändra vektorns längd. Denna flaggbit är ömsesidigt uteslutande med den

### TYPE_GENERAL_SCALE {#TYPE-GENERAL-SCALE}
```
public static final int TYPE_GENERAL_SCALE
```


En generell skala multiplicerar längden på vektorer med olika värden i x‑ och y‑riktningarna utan att förändra vinkeln mellan ortogonala vektorer. Denna flaggbit är ömsesidigt uteslutande med TypeUniformScale‑flaggan.

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


Denna konstant indikerar att den transform som definieras av detta objekt utför en godtycklig konvertering av inmatningskoordinaterna. Om denna transform kan klassificeras av någon av ovanstående konstanter kommer typen antingen att vara konstanten TypeIdentity eller en kombination av lämpliga flaggbitar för de olika koordinatkonverteringarna som denna transform utför.

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


En identitetstransform är en där utdata-koordinaterna alltid är desamma som indata-koordinaterna. Om denna transform är något annat än identitetstransformen kommer typen antingen att vara konstanten GENERAL\_TRANSFORM eller en kombination av lämpliga flaggbitar för de olika koordinatkonverteringarna som denna transform utför.

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


Denna konstant är en bitmask för någon av rotations‑flaggbitarna.

### TYPE_MASK_SCALE {#TYPE-MASK-SCALE}
```
public static final int TYPE_MASK_SCALE
```


Denna konstant är en bitmask för någon av skalnings‑flaggbitarna.

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


Denna flaggbit indikerar att den transform som definieras av detta objekt utför en kvadrantrotation med någon multipel av 90 grader utöver de konverteringar som anges av andra flaggbitar. En rotation ändrar vektorns vinklar med samma mängd oavsett vektorns ursprungliga riktning och utan att ändra vektorns längd. Denna flaggbit är ömsesidigt uteslutande med flaggan TypeGeneralRotation.

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


En translation förflyttar koordinaterna med ett konstant värde i x och y utan att förändra vektorlängden eller vinkeln.

### TYPE_UNIFORM_SCALE {#TYPE-UNIFORM-SCALE}
```
public static final int TYPE_UNIFORM_SCALE
```


En enhetlig skalning multiplicerar vektorns längd med samma mängd i både x- och y-riktningarna utan att ändra vinkeln mellan vektorerna. Denna flaggbit är ömsesidigt uteslutande med flaggan TypeGeneralScale.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om det angivna  System.Object  är lika med denna instans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Det  System.Object  att jämföra med den här instansen. |

**Returns:**
boolean -  true  om det angivna  System.Object  är lika med den här instansen; annars  false .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getElements() {#getElements--}
```
public float[] getElements()
```


Hämtar en kopia av matrisens element.

**Returns:**
float[] - En kopia av matrisens element.
### getM11() {#getM11--}
```
public float getM11()
```


Hämtar matriselementet i första raden första kolumnen. Representerar skalning längs X-axeln.

**Returns:**
float
### getM12() {#getM12--}
```
public float getM12()
```


Hämtar matriselementet i första raden andra kolumnen. Representerar skevning längs Y-axeln.

**Returns:**
float
### getM21() {#getM21--}
```
public float getM21()
```


Hämtar matriselementet i andra raden första kolumnen. Representerar skevning längs X-axeln.

**Returns:**
float
### getM22() {#getM22--}
```
public float getM22()
```


Hämtar matriselementet i andra raden andra kolumnen. Representerar skalning längs Y-axeln.

**Returns:**
float
### getM31() {#getM31--}
```
public float getM31()
```


Hämtar matriselementet i tredje raden första kolumnen. Representerar translation längs X-axeln.

**Returns:**
float
### getM32() {#getM32--}
```
public float getM32()
```


Hämtar matriselementet i tredje raden första kolumnen. Representerar translation längs Y-axeln.

**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för den här instansen.

**Returns:**
int - En hashkod för den här instansen, lämplig för användning i hash‑algoritmer och datastrukturer som en hashtabell.
### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


Bestämmer om två matriser är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.psd/matrix) | Den första matrisen att jämföra. |
| b | [Matrix](../../com.aspose.psd/matrix) | Den andra matrisen att jämföra. |

**Returns:**
boolean - Sant om matriserna är lika.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Returnerar `true` om detta `AffineTransform` är en identitetstransform.

**Returns:**
boolean - `true` om detta `AffineTransform` är en identitetstransform; `false` annars.
### multiply(Matrix Tx) {#multiply-com.aspose.psd.Matrix-}
```
public void multiply(Matrix Tx)
```


Multiplicerar denna Matrix med matrisen som anges i matris‑parametern med (standard) Prepend‑ordning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | Matrisen att multiplicera med. |

### multiply(Matrix Tx, int order) {#multiply-com.aspose.psd.Matrix-int-}
```
public void multiply(Matrix Tx, int order)
```


Multiplicerar denna Matrix med matrisen som anges i matris‑parametern, i den ordning som anges i order‑parametern.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | Tx: Tx: Tx: |
| ordning | int | Ordningen. Ordningen. Ordningen. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reset() {#reset--}
```
public void reset()
```


Återställer denna Matrix så att den har elementen i identitetsmatrisen.

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Applicerar en medursrotation med ett värde som anges i vinkel‑parametern, kring origo (noll‑x‑ och y‑koordinater) för denna Matrix i standard‑ (Prepend)‑ordning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


Applicerar en medursrotation med ett värde som anges i vinkel‑parametern, kring origo (noll‑x‑ och y‑koordinater) för denna Matrix i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln. |
| ordning | int | Matrisordning. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.psd.PointF-}
```
public void rotateAt(float angle, PointF point)
```


Applicerar en medursrotation kring den angivna punkten på denna Matrix i standard‑ (Prepend)‑ordning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Vinkeln. |
| point | [PointF](../../com.aspose.psd/pointf) | Punkten. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.psd.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


Applicerar en medursrotation kring den angivna punkten på denna Matrix i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Vinkeln. |
| point | [PointF](../../com.aspose.psd/pointf) | Punkten. |
| ordning | int | Ordningen. |

### scale(float sx, float sy) {#scale-float-float-}
```
public void scale(float sx, float sy)
```


Tillämpar den specificerade skalvektorn (scaleX och scaleY) på denna Matrix med (standard) Prepend order.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sx | float | Sx. Sx. Sx. |
| sy | float | Sy. Sy. Sy. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


Tillämpar den specificerade skalvektorn (scaleX och scaleY) på denna Matrix med den specificerade ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scaleX | float | Skala X. |
| scaleY | float | Skala Y. |
| ordning | int | Ordningen. |

### toString() {#toString--}
```
public String toString()
```


Returnerar en  System.String  som representerar detta objekt.

**Returns:**
java.lang.String - En  System.String  som representerar detta objekt.
### transformPoints(PointF[] points) {#transformPoints-com.aspose.psd.PointF---}
```
public void transformPoints(PointF[] points)
```


Tillämpar den geometriska transformationen som representeras av denna Matrix på en specificerad punktarray.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Punkterna. |

### translate(float tx, float ty) {#translate-float-float-}
```
public void translate(float tx, float ty)
```


Tillämpar den specificerade transvektorn på denna Matrix med (standard) Prepend order.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tx | float | Tx: Tx: Tx: |
| ty | float | Den ty. Den ty. Den ty. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


Tillämpar den specificerade transvektorn på denna Matrix i den specificerade ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| offsetX | float | Offset X:en. |
| offsetY | float | Offset Y:en. |
| ordning | int | Ordningen. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

