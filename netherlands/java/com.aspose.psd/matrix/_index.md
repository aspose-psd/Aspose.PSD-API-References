---
title: "Matrix"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Vervangt de GDI‑Matrix."
type: docs
weight: 69
url: /nl/java/com.aspose.psd/matrix/
---

**Inheritance:**
java.lang.Object
```
public class Matrix
```

Vervangt de GDI+ Matrix.

De meeste algoritmen zijn overgenomen uit Sun's AffineTransform.java. Java‑namen voor matrixelementen die intern worden gebruikt. Mapping van java‑namen naar .net‑namen met beschrijving: m00 M11 Schaal X m10 M12 Schuine Y m01 M21 Schuine X m11 M22 Schaal Y m02 M31 Translatie X m12 M32 Translatie Y
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Matrix()](#Matrix--) | Initialiseert een nieuw exemplaar van de Matrix‑klasse als de identiteitsmatrix. |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | Initialiseert een nieuw exemplaar van de Matrix‑klasse. |
| [Matrix(Matrix origin)](#Matrix-com.aspose.psd.Matrix-) | Maakt een kopie van de Matrix‑klasse. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---) | Initialiseert een nieuw exemplaar van de Aspose.Imaging.Matrix‑klasse naar de geometrische transformatie gedefinieerd door het opgegeven rechthoek en de array van punten. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---) | Initialiseert een nieuw exemplaar van de Aspose.Imaging.Matrix‑klasse naar de geometrische transformatie gedefinieerd door het opgegeven rechthoek en de array van punten. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [TYPE_FLIP](#TYPE-FLIP) | Dit vlag‑bit geeft aan dat de transformatie gedefinieerd door dit object een spiegelbeeld‑omslag langs een as uitvoert, waardoor het normaal rechtshandige coördinatensysteem wordt omgezet in een linkshandig systeem, naast de conversies die door andere vlag‑bits worden aangegeven. |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | Dit vlag‑bit geeft aan dat de transformatie gedefinieerd door dit object een rotatie met een willekeurige hoek uitvoert, naast de conversies die door andere vlag‑bits worden aangegeven. |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | Een algemene schaal vermenigvuldigt de lengte van vectoren met verschillende waarden in de x‑ en y‑richtingen zonder de hoek tussen loodrechte vectoren te veranderen. |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | Deze constante geeft aan dat de transformatie gedefinieerd door dit object een willekeurige conversie van de invoercoördinaten uitvoert. |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | Een identiteits‑transformatie is er een waarbij de uitvoercoördinaten altijd dezelfde zijn als de invoercoördinaten. |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | Deze constante is een bitmasker voor een van de rotatie‑vlagbits. |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | Deze constante is een bitmasker voor een van de schaal‑vlagbits. |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | Dit vlagbit geeft aan dat de transformatie gedefinieerd door dit object een kwadrantrotatie uitvoert met een veelvoud van 90 graden, naast de conversies die door andere vlagbits worden aangegeven. |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | Een translatie verplaatst de coördinaten met een constante hoeveelheid in x en y zonder de lengte of hoek van vectoren te wijzigen. |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | Een uniforme schaal vermenigvuldigt de lengte van vectoren met dezelfde hoeveelheid in zowel de x- als y-richting zonder de hoek tussen vectoren te wijzigen. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of het opgegeven  System.Object  gelijk is aan deze instantie. |
| [getClass()](#getClass--) |  |
| [getElements()](#getElements--) | Haalt een kopie van de matrixelementen op. |
| [getM11()](#getM11--) | Haalt het matrixelement op in de eerste rij, eerste kolom. |
| [getM12()](#getM12--) | Haalt het matrixelement op in de eerste rij, tweede kolom. |
| [getM21()](#getM21--) | Haalt het matrixelement op in de tweede rij, eerste kolom. |
| [getM22()](#getM22--) | Haalt het matrixelement op in de tweede rij, tweede kolom. |
| [getM31()](#getM31--) | Haalt het matrixelement op in de derde rij, eerste kolom. |
| [getM32()](#getM32--) | Haalt het matrixelement op in de derde rij, eerste kolom. |
| [hashCode()](#hashCode--) | Retourneert een hashcode voor dit exemplaar. |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-) | Bepaalt of twee matrices gelijk zijn. |
| [isIdentity()](#isIdentity--) | Retourneert `true` als deze `AffineTransform` een identiteits‑transformatie is. |
| [multiply(Matrix Tx)](#multiply-com.aspose.psd.Matrix-) | Vermenigvuldigt deze Matrix met de matrix die is opgegeven in de matrixparameter met behulp van de (standaard) Prepend‑volgorde. |
| [multiply(Matrix Tx, int order)](#multiply-com.aspose.psd.Matrix-int-) | Vermenigvuldigt deze Matrix met de matrix die is opgegeven in de matrixparameter, en in de volgorde die is opgegeven in de order‑parameter. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | Stelt deze Matrix opnieuw in zodat deze de elementen van de identiteitsmatrix bevat. |
| [rotate(float angle)](#rotate-float-) | Past een klokwijzerzinrotatie toe van een hoeveelheid die is opgegeven in de hoekparameter, rond de oorsprong (nul x- en y-coördinaten) voor deze Matrix in de standaard (Prepend) volgorde. |
| [rotate(float angle, int order)](#rotate-float-int-) | Past een klokwijzerzinrotatie toe van een hoeveelheid die is opgegeven in de hoekparameter, rond de oorsprong (nul x- en y-coördinaten) voor deze Matrix in de opgegeven volgorde. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.psd.PointF-) | Past een klokwijzerzinrotatie rond het opgegeven punt toe op deze Matrix in de standaard (Prepend) volgorde. |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.psd.PointF-int-) | Past een klokwijzerzinrotatie rond het opgegeven punt toe op deze Matrix in de opgegeven volgorde. |
| [scale(float sx, float sy)](#scale-float-float-) | Past de opgegeven schaalvector (scaleX en scaleY) toe op deze Matrix met gebruik van de (standaard) Prepend‑volgorde. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Past de opgegeven schaalvector (scaleX en scaleY) toe op deze Matrix met de opgegeven volgorde. |
| [toString()](#toString--) | Retourneert een  System.String  die deze instantie vertegenwoordigt. |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.psd.PointF---) | Past de geometrische transformatie die door deze Matrix wordt vertegenwoordigd toe op een opgegeven array van punten. |
| [translate(float tx, float ty)](#translate-float-float-) | Past de opgegeven translatievector toe op deze  Matrix  met (standaard) Prepend volgorde. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Past de opgegeven translatievector toe op deze Matrix in de opgegeven volgorde. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix() {#Matrix--}
```
public Matrix()
```


Initialiseert een nieuw exemplaar van de Matrix‑klasse als de identiteitsmatrix.

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


Initialiseert een nieuw exemplaar van de Matrix‑klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| m11 | float | m00 M11 Schaal X |
| m12 | float | m10 M12 Schuif Y |
| m21 | float | m01 M21 Schuif X |
| m22 | float | m11 M22 Schaal Y |
| m31 | float | m02 M31 Vertaal X |
| m32 | float | m12 M32 Vertaal Y |

### Matrix(Matrix origin) {#Matrix-com.aspose.psd.Matrix-}
```
public Matrix(Matrix origin)
```


Maakt een kopie van de Matrix‑klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.psd/matrix) | de basismatrix voor coping |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Initialiseert een nieuw exemplaar van de Aspose.Imaging.Matrix‑klasse naar de geometrische transformatie gedefinieerd door het opgegeven rechthoek en de array van punten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Een  Aspose.Imaging.RectangleF  structuur die de te transformeren rechthoek vertegenwoordigt. |
| plgpts | [PointF\[\]](../../com.aspose.psd/pointf) | Een array van drie  Aspose.Imaging.PointF  structuren die de punten van een parallellogram vertegenwoordigen waartoe de bovenlinker, bovenrechter en onderlinker hoeken van de rechthoek moeten worden getransformeerd. De onderrechter hoek van het parallellogram wordt geïmpliceerd door de eerste drie hoeken. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Initialiseert een nieuw exemplaar van de Aspose.Imaging.Matrix‑klasse naar de geometrische transformatie gedefinieerd door het opgegeven rechthoek en de array van punten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Een  Aspose.Imaging.Rectangle  structuur die de te transformeren rechthoek vertegenwoordigt. |
| plgpts | [Point\[\]](../../com.aspose.psd/point) | Een array van drie  Aspose.Imaging.Point  structuren die de punten van een parallellogram vertegenwoordigen waartoe de bovenlinker, bovenrechter en onderlinker hoeken van de rechthoek moeten worden getransformeerd. De onderrechter hoek van het parallellogram wordt geïmpliceerd door de eerste drie hoeken. |

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


Dit vlagbit geeft aan dat de transformatie gedefinieerd door dit object een spiegelbeeldomslag uitvoert rond een as, waardoor het normaal rechtshandige coördinatensysteem wordt omgezet in een linkshandig systeem, naast de conversies die door andere vlagbits worden aangegeven. Een rechtshandig coördinatensysteem is er een waarbij de positieve X-as tegen de klok in draait om de positieve Y-as te overlappen, vergelijkbaar met de richting waarin de vingers van uw rechterhand krullen wanneer u recht op uw duim kijkt. Een linkshandig coördinatensysteem is er een waarbij de positieve X-as met de klok mee draait om de positieve Y-as te overlappen, vergelijkbaar met de richting waarin de vingers van uw linkerhand krullen. Er is geen wiskundige manier om de hoek van de oorspronkelijke flip‑ of spiegeltransformatie te bepalen, aangezien alle flip‑hoeken identiek zijn bij een passende aanpassingsrotatie. OPMERKING: TypeFlip werd toegevoegd nadat GENERAL\_TRANSFORM in publieke circulatie was en de vlagbits konden niet langer gemakkelijk worden genummerd zonder binaire incompatibiliteit in externe code te introduceren.

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


Dit vlagbit geeft aan dat de transformatie gedefinieerd door dit object een rotatie uitvoert met een willekeurige hoek, naast de conversies die door andere vlagbits worden aangegeven. Een rotatie verandert de hoeken van vectoren met dezelfde hoeveelheid, ongeacht de oorspronkelijke richting van de vector en zonder de lengte van de vector te wijzigen. Dit vlagbit staat wederzijds exclusief met de

### TYPE_GENERAL_SCALE {#TYPE-GENERAL-SCALE}
```
public static final int TYPE_GENERAL_SCALE
```


Een algemene schaal vermenigvuldigt de lengte van vectoren met verschillende hoeveelheden in de x- en y-richting zonder de hoek tussen loodrechte vectoren te veranderen. Dit vlagbit staat wederzijds exclusief met de TypeUniformScale‑vlag.

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


Deze constante geeft aan dat de transformatie gedefinieerd door dit object een willekeurige conversie van de invoercoördinaten uitvoert. Als deze transformatie kan worden geclassificeerd door een van de bovenstaande constanten, zal het type ofwel de constante TypeIdentity zijn of een combinatie van de juiste vlagbits voor de verschillende coördinatenconversies die deze transformatie uitvoert.

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


Een identieke transformatie is er een waarbij de uitvoercoördinaten altijd hetzelfde zijn als de invoercoördinaten. Als deze transformatie iets anders is dan de identieke transformatie, zal het type ofwel de constante GENERAL\_TRANSFORM zijn of een combinatie van de juiste vlagbits voor de verschillende coördinatenconversies die deze transformatie uitvoert.

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


Deze constante is een bitmasker voor een van de rotatie‑vlagbits.

### TYPE_MASK_SCALE {#TYPE-MASK-SCALE}
```
public static final int TYPE_MASK_SCALE
```


Deze constante is een bitmasker voor een van de schaal‑vlagbits.

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


Dit vlagbit geeft aan dat de transformatie gedefinieerd door dit object een kwadrantrotatie uitvoert met een veelvoud van 90 graden, naast de conversies die door andere vlagbits worden aangegeven. Een rotatie verandert de hoeken van vectoren met dezelfde hoeveelheid, ongeacht de oorspronkelijke richting van de vector en zonder de lengte van de vector te wijzigen. Dit vlagbit staat wederzijds exclusief met de TypeGeneralRotation‑vlag.

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


Een translatie verplaatst de coördinaten met een constante hoeveelheid in x en y zonder de lengte of hoek van vectoren te wijzigen.

### TYPE_UNIFORM_SCALE {#TYPE-UNIFORM-SCALE}
```
public static final int TYPE_UNIFORM_SCALE
```


Een uniforme schaal vermenigvuldigt de lengte van vectoren met dezelfde hoeveelheid in zowel de x- als y‑richting zonder de hoek tussen vectoren te veranderen. Dit vlagbit staat wederzijds exclusief met het TypeGeneralScale‑vlagbit.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of het opgegeven  System.Object  gelijk is aan deze instantie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het  System.Object  om te vergelijken met dit exemplaar. |

**Returns:**
boolean -  true  als het opgegeven  System.Object  gelijk is aan deze instantie; anders,  false .
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


Haalt een kopie van de matrixelementen op.

**Returns:**
float[] - Een kopie van matrixelementen.
### getM11() {#getM11--}
```
public float getM11()
```


Haalt het matrixelement op in de eerste rij, eerste kolom. Vertegenwoordigt schaal langs de X‑as.

**Returns:**
float
### getM12() {#getM12--}
```
public float getM12()
```


Haalt het matrixelement op in de eerste rij, tweede kolom. Vertegenwoordigt schuine vervorming langs de Y‑as.

**Returns:**
float
### getM21() {#getM21--}
```
public float getM21()
```


Haalt het matrixelement op in de tweede rij, eerste kolom. Vertegenwoordigt schuine vervorming langs de X‑as.

**Returns:**
float
### getM22() {#getM22--}
```
public float getM22()
```


Haalt het matrixelement op in de tweede rij, tweede kolom. Vertegenwoordigt schaal langs de Y‑as.

**Returns:**
float
### getM31() {#getM31--}
```
public float getM31()
```


Haalt het matrixelement op in de derde rij, eerste kolom. Vertegenwoordigt translatie langs de X‑as.

**Returns:**
float
### getM32() {#getM32--}
```
public float getM32()
```


Haalt het matrixelement op in de derde rij, eerste kolom. Vertegenwoordigt translatie langs de Y‑as.

**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hashcode voor dit exemplaar.

**Returns:**
int - Een hashcode voor deze instantie, geschikt voor gebruik in hash-algoritmen en datastructuren zoals een hashtabel.
### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


Bepaalt of twee matrices gelijk zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.psd/matrix) | De eerste matrix om te vergelijken. |
| b | [Matrix](../../com.aspose.psd/matrix) | De tweede matrix om te vergelijken. |

**Returns:**
boolean - Waar als matrices gelijk zijn.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Retourneert `true` als deze `AffineTransform` een identiteits‑transformatie is.

**Returns:**
boolean - `true` als deze `AffineTransform` een identiteitstransformatie is; `false` anders.
### multiply(Matrix Tx) {#multiply-com.aspose.psd.Matrix-}
```
public void multiply(Matrix Tx)
```


Vermenigvuldigt deze Matrix met de matrix die is opgegeven in de matrixparameter met behulp van de (standaard) Prepend‑volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | De matrix om mee te vermenigvuldigen. |

### multiply(Matrix Tx, int order) {#multiply-com.aspose.psd.Matrix-int-}
```
public void multiply(Matrix Tx, int order)
```


Vermenigvuldigt deze Matrix met de matrix die is opgegeven in de matrixparameter, en in de volgorde die is opgegeven in de order‑parameter.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | De tx. De tx. De tx. |
| volgorde | int | De volgorde. De volgorde. De volgorde. |

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


Stelt deze Matrix opnieuw in zodat deze de elementen van de identiteitsmatrix bevat.

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Past een klokwijzerzinrotatie toe van een hoeveelheid die is opgegeven in de hoekparameter, rond de oorsprong (nul x- en y-coördinaten) voor deze Matrix in de standaard (Prepend) volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| angle | float | De rotatiehoek. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


Past een klokwijzerzinrotatie toe van een hoeveelheid die is opgegeven in de hoekparameter, rond de oorsprong (nul x- en y-coördinaten) voor deze Matrix in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| angle | float | De rotatiehoek. |
| volgorde | int | De matrixvolgorde. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.psd.PointF-}
```
public void rotateAt(float angle, PointF point)
```


Past een klokwijzerzinrotatie rond het opgegeven punt toe op deze Matrix in de standaard (Prepend) volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| angle | float | De hoek. |
| point | [PointF](../../com.aspose.psd/pointf) | Het punt. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.psd.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


Past een klokwijzerzinrotatie rond het opgegeven punt toe op deze Matrix in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| angle | float | De hoek. |
| point | [PointF](../../com.aspose.psd/pointf) | Het punt. |
| volgorde | int | De volgorde. |

### scale(float sx, float sy) {#scale-float-float-}
```
public void scale(float sx, float sy)
```


Past de opgegeven schaalvector (scaleX en scaleY) toe op deze Matrix met gebruik van de (standaard) Prepend‑volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sx | float | De sx. De sx. De sx. |
| sy | float | De sy. De sy. De sy. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


Past de opgegeven schaalvector (scaleX en scaleY) toe op deze Matrix met de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scaleX | float | De schaal X. |
| scaleY | float | De schaal Y. |
| volgorde | int | De volgorde. |

### toString() {#toString--}
```
public String toString()
```


Retourneert een  System.String  die deze instantie vertegenwoordigt.

**Returns:**
java.lang.String - Een  System.String  die deze instantie vertegenwoordigt.
### transformPoints(PointF[] points) {#transformPoints-com.aspose.psd.PointF---}
```
public void transformPoints(PointF[] points)
```


Past de geometrische transformatie die door deze Matrix wordt vertegenwoordigd toe op een opgegeven array van punten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | De punten. |

### translate(float tx, float ty) {#translate-float-float-}
```
public void translate(float tx, float ty)
```


Past de opgegeven translatievector toe op deze  Matrix  met (standaard) Prepend volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tx | float | De tx. De tx. De tx. |
| ty | float | De ty. De ty. De ty. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


Past de opgegeven translatievector toe op deze Matrix in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| offsetX | float | De offset X. |
| offsetY | float | De offset Y. |
| volgorde | int | De volgorde. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

