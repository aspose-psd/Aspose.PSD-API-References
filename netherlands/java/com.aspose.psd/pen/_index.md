---
title: "Pen"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Definieert een object dat wordt gebruikt om lijnen, krommen en figuren te tekenen."
type: docs
weight: 77
url: /nl/java/com.aspose.psd/pen/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.TransparencySupporter](../../com.aspose.psd/transparencysupporter)
```
public class Pen extends TransparencySupporter
```

Definieert een object dat wordt gebruikt om lijnen, krommen en figuren te tekenen.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.psd.Color-) | Initialiseert een nieuw exemplaar van de  Pen  klasse met de opgegeven kleur. |
| [Pen(Color color, float width)](#Pen-com.aspose.psd.Color-float-) | Initialiseert een nieuw exemplaar van de  Pen  klasse met de opgegeven  Color  en  Pen.Width  eigenschappen. |
| [Pen(Brush brush)](#Pen-com.aspose.psd.Brush-) | Initialiseert een nieuw exemplaar van de  Pen  klasse met de opgegeven  Brush . |
| [Pen(Brush brush, float width)](#Pen-com.aspose.psd.Brush-float-) | Initialiseert een nieuw exemplaar van de  Pen  klasse met de opgegeven  Brush  en  Pen.Width . |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Haalt de uitlijning op voor deze  Pen . |
| [getBrush()](#getBrush--) | Haalt de  Brush  op die de attributen van deze  Pen  bepaalt. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Haalt de kleur op van deze  Pen . |
| [getCompoundArray()](#getCompoundArray--) | Haalt een array van waarden op die een samengestelde pen specificeert. |
| [getCustomEndCap()](#getCustomEndCap--) | Haalt een aangepast uiteinde op dat wordt gebruikt aan het einde van lijnen getekend met deze  Pen . |
| [getCustomStartCap()](#getCustomStartCap--) | Haalt een aangepast uiteinde op dat wordt gebruikt aan het begin van lijnen getekend met deze  Pen . |
| [getDashCap()](#getDashCap--) | Haalt de uiteindelijke stijl op die wordt gebruikt aan het einde van de streepjes die gestippelde lijnen vormen, getekend met deze  Pen . |
| [getDashOffset()](#getDashOffset--) | Haalt de afstand op van het begin van een lijn tot het begin van een streepjespatroon. |
| [getDashPattern()](#getDashPattern--) | Haalt een array van aangepaste streepjes en spaties op. |
| [getDashStyle()](#getDashStyle--) | Haalt de stijl op die wordt gebruikt voor gestippelde lijnen getekend met deze  Pen . |
| [getEndCap()](#getEndCap--) | Haalt de uiteindelijke stijl op die wordt gebruikt aan het einde van lijnen getekend met deze  Pen . |
| [getLineJoin()](#getLineJoin--) | Haalt de verbindingsstijl op voor de uiteinden van twee opeenvolgende lijnen getekend met deze  Pen . |
| [getMiterLimit()](#getMiterLimit--) | Haalt de limiet op van de dikte van de verbinding op een afgeschuinde hoek. |
| [getOpacity()](#getOpacity--) | Haalt de opacity van het object op. |
| [getPenType()](#getPenType--) | Haalt de stijl van lijnen op die getekend worden met deze  Pen . |
| [getStartCap()](#getStartCap--) | Haalt de uiteindelijke stijl op die wordt gebruikt aan het begin van lijnen getekend met deze  Pen . |
| [getTransform()](#getTransform--) | Haalt een kopie op van de geometrische transformatie voor deze  Pen . |
| [getWidth()](#getWidth--) | Haalt de breedte op van deze  Pen , in eenheden van het Graphics-object dat wordt gebruikt voor tekenen. |
| [hashCode()](#hashCode--) |  |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Vermenigvuldigt de transformatie-matrix voor deze  Pen  met de opgegeven  Matrix . |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Vermenigvuldigt de transformatie-matrix voor deze  Pen  met de opgegeven  Matrix  in de opgegeven volgorde. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Stelt de matrix voor geometrische transformatie van deze Pen opnieuw in op de identiteit. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Roteert de lokale geometrische transformatie met de opgegeven hoek. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Roteert de lokale geometrische transformatie met de opgegeven hoek in de opgegeven volgorde. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Schaalt de lokale geometrische transformatie met de opgegeven factoren. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Schaalt de lokale geometrische transformatie met de opgegeven factoren in de opgegeven volgorde. |
| [setAlignment(int value)](#setAlignment-int-) | Stelt de uitlijning in voor deze Pen. |
| [setBrush(Brush value)](#setBrush-com.aspose.psd.Brush-) | Stelt de Brush in die de attributen van deze Pen bepaalt. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Stelt de kleur van deze Pen in. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Stelt een array van waarden in die een samengestelde pen specificeert. |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.psd.CustomLineCap-) | Stelt een aangepaste kap in die wordt gebruikt aan het einde van lijnen die met deze Pen getekend worden. |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.psd.CustomLineCap-) | Stelt een aangepaste kap in die wordt gebruikt aan het begin van lijnen die met deze Pen getekend worden. |
| [setDashCap(int value)](#setDashCap-int-) | Stelt de kapstijl in die wordt gebruikt aan het einde van de streepjes die gestippelde lijnen vormen die met deze Pen getekend worden. |
| [setDashOffset(float value)](#setDashOffset-float-) | Stelt de afstand in van het begin van een lijn tot het begin van een streepjespatroon. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Stelt een array van aangepaste streepjes en spaties in. |
| [setDashStyle(int value)](#setDashStyle-int-) | Stelt de stijl in die wordt gebruikt voor gestippelde lijnen die met deze Pen getekend worden. |
| [setEndCap(int value)](#setEndCap-int-) | Stelt de kapstijl in die wordt gebruikt aan het einde van lijnen die met deze Pen getekend worden. |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Stelt de waarden in die de stijl van de kap bepalen die wordt gebruikt om lijnen die door deze Pen getekend worden te beëindigen. |
| [setLineJoin(int value)](#setLineJoin-int-) | Stelt de verbindingsstijl in voor de uiteinden van twee opeenvolgende lijnen die met deze Pen getekend worden. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Stelt de limiet in van de dikte van de verbinding op een verstekhoek. |
| [setOpacity(float value)](#setOpacity-float-) | Stelt de opacity van het object in. |
| [setStartCap(int value)](#setStartCap-int-) | Stelt de kapstijl in die wordt gebruikt aan het begin van lijnen die met deze Pen getekend worden. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Stelt een kopie van de geometrische transformatie in voor deze Pen. |
| [setWidth(float value)](#setWidth-float-) | Stelt de breedte van deze Pen in, in eenheden van het Graphics-object dat voor het tekenen wordt gebruikt. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Verschuift de lokale geometrische transformatie met de opgegeven afmetingen. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Verschuift de lokale geometrische transformatie met de opgegeven afmetingen in de opgegeven volgorde. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pen(Color color) {#Pen-com.aspose.psd.Color-}
```
public Pen(Color color)
```


Initialiseert een nieuw exemplaar van de  Pen  klasse met de opgegeven kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Een Color-structuur die de kleur van deze Pen aangeeft. |

### Pen(Color color, float width) {#Pen-com.aspose.psd.Color-float-}
```
public Pen(Color color, float width)
```


Initialiseert een nieuw exemplaar van de  Pen  klasse met de opgegeven  Color  en  Pen.Width  eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Een Color-structuur die de kleur van deze Pen aangeeft. |
| breedte | float | Een waarde die de breedte van deze  Pen  aangeeft. |

### Pen(Brush brush) {#Pen-com.aspose.psd.Brush-}
```
public Pen(Brush brush)
```


Initialiseert een nieuw exemplaar van de  Pen  klasse met de opgegeven  Brush .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Een  Brush  die de vul-eigenschappen van deze  Pen  bepaalt. |

### Pen(Brush brush, float width) {#Pen-com.aspose.psd.Brush-float-}
```
public Pen(Brush brush, float width)
```


Initialiseert een nieuw exemplaar van de  Pen  klasse met de opgegeven  Brush  en  Pen.Width .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Een  Brush  die de kenmerken van deze  Pen  bepaalt. |
| breedte | float | De breedte van de nieuwe  Pen . |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Haalt de uitlijning op voor deze  Pen .

**Returns:**
int - Een  PenAlignment  die de uitlijning voor deze  Pen  weergeeft.
### getBrush() {#getBrush--}
```
public Brush getBrush()
```


Haalt de  Brush  op die de attributen van deze  Pen  bepaalt.

**Returns:**
[Brush](../../com.aspose.psd/brush) - A  Brush  that determines attributes of this  Pen .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


Haalt de kleur op van deze  Pen .

**Returns:**
[Color](../../com.aspose.psd/color) - A  Color  structure that represents the color of this  Pen .
### getCompoundArray() {#getCompoundArray--}
```
public float[] getCompoundArray()
```


Haalt een array van waarden op die een samengestelde pen specificeert. Een samengestelde pen tekent een samengestelde lijn bestaande uit parallelle lijnen en spaties.

**Returns:**
float[] - Een array van reële getallen die de samengestelde array specificeert. De elementen in de array moeten in oplopende volgorde staan, niet kleiner dan 0, en niet groter dan 1.
### getCustomEndCap() {#getCustomEndCap--}
```
public CustomLineCap getCustomEndCap()
```


Haalt een aangepast uiteinde op dat wordt gebruikt aan het einde van lijnen getekend met deze  Pen .

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the end of lines drawn with this  Pen .
### getCustomStartCap() {#getCustomStartCap--}
```
public CustomLineCap getCustomStartCap()
```


Haalt een aangepast uiteinde op dat wordt gebruikt aan het begin van lijnen getekend met deze  Pen .

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the beginning of lines drawn with this  Pen .
### getDashCap() {#getDashCap--}
```
public int getDashCap()
```


Haalt de uiteindelijke stijl op die wordt gebruikt aan het einde van de streepjes die gestippelde lijnen vormen, getekend met deze  Pen .

**Returns:**
int - Een van de  DashCap  waarden die de kapstijl weergeeft die wordt gebruikt aan het begin en einde van de streepjes die gestippelde lijnen vormen die met deze  Pen  worden getekend.
### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


Haalt de afstand op van het begin van een lijn tot het begin van een streepjespatroon.

**Returns:**
float - De afstand van het begin van een lijn tot het begin van een streepjespatroon.
### getDashPattern() {#getDashPattern--}
```
public float[] getDashPattern()
```


Haalt een array van aangepaste streepjes en spaties op.

**Returns:**
float[] - Een array van reële getallen die de lengtes van afwisselende streepjes en spaties in gestippelde lijnen specificeert.
### getDashStyle() {#getDashStyle--}
```
public int getDashStyle()
```


Haalt de stijl op die wordt gebruikt voor gestippelde lijnen getekend met deze  Pen .

**Returns:**
int - Een  DashStyle  die de stijl weergeeft die wordt gebruikt voor gestippelde lijnen die met deze  Pen  worden getekend.
### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


Haalt de uiteindelijke stijl op die wordt gebruikt aan het einde van lijnen getekend met deze  Pen .

**Returns:**
int - Een van de  LineCap  waarden die de kapstijl weergeeft die wordt gebruikt aan het einde van lijnen die met deze  Pen  worden getekend.
### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


Haalt de verbindingsstijl op voor de uiteinden van twee opeenvolgende lijnen getekend met deze  Pen .

**Returns:**
int - Een  LineJoin  die de verbindingsstijl weergeeft voor de uiteinden van twee opeenvolgende lijnen die met deze  Pen  worden getekend.
### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


Haalt de limiet op van de dikte van de verbinding op een afgeschuinde hoek.

**Returns:**
float - De limiet van de dikte van de verbinding op een afgeschuinde hoek.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Haalt de opacity van het object op. De waarde moet tussen 0 en 1 liggen. Een waarde van 0 betekent dat het object volledig zichtbaar is, een waarde van 1 betekent dat het object volledig ondoorzichtig is.

**Returns:**
float - De opacity-waarde.
### getPenType() {#getPenType--}
```
public int getPenType()
```


Haalt de stijl van lijnen op die getekend worden met deze  Pen .

**Returns:**
int - Een  PenType  enumeratie die de stijl van lijnen specificeert die met deze  Pen  worden getekend.
### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


Haalt de uiteindelijke stijl op die wordt gebruikt aan het begin van lijnen getekend met deze  Pen .

**Returns:**
int - Een van de  LineCap  waarden die de kapstijl weergeeft die wordt gebruikt aan het begin van lijnen die met deze  Pen  worden getekend.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Haalt een kopie op van de geometrische transformatie voor deze  Pen .

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Matrix  that represents the geometric transformation for this  Pen .
### getWidth() {#getWidth--}
```
public float getWidth()
```


Haalt de breedte op van deze  Pen , in eenheden van het Graphics-object dat wordt gebruikt voor tekenen.

**Returns:**
float - De breedte van deze  Pen .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Vermenigvuldigt de transformatie-matrix voor deze  Pen  met de opgegeven  Matrix .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Het  Matrix  object waarmee de transformatie-matrix wordt vermenigvuldigd. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Vermenigvuldigt de transformatie-matrix voor deze  Pen  met de opgegeven  Matrix  in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | De  Matrix  waarmee de transformatie-matrix wordt vermenigvuldigd. |
| volgorde | int | De volgorde waarin de vermenigvuldigingsbewerking moet worden uitgevoerd. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Stelt de matrix voor geometrische transformatie van deze Pen opnieuw in op de identiteit.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Roteert de lokale geometrische transformatie met de opgegeven hoek. Deze methode plaatst de rotatie vóór de transformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| angle | float | De rotatiehoek. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Roteert de lokale geometrische transformatie met de opgegeven hoek in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| angle | float | De rotatiehoek. |
| volgorde | int | Een  MatrixOrder  die aangeeft of de rotatiematrix moet worden toegevoegd of voorafgegaan. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Schaalt de lokale geometrische transformatie met de opgegeven factoren. Deze methode plaatst de schaalmatrix vóór de transformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sx | float | De factor waarmee de transformatie in de x-richting wordt geschaald. |
| sy | float | De factor waarmee de transformatie in de y-richting wordt geschaald. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Schaalt de lokale geometrische transformatie met de opgegeven factoren in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sx | float | De factor waarmee de transformatie in de x-richting wordt geschaald. |
| sy | float | De factor waarmee de transformatie in de y-richting wordt geschaald. |
| volgorde | int | Een  MatrixOrder  die specificeert of de schaalmatrix moet worden toegevoegd of voorafgeplaatst. |

### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Stelt de uitlijning in voor deze Pen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Een  PenAlignment  die de uitlijning voor deze  Pen  weergeeft. |

### setBrush(Brush value) {#setBrush-com.aspose.psd.Brush-}
```
public void setBrush(Brush value)
```


Stelt de Brush in die de attributen van deze Pen bepaalt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Brush](../../com.aspose.psd/brush) | Een  Brush  die de attributen van deze  Pen  bepaalt. |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public void setColor(Color value)
```


Stelt de kleur van deze Pen in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Een  Color  structuur die de kleur van deze  Pen  weergeeft. |

### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public void setCompoundArray(float[] value)
```


Stelt een array van waarden in die een samengestelde pen specificeert. Een samengestelde pen tekent een samengestelde lijn bestaande uit parallelle lijnen en spaties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float[] | Een array van reële getallen die de samengestelde array specificeert. De elementen in de array moeten in oplopende volgorde staan, niet kleiner dan 0 en niet groter dan 1. |

### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomEndCap(CustomLineCap value)
```


Stelt een aangepaste kap in die wordt gebruikt aan het einde van lijnen die met deze Pen getekend worden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | Een  CustomLineCap  die de kap aangeeft die wordt gebruikt aan het einde van lijnen die met deze  Pen  zijn getekend. |

### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomStartCap(CustomLineCap value)
```


Stelt een aangepaste kap in die wordt gebruikt aan het begin van lijnen die met deze Pen getekend worden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | Een  CustomLineCap  die de kap aangeeft die wordt gebruikt aan het begin van lijnen die met deze  Pen  zijn getekend. |

### setDashCap(int value) {#setDashCap-int-}
```
public void setDashCap(int value)
```


Stelt de kapstijl in die wordt gebruikt aan het einde van de streepjes die gestippelde lijnen vormen die met deze Pen getekend worden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Een van de  DashCap  waarden die de kapstijl aangeeft die wordt gebruikt aan het begin en einde van de streepjes waaruit gestippelde lijnen getekend met deze  Pen  bestaan. |

### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


Stelt de afstand in van het begin van een lijn tot het begin van een streepjespatroon.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | De afstand van het begin van een lijn tot het begin van een streeppatroon. |

### setDashPattern(float[] value) {#setDashPattern-float---}
```
public void setDashPattern(float[] value)
```


Stelt een array van aangepaste streepjes en spaties in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float[] | Een array van reële getallen die de lengtes van afwisselende streepjes en spaties in gestippelde lijnen specificeert. |

### setDashStyle(int value) {#setDashStyle-int-}
```
public void setDashStyle(int value)
```


Stelt de stijl in die wordt gebruikt voor gestippelde lijnen die met deze Pen getekend worden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Een  DashStyle  die de stijl aangeeft die wordt gebruikt voor gestippelde lijnen getekend met deze  Pen . |

### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


Stelt de kapstijl in die wordt gebruikt aan het einde van lijnen die met deze Pen getekend worden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Een van de  LineCap  waarden die de kapstijl aangeeft die wordt gebruikt aan het einde van lijnen getekend met deze  Pen . |

### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public void setLineCap(int startCap, int endCap, int dashCap)
```


Stelt de waarden in die de stijl van de kap bepalen die wordt gebruikt om lijnen die door deze Pen getekend worden te beëindigen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startCap | int | Een  LineCap  die de kapstijl aangeeft die moet worden gebruikt aan het begin van lijnen getekend met deze  Pen . |
| endCap | int | Een  LineCap  die de kapstijl aangeeft die moet worden gebruikt aan het einde van lijnen getekend met deze  Pen . |
| dashCap | int | Een  LineCap  die de kapstijl aangeeft die moet worden gebruikt aan het begin of einde van gestippelde lijnen getekend met deze  Pen . |

### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


Stelt de verbindingsstijl in voor de uiteinden van twee opeenvolgende lijnen die met deze Pen getekend worden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Een  LineJoin  die de verbindingsstijl aangeeft voor de uiteinden van twee opeenvolgende lijnen getekend met deze  Pen . |

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


Stelt de limiet in van de dikte van de verbinding op een verstekhoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | De limiet van de dikte van de verbinding op een verstekhoek. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Stelt de opacity van het object in. De waarde moet tussen 0 en 1 liggen. Een waarde van 0 betekent dat het object volledig zichtbaar is, een waarde van 1 betekent dat het object volledig ondoorzichtig is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | De opacity-waarde. |

### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


Stelt de kapstijl in die wordt gebruikt aan het begin van lijnen die met deze Pen getekend worden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Een van de  LineCap  waarden die de kapstijl aangeeft die wordt gebruikt aan het begin van lijnen getekend met deze  Pen . |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Stelt een kopie van de geometrische transformatie in voor deze Pen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | Een kopie van de  Matrix  die de geometrische transformatie voor deze  Pen  weergeeft. |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Stelt de breedte van deze Pen in, in eenheden van het Graphics-object dat voor het tekenen wordt gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | De breedte van deze  Pen . |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen. Deze methode plaatst de translatie vooraan in de transformatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dx | float | De waarde van de translatie in x. |
| dy | float | De waarde van de translatie in y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Verschuift de lokale geometrische transformatie met de opgegeven afmetingen in de opgegeven volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dx | float | De waarde van de translatie in x. |
| dy | float | De waarde van de translatie in y. |
| volgorde | int | De volgorde (voorgaan of toevoegen) waarin de translatie moet worden toegepast. |

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

