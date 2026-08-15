---
title: "TextureBrush Klasse"
type: docs
weight: 90
url: /nl/python-net/aspose.psd.brushes/texturebrush/
---

**Summary:** Each property of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class is a [Brush](/psd/python-net/aspose.psd/brush/) object that uses an image to fill the interior of a shape. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.TextureBrush

**Inheritance:** TransformBrush

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [TextureBrush(image)](#TextureBrush_image_1) | Initialiseert een nieuw exemplaar van de [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) klasse die de opgegeven afbeelding gebruikt. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_2) | Initialiseert een nieuw exemplaar van de [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) klasse die de opgegeven afbeelding en begrenzende rechthoek gebruikt. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_3) | Initialiseert een nieuw exemplaar van de [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) klasse die de opgegeven afbeelding en begrenzende rechthoek gebruikt. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_4) | Initialiseert een nieuw exemplaar van de [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) klasse die de opgegeven afbeelding, begrenzende rechthoek en afbeeldingseigenschappen gebruikt. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_5) | Initialiseert een nieuw exemplaar van de [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) klasse die de opgegeven afbeelding, begrenzende rechthoek en afbeeldingseigenschappen gebruikt. |
| [TextureBrush(image, wrap_mode)](#TextureBrush_image_wrap_mode_6) | Initialiseert een nieuw exemplaar van de [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) klasse die de opgegeven afbeelding en wrap-modus gebruikt. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_7) | Initialiseert een nieuw exemplaar van de [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) klasse die de opgegeven afbeelding, wrap-modus en begrenzende rechthoek gebruikt. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_8) | Initialiseert een nieuw exemplaar van de [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) klasse die de opgegeven afbeelding, wrap-modus en begrenzende rechthoek gebruikt. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| disposed | bool | r | Geeft een waarde die aangeeft of dit exemplaar is vrijgegeven. |
| image | [Image](/psd/python-net/aspose.psd/image) | r | Haalt het [Image](/psd/python-net/aspose.psd/image/) object op dat aan dit [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object is gekoppeld. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | r | Haalt de [TextureBrush.image_attributes](/psd/python-net/aspose.psd.brushes/texturebrush/) op die aan dit [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) is gekoppeld. |
| image_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Haalt het [Rectangle](/psd/python-net/aspose.psd/rectangle/) op dat aan dit [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) is gekoppeld. |
| is_transform_changed | bool | r | Haalt een waarde op die aangeeft of transformaties op een of andere manier zijn gewijzigd. Bijvoorbeeld het instellen van de transformatie‑matrix of<br/>            het aanroepen van een van de methoden die de transformatie‑matrix wijzigen. De eigenschap is geïntroduceerd voor achterwaartse compatibiliteit met GDI+. |
| opacity | float | r/w | Haalt op of stelt de dekking van de penseel in. De waarde moet tussen 0 en 1 liggen. Een waarde van 0 betekent dat de penseel volledig zichtbaar is, een waarde van 1 betekent dat de penseel volledig ondoorzichtig is. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Haalt op of stelt een kopie van de [Matrix](/psd/python-net/aspose.psd/matrix/) in die een lokale geometrische transformatie definieert voor deze [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | r/w | Haalt op of stelt een [WrapMode](/psd/python-net/aspose.psd/wrapmode/) enumeratie in die de wrap-modus aangeeft voor deze [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Maakt een nieuwe diepe kloon van de huidige [Brush](/psd/python-net/aspose.psd/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | Vermenigvuldigt de [Matrix](/psd/python-net/aspose.psd/matrix/) die de lokale geometrische transformatie van deze [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) weergeeft met de opgegeven [Matrix](/psd/python-net/aspose.psd/matrix/) door de opgegeven [Matrix](/psd/python-net/aspose.psd/matrix/) voor te voegen. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | Vermenigvuldigt de [Matrix](/psd/python-net/aspose.psd/matrix/) die de lokale geometrische transformatie van deze [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) weergeeft met de opgegeven [Matrix](/psd/python-net/aspose.psd/matrix/) in de opgegeven volgorde. |
| reset_transform() | Stelt de [TransformBrush.transform](/psd/python-net/aspose.psd.brushes/transformbrush/) eigenschap in op de identiteit. |
| [rotate_transform(angle)](#rotate_transform_angle_4) | Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid. Deze methode plaatst de rotatie vóór de transformatie. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid in de opgegeven volgorde. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | Schaalt de lokale geometrische transformatie met de opgegeven waarden. Deze methode plaatst de schaalmatrix vóór de transformatie. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | Schaalt de lokale geometrische transformatie met de opgegeven waarden in de opgegeven volgorde. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen. Deze methode plaatst de translatie vóór de transformatie. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen in de opgegeven volgorde. |


### Constructor: TextureBrush(image) {#TextureBrush_image_1}


```
 TextureBrush(image) 
```

Initialiseert een nieuw exemplaar van de [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) klasse die de opgegeven afbeelding gebruikt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Het [Image](/psd/python-net/aspose.psd/image/) object waarmee dit [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object binnenkanten vult. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_2}


```
 TextureBrush(image, destination_rectangle) 
```

Initialiseert een nieuw exemplaar van de [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) klasse die de opgegeven afbeelding en begrenzende rechthoek gebruikt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Het [Image](/psd/python-net/aspose.psd/image/) object waarmee dit [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object binnenkanten vult. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de begrenzende rechthoek voor dit [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object vertegenwoordigt. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_3}


```
 TextureBrush(image, destination_rectangle) 
```

Initialiseert een nieuw exemplaar van de [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) klasse die de opgegeven afbeelding en begrenzende rechthoek gebruikt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Het [Image](/psd/python-net/aspose.psd/image/) object waarmee dit [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object binnenkanten vult. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de begrenzende rechthoek voor dit [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object vertegenwoordigt. |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_4}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Initialiseert een nieuw exemplaar van de [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) klasse die de opgegeven afbeelding, begrenzende rechthoek en afbeeldingseigenschappen gebruikt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Het [Image](/psd/python-net/aspose.psd/image/) object waarmee dit [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object binnenkanten vult. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de begrenzende rechthoek voor dit [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object vertegenwoordigt. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Een [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object dat extra informatie bevat over de afbeelding die door dit [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object wordt gebruikt. |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_5}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Initialiseert een nieuw exemplaar van de [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) klasse die de opgegeven afbeelding, begrenzende rechthoek en afbeeldingseigenschappen gebruikt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Het [Image](/psd/python-net/aspose.psd/image/) object waarmee dit [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object binnenkanten vult. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de begrenzende rechthoek voor dit [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object vertegenwoordigt. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Een [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object dat extra informatie bevat over de afbeelding die door dit [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object wordt gebruikt. |

### Constructor: TextureBrush(image, wrap_mode) {#TextureBrush_image_wrap_mode_6}


```
 TextureBrush(image, wrap_mode) 
```

Initialiseert een nieuw exemplaar van de [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) klasse die de opgegeven afbeelding en wrap-modus gebruikt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Het [Image](/psd/python-net/aspose.psd/image/) object waarmee dit [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object binnenkanten vult. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Een [WrapMode](/psd/python-net/aspose.psd/wrapmode/) enumeratie die specificeert hoe dit [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object wordt getegeld. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_7}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Initialiseert een nieuw exemplaar van de [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) klasse die de opgegeven afbeelding, wrap-modus en begrenzende rechthoek gebruikt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Het [Image](/psd/python-net/aspose.psd/image/) object waarmee dit [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object binnenkanten vult. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Een [WrapMode](/psd/python-net/aspose.psd/wrapmode/) enumeratie die specificeert hoe dit [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object wordt getegeld. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de begrenzende rechthoek voor dit [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object vertegenwoordigt. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_8}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Initialiseert een nieuw exemplaar van de [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) klasse die de opgegeven afbeelding, wrap-modus en begrenzende rechthoek gebruikt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Het [Image](/psd/python-net/aspose.psd/image/) object waarmee dit [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object binnenkanten vult. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Een [WrapMode](/psd/python-net/aspose.psd/wrapmode/) enumeratie die specificeert hoe dit [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object wordt getegeld. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de begrenzende rechthoek voor dit [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object vertegenwoordigt. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Maakt een nieuwe diepe kloon van de huidige [Brush](/psd/python-net/aspose.psd/brush/).

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Brush](/psd/python-net/aspose.psd/brush) | Een nieuwe [Brush](/psd/python-net/aspose.psd/brush/) die de diepe kloon is van deze [Brush](/psd/python-net/aspose.psd/brush/) instantie. |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

Vermenigvuldigt de [Matrix](/psd/python-net/aspose.psd/matrix/) die de lokale geometrische transformatie van deze [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) weergeeft met de opgegeven [Matrix](/psd/python-net/aspose.psd/matrix/) door de opgegeven [Matrix](/psd/python-net/aspose.psd/matrix/) voor te voegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | De [Matrix](/psd/python-net/aspose.psd/matrix/) waarmee de geometrische transformatie moet worden vermenigvuldigd. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

Vermenigvuldigt de [Matrix](/psd/python-net/aspose.psd/matrix/) die de lokale geometrische transformatie van deze [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) weergeeft met de opgegeven [Matrix](/psd/python-net/aspose.psd/matrix/) in de opgegeven volgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | De [Matrix](/psd/python-net/aspose.psd/matrix/) waarmee de geometrische transformatie moet worden vermenigvuldigd. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Een [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) die specificeert in welke volgorde de twee matrices moeten worden vermenigvuldigd. |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid. Deze methode plaatst de rotatie vóór de transformatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| hoek | float | De rotatiehoek. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid in de opgegeven volgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| hoek | float | De rotatiehoek. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Een [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) die specificeert of de rotatiematrix moet worden toegevoegd of vooraf moet worden geplaatst. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

Schaalt de lokale geometrische transformatie met de opgegeven waarden. Deze methode plaatst de schaalmatrix vóór de transformatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| sx | float | De hoeveelheid waarmee de transformatie langs de x-as moet worden geschaald. |
| sy | float | De hoeveelheid waarmee de transformatie langs de y-as moet worden geschaald. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

Schaalt de lokale geometrische transformatie met de opgegeven waarden in de opgegeven volgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| sx | float | De hoeveelheid waarmee de transformatie langs de x-as moet worden geschaald. |
| sy | float | De hoeveelheid waarmee de transformatie langs de y-as moet worden geschaald. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Een [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) die specificeert of de schaalmatrix moet worden toegevoegd of vooraf moet worden geplaatst. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen. Deze methode plaatst de translatie vóór de transformatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| dx | float | De waarde van de translatie in x. |
| dy | float | De waarde van de translatie in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen in de opgegeven volgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| dx | float | De waarde van de translatie in x. |
| dy | float | De waarde van de translatie in y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | De volgorde (voorgaan of toevoegen) waarin de translatie moet worden toegepast. |

