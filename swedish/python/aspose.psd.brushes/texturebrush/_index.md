---
title: "TextureBrush-klass"
type: docs
weight: 90
url: /sv/python-net/aspose.psd.brushes/texturebrush/
---

**Summary:** Each property of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class is a [Brush](/psd/python-net/aspose.psd/brush/) object that uses an image to fill the interior of a shape. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.TextureBrush

**Inheritance:** TransformBrush

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [TextureBrush(image)](#TextureBrush_image_1) | Initierar en ny instans av klassen [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) som använder den angivna bilden. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_2) | Initierar en ny instans av klassen [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) som använder den angivna bilden och den avgränsande rektangeln. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_3) | Initierar en ny instans av klassen [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) som använder den angivna bilden och den avgränsande rektangeln. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_4) | Initierar en ny instans av klassen [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) som använder den angivna bilden, den avgränsande rektangeln och bildattributen. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_5) | Initierar en ny instans av klassen [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) som använder den angivna bilden, den avgränsande rektangeln och bildattributen. |
| [TextureBrush(image, wrap_mode)](#TextureBrush_image_wrap_mode_6) | Initierar en ny instans av klassen [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) som använder den angivna bilden och wrap‑läget. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_7) | Initierar en ny instans av klassen [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) som använder den angivna bilden, wrap‑läget och den avgränsande rektangeln. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_8) | Initierar en ny instans av klassen [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) som använder den angivna bilden, wrap‑läget och den avgränsande rektangeln. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| borttagen | bool | r | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| image | [Image](/psd/python-net/aspose.psd/image) | r | Hämtar [Image](/psd/python-net/aspose.psd/image/)‑objektet som är associerat med detta [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑objekt. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | r | Hämtar [TextureBrush.image_attributes](/psd/python-net/aspose.psd.brushes/texturebrush/) som är associerat med detta [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| image_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Hämtar [Rectangle](/psd/python-net/aspose.psd/rectangle/) som är associerat med detta [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| is_transform_changed | bool | r | Hämtar ett värde som indikerar om transformationer har ändrats på något sätt. Till exempel genom att sätta transformationsmatrisen eller<br/>            anropa någon av metoderna som ändrar transformationsmatrisen. Egenskapen introducerades för bakåtkompatibilitet med GDI+. |
| opacity | float | r/w | Hämtar eller anger penselns opacitet. Värdet bör vara mellan 0 och 1. Värdet 0 betyder att penseln är helt synlig, värdet 1 betyder att penseln är helt ogenomskinlig. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Hämtar eller anger en kopia av [Matrix](/psd/python-net/aspose.psd/matrix/) som definierar en lokal geometrisk transformation för denna [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | r/w | Hämtar eller anger en [WrapMode](/psd/python-net/aspose.psd/wrapmode/)‑enumeration som indikerar omslagsläget för denna [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Skapar en ny djupklon av den aktuella [Brush](/psd/python-net/aspose.psd/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | Multiplicerar [Matrix](/psd/python-net/aspose.psd/matrix/) som representerar den lokala geometriska transformationen för denna [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) med den angivna [Matrix](/psd/python-net/aspose.psd/matrix/) genom att föregå den angivna [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | Multiplicerar [Matrix](/psd/python-net/aspose.psd/matrix/) som representerar den lokala geometriska transformationen för denna [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) med den angivna [Matrix](/psd/python-net/aspose.psd/matrix/) i den angivna ordningen. |
| reset_transform() | Återställer egenskapen [TransformBrush.transform](/psd/python-net/aspose.psd.brushes/transformbrush/) till identitet. |
| [rotate_transform(angle)](#rotate_transform_angle_4) | Rotera den lokala geometriska transformationen med den angivna mängden. Denna metod föregår rotationen till transformationen. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | Rotera den lokala geometriska transformationen med den angivna mängden i den angivna ordningen. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | Skalar den lokala geometriska transformationen med de angivna värdena. Denna metod föregår skalningsmatrisen till transformationen. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | Skalar den lokala geometriska transformationen med de angivna värdena i den angivna ordningen. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Översätter den lokala geometriska transformationen med de angivna dimensionerna. Denna metod föregår översättningen till transformationen. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen. |


### Constructor: TextureBrush(image) {#TextureBrush_image_1}


```
 TextureBrush(image) 
```

Initierar en ny instans av klassen [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) som använder den angivna bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Det [Image](/psd/python-net/aspose.psd/image/)‑objekt som detta [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑objekt fyller interiörer med. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_2}


```
 TextureBrush(image, destination_rectangle) 
```

Initierar en ny instans av klassen [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) som använder den angivna bilden och den avgränsande rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Det [Image](/psd/python-net/aspose.psd/image/)‑objekt som detta [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑objekt fyller interiörer med. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | En [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som representerar den avgränsande rektangeln för detta [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑objekt. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_3}


```
 TextureBrush(image, destination_rectangle) 
```

Initierar en ny instans av klassen [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) som använder den angivna bilden och den avgränsande rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Det [Image](/psd/python-net/aspose.psd/image/)‑objekt som detta [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑objekt fyller interiörer med. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | En [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som representerar den avgränsande rektangeln för detta [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑objekt. |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_4}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Initierar en ny instans av klassen [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) som använder den angivna bilden, den avgränsande rektangeln och bildattributen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Det [Image](/psd/python-net/aspose.psd/image/)‑objekt som detta [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑objekt fyller interiörer med. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | En [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som representerar den avgränsande rektangeln för detta [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑objekt. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Ett [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/)‑objekt som innehåller ytterligare information om bilden som används av detta [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑objekt. |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_5}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Initierar en ny instans av klassen [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) som använder den angivna bilden, den avgränsande rektangeln och bildattributen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Det [Image](/psd/python-net/aspose.psd/image/)‑objekt som detta [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑objekt fyller interiörer med. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | En [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som representerar den avgränsande rektangeln för detta [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑objekt. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Ett [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/)‑objekt som innehåller ytterligare information om bilden som används av detta [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑objekt. |

### Constructor: TextureBrush(image, wrap_mode) {#TextureBrush_image_wrap_mode_6}


```
 TextureBrush(image, wrap_mode) 
```

Initierar en ny instans av klassen [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) som använder den angivna bilden och wrap‑läget.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Det [Image](/psd/python-net/aspose.psd/image/)‑objekt som detta [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑objekt fyller interiörer med. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | En [WrapMode](/psd/python-net/aspose.psd/wrapmode/)‑enumeration som specificerar hur detta [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑objekt upprepas. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_7}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Initierar en ny instans av klassen [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) som använder den angivna bilden, wrap‑läget och den avgränsande rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Det [Image](/psd/python-net/aspose.psd/image/)‑objekt som detta [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑objekt fyller interiörer med. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | En [WrapMode](/psd/python-net/aspose.psd/wrapmode/)‑enumeration som specificerar hur detta [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑objekt upprepas. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | En [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som representerar den avgränsande rektangeln för detta [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑objekt. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_8}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Initierar en ny instans av klassen [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) som använder den angivna bilden, wrap‑läget och den avgränsande rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Det [Image](/psd/python-net/aspose.psd/image/)‑objekt som detta [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑objekt fyller interiörer med. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | En [WrapMode](/psd/python-net/aspose.psd/wrapmode/)‑enumeration som specificerar hur detta [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑objekt upprepas. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | En [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som representerar den avgränsande rektangeln för detta [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/)‑objekt. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Skapar en ny djupklon av den aktuella [Brush](/psd/python-net/aspose.psd/brush/).

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Brush](/psd/python-net/aspose.psd/brush) | En ny [Brush](/psd/python-net/aspose.psd/brush/) som är den djupa klonen av denna [Brush](/psd/python-net/aspose.psd/brush/) instans. |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

Multiplicerar [Matrix](/psd/python-net/aspose.psd/matrix/) som representerar den lokala geometriska transformationen för denna [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) med den angivna [Matrix](/psd/python-net/aspose.psd/matrix/) genom att föregå den angivna [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Den [Matrix](/psd/python-net/aspose.psd/matrix/) som används för att multiplicera den geometriska transformen. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

Multiplicerar [Matrix](/psd/python-net/aspose.psd/matrix/) som representerar den lokala geometriska transformationen för denna [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) med den angivna [Matrix](/psd/python-net/aspose.psd/matrix/) i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Den [Matrix](/psd/python-net/aspose.psd/matrix/) som används för att multiplicera den geometriska transformen. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | En [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) som specificerar i vilken ordning de två matriserna ska multipliceras. |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

Rotera den lokala geometriska transformationen med den angivna mängden. Denna metod föregår rotationen till transformationen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Vinkeln för rotationen. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

Rotera den lokala geometriska transformationen med den angivna mängden i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Vinkeln för rotationen. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | En [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) som specificerar om rotationsmatrisen ska läggas till i slutet eller i början. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

Skalar den lokala geometriska transformationen med de angivna värdena. Denna metod föregår skalningsmatrisen till transformationen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sx | float | Mängden med vilken transformen ska skalas i x-axelns riktning. |
| sy | float | Mängden med vilken transformen ska skalas i y-axelns riktning. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

Skalar den lokala geometriska transformationen med de angivna värdena i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sx | float | Mängden med vilken transformen ska skalas i x-axelns riktning. |
| sy | float | Mängden med vilken transformen ska skalas i y-axelns riktning. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | En [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) som specificerar om skalningsmatrisen ska läggas till i slutet eller i början. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

Översätter den lokala geometriska transformationen med de angivna dimensionerna. Denna metod föregår översättningen till transformationen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dx | float | Värdet för translationen i x. |
| dy | float | Värdet för translationen i y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dx | float | Värdet för translationen i x. |
| dy | float | Värdet för translationen i y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ordningen (infoga före eller efter) i vilken translationen ska tillämpas. |

