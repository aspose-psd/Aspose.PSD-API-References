---
title: "Pen"
second_title: "Aspose.PSD för Java API-referens"
description: "Definierar ett objekt som används för att rita linjer, kurvor och figurer."
type: docs
weight: 77
url: /sv/java/com.aspose.psd/pen/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.TransparencySupporter](../../com.aspose.psd/transparencysupporter)
```
public class Pen extends TransparencySupporter
```

Definierar ett objekt som används för att rita linjer, kurvor och figurer.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.psd.Color-) | Initierar en ny instans av  Pen  -klassen med den angivna färgen. |
| [Pen(Color color, float width)](#Pen-com.aspose.psd.Color-float-) | Initierar en ny instans av  Pen  -klassen med de angivna  Color  och  Pen.Width  egenskaperna. |
| [Pen(Brush brush)](#Pen-com.aspose.psd.Brush-) | Initierar en ny instans av  Pen  -klassen med den angivna  Brush  . |
| [Pen(Brush brush, float width)](#Pen-com.aspose.psd.Brush-float-) | Initierar en ny instans av  Pen  -klassen med den angivna  Brush  och  Pen.Width  . |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Hämtar justeringen för denna  Pen  . |
| [getBrush()](#getBrush--) | Hämtar  Brush  som bestämmer attribut för denna  Pen  . |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Hämtar färgen på denna  Pen  . |
| [getCompoundArray()](#getCompoundArray--) | Hämtar en array med värden som specificerar en sammansatt penna. |
| [getCustomEndCap()](#getCustomEndCap--) | Hämtar en anpassad ändkappa att använda i slutet av linjer som ritas med denna  Pen  . |
| [getCustomStartCap()](#getCustomStartCap--) | Hämtar en anpassad startkappa att använda i början av linjer som ritas med denna  Pen  . |
| [getDashCap()](#getDashCap--) | Hämtar kappstilen som används i slutet av de streck som bildar streckade linjer rita med denna  Pen  . |
| [getDashOffset()](#getDashOffset--) | Hämtar avståndet från början av en linje till början av ett streckmönster. |
| [getDashPattern()](#getDashPattern--) | Hämtar en array med anpassade streck och mellanslag. |
| [getDashStyle()](#getDashStyle--) | Hämtar stilen som används för streckade linjer rita med denna  Pen  . |
| [getEndCap()](#getEndCap--) | Hämtar kappstilen som används i slutet av linjer rita med denna  Pen  . |
| [getLineJoin()](#getLineJoin--) | Hämtar fogstilen för ändarna på två på varandra följande linjer rita med denna  Pen  . |
| [getMiterLimit()](#getMiterLimit--) | Hämtar gränsen för tjockleken på fogen på ett snedställt hörn. |
| [getOpacity()](#getOpacity--) | Hämtar objektets opacitet. |
| [getPenType()](#getPenType--) | Hämtar stilen på linjer rita med denna  Pen  . |
| [getStartCap()](#getStartCap--) | Hämtar kappstilen som används i början av linjer rita med denna  Pen  . |
| [getTransform()](#getTransform--) | Hämtar en kopia av den geometriska transformationen för denna  Pen  . |
| [getWidth()](#getWidth--) | Hämtar bredden på detta  Pen , i enheter av Graphics-objektet som används för ritning. |
| [hashCode()](#hashCode--) |  |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Multiplicerar transformationsmatrisen för detta  Pen  med den angivna  Matrix . |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Multiplicerar transformationsmatrisen för detta  Pen  med den angivna  Matrix  i den angivna ordningen. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Återställer den geometriska transformationsmatrisen för detta  Pen  till identitet. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Rotera den lokala geometriska transformationen med den angivna vinkeln. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Rotera den lokala geometriska transformationen med den angivna vinkeln i den angivna ordningen. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Skalar den lokala geometriska transformationen med de angivna faktorerna. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Skalar den lokala geometriska transformationen med de angivna faktorerna i den angivna ordningen. |
| [setAlignment(int value)](#setAlignment-int-) | Ställer in justeringen för detta  Pen . |
| [setBrush(Brush value)](#setBrush-com.aspose.psd.Brush-) | Ställer in  Brush  som bestämmer attributen för detta  Pen . |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Ställer in färgen på detta  Pen . |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Ställer in en array av värden som specificerar en sammansatt pen. |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.psd.CustomLineCap-) | Ställer in en anpassad spets att använda i slutet av linjer som ritas med detta  Pen . |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.psd.CustomLineCap-) | Ställer in en anpassad spets att använda i början av linjer som ritas med detta  Pen . |
| [setDashCap(int value)](#setDashCap-int-) | Ställer in spetsstilen som används i slutet av strecken som bildar streckade linjer ritat med detta  Pen . |
| [setDashOffset(float value)](#setDashOffset-float-) | Ställer in avståndet från början av en linje till början av ett streckmönster. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Ställer in en array av anpassade streck och mellanslag. |
| [setDashStyle(int value)](#setDashStyle-int-) | Ställer in stilen som används för streckade linjer ritat med detta  Pen . |
| [setEndCap(int value)](#setEndCap-int-) | Ställer in spetsstilen som används i slutet av linjer ritat med detta  Pen . |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Ställer in värdena som bestämmer spetsstilen som används för att avsluta linjer ritat av detta  Pen . |
| [setLineJoin(int value)](#setLineJoin-int-) | Ställer in fogstilen för ändarna på två på varandra följande linjer ritat med detta  Pen . |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Ställer in gränsen för tjockleken på fogen på ett snedställd hörn. |
| [setOpacity(float value)](#setOpacity-float-) | Ställer in objektets opacitet. |
| [setStartCap(int value)](#setStartCap-int-) | Ställer in spetsstilen som används i början av linjer ritat med detta  Pen . |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Ställer in en kopia av den geometriska transformationen för detta  Pen . |
| [setWidth(float value)](#setWidth-float-) | Ställer in bredden på detta  Pen , i enheter av Graphics-objektet som används för ritning. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Översätter den lokala geometriska transformationen med de angivna dimensionerna. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pen(Color color) {#Pen-com.aspose.psd.Color-}
```
public Pen(Color color)
```


Initierar en ny instans av  Pen  -klassen med den angivna färgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | En  Color  struktur som indikerar färgen på denna  Pen . |

### Pen(Color color, float width) {#Pen-com.aspose.psd.Color-float-}
```
public Pen(Color color, float width)
```


Initierar en ny instans av  Pen  -klassen med de angivna  Color  och  Pen.Width  egenskaperna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | En  Color  struktur som indikerar färgen på denna  Pen . |
| bredd | float | Ett värde som indikerar bredden på denna  Pen . |

### Pen(Brush brush) {#Pen-com.aspose.psd.Brush-}
```
public Pen(Brush brush)
```


Initierar en ny instans av  Pen  -klassen med den angivna  Brush  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | En  Brush  som bestämmer fyllningsegenskaperna för denna  Pen . |

### Pen(Brush brush, float width) {#Pen-com.aspose.psd.Brush-float-}
```
public Pen(Brush brush, float width)
```


Initierar en ny instans av  Pen  -klassen med den angivna  Brush  och  Pen.Width  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | En  Brush  som bestämmer egenskaperna för denna  Pen . |
| bredd | float | Bredden på den nya  Pen . |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Hämtar justeringen för denna  Pen  .

**Returns:**
int - En  PenAlignment  som representerar justeringen för denna  Pen .
### getBrush() {#getBrush--}
```
public Brush getBrush()
```


Hämtar  Brush  som bestämmer attribut för denna  Pen  .

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


Hämtar färgen på denna  Pen  .

**Returns:**
[Color](../../com.aspose.psd/color) - A  Color  structure that represents the color of this  Pen .
### getCompoundArray() {#getCompoundArray--}
```
public float[] getCompoundArray()
```


Hämtar en array av värden som specificerar en sammansatt penna. En sammansatt penna ritar en sammansatt linje bestående av parallella linjer och mellanrum.

**Returns:**
float[] - En array av reella tal som specificerar den sammansatta arrayen. Elementen i arrayen måste vara i stigande ordning, inte mindre än 0 och inte större än 1.
### getCustomEndCap() {#getCustomEndCap--}
```
public CustomLineCap getCustomEndCap()
```


Hämtar en anpassad ändkappa att använda i slutet av linjer som ritas med denna  Pen  .

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the end of lines drawn with this  Pen .
### getCustomStartCap() {#getCustomStartCap--}
```
public CustomLineCap getCustomStartCap()
```


Hämtar en anpassad startkappa att använda i början av linjer som ritas med denna  Pen  .

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the beginning of lines drawn with this  Pen .
### getDashCap() {#getDashCap--}
```
public int getDashCap()
```


Hämtar kappstilen som används i slutet av de streck som bildar streckade linjer rita med denna  Pen  .

**Returns:**
int - Ett av  DashCap  värdena som representerar kapstilen som används i början och slutet av strecken som utgör streckade linjer ritade med denna  Pen .
### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


Hämtar avståndet från början av en linje till början av ett streckmönster.

**Returns:**
float - Avståndet från början av en linje till början av ett streckmönster.
### getDashPattern() {#getDashPattern--}
```
public float[] getDashPattern()
```


Hämtar en array med anpassade streck och mellanslag.

**Returns:**
float[] - En array av reella tal som specificerar längderna på alternerande streck och mellanrum i streckade linjer.
### getDashStyle() {#getDashStyle--}
```
public int getDashStyle()
```


Hämtar stilen som används för streckade linjer rita med denna  Pen  .

**Returns:**
int - En  DashStyle  som representerar stilen som används för streckade linjer ritade med denna  Pen .
### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


Hämtar kappstilen som används i slutet av linjer rita med denna  Pen  .

**Returns:**
int - Ett av  LineCap  värdena som representerar kapstilen som används i slutet av linjer ritade med denna  Pen .
### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


Hämtar fogstilen för ändarna på två på varandra följande linjer rita med denna  Pen  .

**Returns:**
int - En  LineJoin  som representerar sammanfogningsstilen för ändarna på två på varandra följande linjer ritade med denna  Pen .
### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


Hämtar gränsen för tjockleken på fogen på ett snedställt hörn.

**Returns:**
float - Gränsen för tjockleken på sammanfogningen i ett snedställd hörn.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Hämtar objektets opacitet. Värdet bör vara mellan 0 och 1. Ett värde på 0 betyder att objektet är helt synligt, ett värde på 1 betyder att objektet är helt ogenomskinligt.

**Returns:**
float - Opacitetsvärdet.
### getPenType() {#getPenType--}
```
public int getPenType()
```


Hämtar stilen på linjer rita med denna  Pen  .

**Returns:**
int - En  PenType  enumeration som specificerar stilen på linjer ritade med denna  Pen .
### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


Hämtar kappstilen som används i början av linjer rita med denna  Pen  .

**Returns:**
int - Ett av  LineCap  värdena som representerar kapstilen som används i början av linjer ritade med denna  Pen .
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Hämtar en kopia av den geometriska transformationen för denna  Pen  .

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Matrix  that represents the geometric transformation for this  Pen .
### getWidth() {#getWidth--}
```
public float getWidth()
```


Hämtar bredden på detta  Pen , i enheter av Graphics-objektet som används för ritning.

**Returns:**
float - Bredden på denna  Pen .
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


Multiplicerar transformationsmatrisen för detta  Pen  med den angivna  Matrix .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Det  Matrix  objektet som ska multipliceras med transformationsmatrisen. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplicerar transformationsmatrisen för detta  Pen  med den angivna  Matrix  i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Det  Matrix  som ska multipliceras med transformationsmatrisen. |
| ordning | int | Ordningen i vilken multiplikationsoperationen ska utföras. |

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


Återställer den geometriska transformationsmatrisen för detta  Pen  till identitet.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Roterar den lokala geometriska transformationen med den angivna vinkeln. Denna metod lägger till rotationen före transformationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Rotera den lokala geometriska transformationen med den angivna vinkeln i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln. |
| ordning | int | En  MatrixOrder  som specificerar om rotationsmatrisen ska läggas till i slutet eller i början. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Skalar den lokala geometriska transformationen med de angivna faktorerna. Denna metod lägger till skalningsmatrisen före transformationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sx | float | Faktorn som används för att skala transformationen i x‑axelns riktning. |
| sy | float | Faktorn som används för att skala transformationen i y‑axelns riktning. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Skalar den lokala geometriska transformationen med de angivna faktorerna i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sx | float | Faktorn som används för att skala transformationen i x‑axelns riktning. |
| sy | float | Faktorn som används för att skala transformationen i y‑axelns riktning. |
| ordning | int | En MatrixOrder som specificerar om skalningsmatrisen ska läggas till eller föregås. |

### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Ställer in justeringen för detta  Pen .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | En PenAlignment som representerar justeringen för denna Pen. |

### setBrush(Brush value) {#setBrush-com.aspose.psd.Brush-}
```
public void setBrush(Brush value)
```


Ställer in  Brush  som bestämmer attributen för detta  Pen .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Brush](../../com.aspose.psd/brush) | En Brush som bestämmer attributen för denna Pen. |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public void setColor(Color value)
```


Ställer in färgen på detta  Pen .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | En Color‑struktur som representerar färgen på denna Pen. |

### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public void setCompoundArray(float[] value)
```


Ställer in en värdearray som specificerar en sammansatt penna. En sammansatt penna ritar en sammansatt linje bestående av parallella linjer och mellanrum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float[] | En array av reella tal som specificerar den sammansatta arrayen. Elementen i arrayen måste vara i stigande ordning, inte mindre än 0 och inte större än 1. |

### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomEndCap(CustomLineCap value)
```


Ställer in en anpassad spets att använda i slutet av linjer som ritas med detta  Pen .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | En CustomLineCap som representerar änden som används i slutet av linjer som ritas med denna Pen. |

### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomStartCap(CustomLineCap value)
```


Ställer in en anpassad spets att använda i början av linjer som ritas med detta  Pen .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | En CustomLineCap som representerar änden som används i början av linjer som ritas med denna Pen. |

### setDashCap(int value) {#setDashCap-int-}
```
public void setDashCap(int value)
```


Ställer in spetsstilen som används i slutet av strecken som bildar streckade linjer ritat med detta  Pen .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Ett av DashCap‑värdena som representerar kapstil som används i början och slutet av strecken som utgör streckade linjer ritat med denna Pen. |

### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


Ställer in avståndet från början av en linje till början av ett streckmönster.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Avståndet från början av en linje till starten av ett streckmönster. |

### setDashPattern(float[] value) {#setDashPattern-float---}
```
public void setDashPattern(float[] value)
```


Ställer in en array av anpassade streck och mellanslag.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float[] | En array av reella tal som specificerar längderna på alternerande streck och mellanslag i streckade linjer. |

### setDashStyle(int value) {#setDashStyle-int-}
```
public void setDashStyle(int value)
```


Ställer in stilen som används för streckade linjer ritat med detta  Pen .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | En DashStyle som representerar stilen som används för streckade linjer ritat med denna Pen. |

### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


Ställer in spetsstilen som används i slutet av linjer ritat med detta  Pen .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Ett av LineCap‑värdena som representerar kapstilen som används i slutet av linjer ritat med denna Pen. |

### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public void setLineCap(int startCap, int endCap, int dashCap)
```


Ställer in värdena som bestämmer spetsstilen som används för att avsluta linjer ritat av detta  Pen .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startCap | int | En LineCap som representerar kapstilen att använda i början av linjer ritat med denna Pen. |
| endCap | int | En LineCap som representerar kapstilen att använda i slutet av linjer ritat med denna Pen. |
| dashCap | int | En LineCap som representerar kapstilen att använda i början eller slutet av streckade linjer ritat med denna Pen. |

### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


Ställer in fogstilen för ändarna på två på varandra följande linjer ritat med detta  Pen .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | En LineJoin som representerar sammanfogningsstilen för ändarna på två på varandra följande linjer ritat med denna Pen. |

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


Ställer in gränsen för tjockleken på fogen på ett snedställd hörn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Gränsen för tjockleken på fogen i ett snedkantigt hörn. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Ställer in objektets opacitet. Värdet bör vara mellan 0 och 1. Ett värde på 0 betyder att objektet är helt synligt, ett värde på 1 betyder att objektet är helt ogenomskinligt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Opacitetsvärdet. |

### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


Ställer in spetsstilen som används i början av linjer ritat med detta  Pen .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Ett av LineCap‑värdena som representerar kapstilen som används i början av linjer ritat med denna Pen. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Ställer in en kopia av den geometriska transformationen för detta  Pen .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | En kopia av Matrix som representerar den geometriska transformationen för denna Pen. |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Ställer in bredden på detta  Pen , i enheter av Graphics-objektet som används för ritning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Bredden på denna Pen. |

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


Översätter den lokala geometriska transformationen med de angivna dimensionerna. Denna metod lägger till translationen i början av transformationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | float | Värdet för översättningen i x. |
| dy | float | Värdet för översättningen i y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | float | Värdet för översättningen i x. |
| dy | float | Värdet för översättningen i y. |
| ordning | int | Ordningen (infoga i början eller i slutet) i vilken översättningen ska tillämpas. |

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

