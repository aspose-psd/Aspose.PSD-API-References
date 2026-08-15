---
title: "Matrix Klasse"
type: docs
weight: 3000
url: /nl/python-net/aspose.psd/matrix/
---

**Summary:** Replaces the GDI+ Matrix.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Matrix

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [Matrix()](#Matrix__1) | Initialiseert een nieuw exemplaar van de Matrix-klasse als de identiteitsmatrix. |
| [Matrix(m11, m12, m21, m22, m31, m32)](#Matrix_m11_m12_m21_m22_m31_m32_2) | Initialiseert een nieuw exemplaar van de [Matrix](/psd/python-net/aspose.psd/matrix/) klasse. |
| [Matrix(origin)](#Matrix_origin_3) | Maakt een kopie van de [Matrix](/psd/python-net/aspose.psd/matrix/) klasse. |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_4) | Initialiseert een nieuw exemplaar van de [Matrix](/psd/python-net/aspose.psd/matrix/) klasse voor de geometrische transformatie die wordt gedefinieerd door het opgegeven rechthoek en de array van punten. |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_5) | Initialiseert een nieuw exemplaar van de [Matrix](/psd/python-net/aspose.psd/matrix/) klasse voor de geometrische transformatie die wordt gedefinieerd door het opgegeven rechthoek en de array van punten. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| TYPE_FLIP [statisch] | int | r | Dit vlagbit geeft aan dat de transformatie gedefinieerd door dit object<br/>            een spiegelbeeldomslag uitvoert rond een as die het<br/>            normaal rechtshandige coördinatensysteem verandert in een linkshandig<br/>            systeem, naast de conversies aangegeven door andere vlagbits.<br/>            Een rechtshandig coördinatensysteem is er een waarbij de positieve X<br/>            as tegen de klok in draait om de positieve Y-as te overlappen<br/>            vergelijkbaar met de richting waarin de vingers van uw rechterhand<br/>            krullen wanneer u recht op uw duim kijkt.<br/>            Een linkshandig coördinatensysteem is er een waarbij de positieve X<br/>            as met de klok mee draait om de positieve Y-as te overlappen, vergelijkbaar<br/>            met de richting waarin de vingers van uw linkshand krullen.<br/>            Er is geen wiskundige manier om de hoek van de<br/>            oorspronkelijke omslag- of spiegeltransformatie te bepalen, aangezien alle hoeken<br/>            van de omslag identiek zijn gegeven een geschikte aanpassingsrotatie.<br/>            OPMERKING: TypeFlip werd toegevoegd nadat GENERAL_TRANSFORM publiekelijk<br/>            beschikbaar was en de vlagbits niet meer gemakkelijk<br/>            konden worden hernummerd zonder binaire incompatibiliteit in externe<br/>            code te introduceren. |
| TYPE_GENERAL_ROTATION [static] | int | r | Dit vlagbit geeft aan dat de transformatie gedefinieerd door dit object<br/>            een rotatie uitvoert met een willekeurige hoek, naast de<br/>            conversies aangegeven door andere vlagbits.<br/>            Een rotatie verandert de hoeken van vectoren met dezelfde hoeveelheid<br/>            ongeacht de oorspronkelijke richting van de vector en zonder<br/>            de lengte van de vector te wijzigen.<br/>            Dit vlagbit is onderling exclusief met de |
| TYPE_GENERAL_SCALE [static] | int | r | Een algemene schaal vermenigvuldigt de lengte van vectoren met verschillende<br/>            waarden in de x- en y-richting zonder de hoek<br/>            tussen loodrechte vectoren te veranderen.<br/>            Dit vlagbit is onderling exclusief met de TypeUniformScale vlag. |
| TYPE_GENERAL_TRANSFORM [static] | int | r | Deze constante geeft aan dat de transformatie gedefinieerd door dit object<br/>            een willekeurige conversie van de invoercoördinaten uitvoert.<br/>            Als deze transformatie kan worden geclassificeerd door een van de bovenstaande constanten,<br/>            zal het type ofwel de constante TypeIdentity zijn of een<br/>            combinatie van de juiste vlagbits voor de verschillende coördinaten<br/>            conversies die deze transformatie uitvoert. |
| TYPE_IDENTITY [static] | int | r | Een identiteits transformatie is er een waarbij de uitvoercoördinaten<br/>            altijd dezelfde zijn als de invoercoördinaten.<br/>            Als deze transformatie iets anders is dan de identiteits transformatie,<br/>            zal het type ofwel de constante GENERAL_TRANSFORM zijn of een<br/>            combinatie van de juiste vlagbits voor de verschillende coördinaten<br/>            conversies die deze transformatie uitvoert. |
| TYPE_MASK_ROTATION [static] | int | r | Deze constante is een bitmasker voor elk van de rotatie vlagbits. |
| TYPE_MASK_SCALE [static] | int | r | Deze constante is een bitmasker voor elk van de schaal vlagbits. |
| TYPE_QUADRANT_ROTATION [static] | int | r | Dit vlagbit geeft aan dat de transformatie gedefinieerd door dit object<br/>            een kwadrantrotatie uitvoert met een veelvoud van 90 graden in<br/>            aanvulling op de conversies aangegeven door andere vlagbits.<br/>            Een rotatie verandert de hoeken van vectoren met dezelfde hoeveelheid<br/>            ongeacht de oorspronkelijke richting van de vector en zonder<br/>            de lengte van de vector te wijzigen.<br/>            Dit vlagbit is onderling exclusief met de TypeGeneralRotation vlag. |
| TYPE_TRANSLATION [static] | int | r | Een translatie verplaatst de coördinaten met een constante hoeveelheid in x<br/>            en y zonder de lengte of hoek van vectoren te wijzigen. |
| TYPE_UNIFORM_SCALE [static] | int | r | Een uniforme schaal vermenigvuldigt de lengte van vectoren met dezelfde hoeveelheid<br/>            in zowel de x- als y-richting zonder de hoek tussen<br/>            vectoren te veranderen.<br/>            Deze vlagbit is onderling exclusief met de TypeGeneralScale vlag. |
| elements | float | r | Haalt een array van zwevende-kommagetallen op die de elementen van deze [Matrix](/psd/python-net/aspose.psd/matrix/) vertegenwoordigt. |
| m11 | float | r | Haalt het matrixelement op in de eerste rij, eerste kolom. Vertegenwoordigt schaal langs de X-as. |
| m12 | float | r | Haalt het matrixelement op in de eerste rij, tweede kolom. Vertegenwoordigt schuine vervorming langs de Y-as. |
| m21 | float | r | Haalt het matrixelement op in de tweede rij, eerste kolom. Vertegenwoordigt schuine vervorming langs de X-as. |
| m22 | float | r | Haalt het matrixelement op in de tweede rij, tweede kolom. Vertegenwoordigt schaal langs de Y-as. |
| m31 | float | r | Haalt het matrixelement op in de derde rij, eerste kolom. Vertegenwoordigt translatie langs de X-as. |
| m32 | float | r | Haalt het matrixelement op in de derde rij, eerste kolom. Vertegenwoordigt translatie langs de Y-as. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_elements()](#get_elements__1) | Haalt een kopie van de matrixelementen op. |
| [multiply(tx)](#multiply_tx_2) | Vermenigvuldigt deze Matrix met de matrix die is opgegeven in de matrixparameter met gebruik van de (standaard) Prepend-volgorde. |
| [multiply(tx, order)](#multiply_tx_order_3) | Vermenigvuldigt deze Matrix met de matrix die is opgegeven in de matrixparameter, en in de volgorde die is gespecificeerd in de order-parameter. |
| reset() | Reset deze Matrix zodat deze de elementen van de identiteitsmatrix heeft. |
| [rotate(angle)](#rotate_angle_4) | Past een klokwijzerige rotatie toe van een hoeveelheid gespecificeerd in de hoekparameter, rond de oorsprong (nul x- en y-coördinaten) voor deze Matrix in de standaard (Prepend) volgorde. |
| [rotate(angle, order)](#rotate_angle_order_5) | Past een klokwijzerige rotatie toe van een hoeveelheid gespecificeerd in de hoekparameter, rond de oorsprong (nul x- en y-coördinaten) voor deze Matrix in de opgegeven volgorde. |
| [rotate_at(angle, point)](#rotate_at_angle_point_6) | Past een klokwijzerige rotatie rond het opgegeven punt toe op deze Matrix in de standaard (Prepend) volgorde. |
| [rotate_at(angle, point, order)](#rotate_at_angle_point_order_7) | Past een klokwijzerige rotatie rond het opgegeven punt toe op deze Matrix in de opgegeven volgorde. |
| [scale(scale_x, scale_y, order)](#scale_scale_x_scale_y_order_8) | Past de opgegeven schaalvector (scaleX en scaleY) toe op deze [Matrix](/psd/python-net/aspose.psd/matrix/) met de opgegeven volgorde. |
| [scale(sx, sy)](#scale_sx_sy_9) | Past de opgegeven schaalvector (scaleX en scaleY) toe op deze Matrix met gebruik van de (standaard) Prepend-volgorde. |
| [transform_points(points)](#transform_points_points_10) | Past de geometrische transformatie toe die wordt vertegenwoordigd door deze [Matrix](/psd/python-net/aspose.psd/matrix/) op een opgegeven array van punten. |
| [translate(offset_x, offset_y, order)](#translate_offset_x_offset_y_order_11) | Past de opgegeven translatievector toe op deze Matrix in de opgegeven volgorde. |
| [translate(tx, ty)](#translate_tx_ty_12) | Past de opgegeven translatievector toe op deze [Matrix](/psd/python-net/aspose.psd/matrix/) met (standaard) Prepend-volgorde. |


### Constructor: Matrix() {#Matrix__1}


```
 Matrix() 
```

Initialiseert een nieuw exemplaar van de Matrix-klasse als de identiteitsmatrix.

### Constructor: Matrix(m11, m12, m21, m22, m31, m32) {#Matrix_m11_m12_m21_m22_m31_m32_2}


```
 Matrix(m11, m12, m21, m22, m31, m32) 
```

Initialiseert een nieuw exemplaar van de [Matrix](/psd/python-net/aspose.psd/matrix/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| m11 | float | m00     M11     Schaal X |
| m12 | float | m10     M12     Schuine Y |
| m21 | float | m01     M21     Schuine X |
| m22 | float | m11     M22     Schaal Y |
| m31 | float | m02     M31     Vertaal X |
| m32 | float | m12     M32     Vertaal Y |

### Constructor: Matrix(origin) {#Matrix_origin_3}


```
 Matrix(origin) 
```

Maakt een kopie van de [Matrix](/psd/python-net/aspose.psd/matrix/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| origin | [Matrix](/psd/python-net/aspose.psd/matrix) | Een basismatrix voor coping |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_4}


```
 Matrix(rect, plgpts) 
```

Initialiseert een nieuw exemplaar van de [Matrix](/psd/python-net/aspose.psd/matrix/) klasse voor de geometrische transformatie die wordt gedefinieerd door het opgegeven rechthoek en de array van punten.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de te transformeren rechthoek vertegenwoordigt. |
| plgpts | [PointF[]](/psd/python-net/aspose.psd/pointf) | Een array van drie [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de punten van een parallellogram vertegenwoordigen waartoe de bovenlinker, bovenrechter, en onderlinker hoeken van de rechthoek getransformeerd moeten worden. De onderrechter hoek van het parallellogram wordt geïmpliceerd door de eerste drie hoeken. |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_5}


```
 Matrix(rect, plgpts) 
```

Initialiseert een nieuw exemplaar van de [Matrix](/psd/python-net/aspose.psd/matrix/) klasse voor de geometrische transformatie die wordt gedefinieerd door het opgegeven rechthoek en de array van punten.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de te transformeren rechthoek vertegenwoordigt. |
| plgpts | [Point[]](/psd/python-net/aspose.psd/point) | Een array van drie [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de punten van een parallellogram vertegenwoordigen waartoe de bovenlinker, bovenrechter, en onderlinker hoeken van de rechthoek getransformeerd moeten worden. De onderrechter hoek van het parallellogram wordt geïmpliceerd door de eerste drie hoeken. |

### Method: get_elements() {#get_elements__1}


```
 get_elements() 
```

Haalt een kopie van de matrixelementen op.

**Returns**

| Type | Beschrijving |
| :- | :- |
| float | Een kopie van matrixelementen. |


### Method: multiply(tx) {#multiply_tx_2}


```
 multiply(tx) 
```

Vermenigvuldigt deze Matrix met de matrix die is opgegeven in de matrixparameter met gebruik van de (standaard) Prepend-volgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | De matrix om mee te vermenigvuldigen. |

### Method: multiply(tx, order) {#multiply_tx_order_3}


```
 multiply(tx, order) 
```

Vermenigvuldigt deze Matrix met de matrix die is opgegeven in de matrixparameter, en in de volgorde die is gespecificeerd in de order-parameter.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | De tx. De tx. De tx. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | De volgorde. De volgorde. De volgorde. |

### Method: rotate(angle) {#rotate_angle_4}


```
 rotate(angle) 
```

Past een klokwijzerige rotatie toe van een hoeveelheid gespecificeerd in de hoekparameter, rond de oorsprong (nul x- en y-coördinaten) voor deze Matrix in de standaard (Prepend) volgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| hoek | float | De rotatiehoek. |

### Method: rotate(angle, order) {#rotate_angle_order_5}


```
 rotate(angle, order) 
```

Past een klokwijzerige rotatie toe van een hoeveelheid gespecificeerd in de hoekparameter, rond de oorsprong (nul x- en y-coördinaten) voor deze Matrix in de opgegeven volgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| hoek | float | De rotatiehoek. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | De matrixvolgorde. |

### Method: rotate_at(angle, point) {#rotate_at_angle_point_6}


```
 rotate_at(angle, point) 
```

Past een klokwijzerige rotatie rond het opgegeven punt toe op deze Matrix in de standaard (Prepend) volgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| hoek | float | De hoek. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Het punt. |

### Method: rotate_at(angle, point, order) {#rotate_at_angle_point_order_7}


```
 rotate_at(angle, point, order) 
```

Past een klokwijzerige rotatie rond het opgegeven punt toe op deze Matrix in de opgegeven volgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| hoek | float | De hoek. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Het punt. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | De volgorde. |

### Method: scale(scale_x, scale_y, order) {#scale_scale_x_scale_y_order_8}


```
 scale(scale_x, scale_y, order) 
```

Past de opgegeven schaalvector (scaleX en scaleY) toe op deze [Matrix](/psd/python-net/aspose.psd/matrix/) met de opgegeven volgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| scale_x | float | De schaal X. |
| scale_y | float | De schaal Y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | De volgorde. |

### Method: scale(sx, sy) {#scale_sx_sy_9}


```
 scale(sx, sy) 
```

Past de opgegeven schaalvector (scaleX en scaleY) toe op deze Matrix met gebruik van de (standaard) Prepend-volgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| sx | float | De sx. De sx. De sx. |
| sy | float | De sy. De sy. De sy. |

### Method: transform_points(points) {#transform_points_points_10}


```
 transform_points(points) 
```

Past de geometrische transformatie toe die wordt vertegenwoordigd door deze [Matrix](/psd/python-net/aspose.psd/matrix/) op een opgegeven array van punten.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | De punten. |

### Method: translate(offset_x, offset_y, order) {#translate_offset_x_offset_y_order_11}


```
 translate(offset_x, offset_y, order) 
```

Past de opgegeven translatievector toe op deze Matrix in de opgegeven volgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| offset_x | float | De X-offset. |
| offset_y | float | De Y-offset. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | De volgorde. |

### Method: translate(tx, ty) {#translate_tx_ty_12}


```
 translate(tx, ty) 
```

Past de opgegeven translatievector toe op deze [Matrix](/psd/python-net/aspose.psd/matrix/) met (standaard) Prepend-volgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| tx | float | De tx. De tx. De tx. |
| ty | float | De ty. De ty. De ty. |

