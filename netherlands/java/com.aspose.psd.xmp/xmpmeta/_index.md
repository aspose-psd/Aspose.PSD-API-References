---
title: "XmpMeta"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Stelt xmpmeta voor."
type: docs
weight: 17
url: /nl/java/com.aspose.psd.xmp/xmpmeta/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpMeta extends XmpElementBase implements IXmlValue, System.IEquatable<XmpElementBase>
```

Stelt xmpmeta voor. Optioneel. Het doel van dit element is om XMP-metadata te identificeren binnen algemene XML-tekst die mogelijk andere niet-XMP-toepassingen van RDF bevat.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [XmpMeta(String toolkitVersion)](#XmpMeta-java.lang.String-) | Initialiseert een nieuw exemplaar van de  XmpMeta  klasse. |
| [XmpMeta()](#XmpMeta--) | Initialiseert een nieuw exemplaar van de  XmpMeta  klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Voegt het attribuut toe. |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | Wijst het opgegeven XMP-element toe aan het huidige. |
| [clearAttributes()](#clearAttributes--) | Verwijdert alle attributen. |
| [deepClone_internalized()](#deepClone-internalized--) | Kloont deze instantie. |
| [equals(Object other)](#equals-java.lang.Object-) | Bepaalt of het opgegeven  System.Object , gelijk is aan dit exemplaar. |
| [getAdobeXmpToolkit()](#getAdobeXmpToolkit--) | Haalt of stelt de Adobe Xmp toolkit-versie in. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Haalt het attribuut op. |
| [getClass()](#getClass--) |  |
| [getXmlValue()](#getXmlValue--) | Converteert XMP-waarde naar de XML-representatie. |
| [hashCode()](#hashCode--) | Retourneert een hashcode voor dit exemplaar. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | Geeft aan of het huidige object gelijk is aan een ander object van hetzelfde type. |
| [isEquals(XmpMeta other)](#isEquals-com.aspose.psd.xmp.XmpMeta-) | Geeft aan of het huidige object gelijk is aan een ander object van hetzelfde type. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAdobeXmpToolkit(String value)](#setAdobeXmpToolkit-java.lang.String-) | Haalt of stelt de Adobe Xmp toolkit-versie in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpMeta(String toolkitVersion) {#XmpMeta-java.lang.String-}
```
public XmpMeta(String toolkitVersion)
```


Initialiseert een nieuw exemplaar van de  XmpMeta  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| toolkitVersion | java.lang.String | Adobe XMP toolkit-versie. |

### XmpMeta() {#XmpMeta--}
```
public XmpMeta()
```


Initialiseert een nieuw exemplaar van de  XmpMeta  klasse.

### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


Voegt het attribuut toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| attribuut | java.lang.String | Het attribuut. |
| waarde | java.lang.String | De waarde. |

### assign_internalized(XmpElementBase xmpElement) {#assign-internalized-com.aspose.psd.xmp.XmpElementBase-}
```
public void assign_internalized(XmpElementBase xmpElement)
```


Wijst het opgegeven XMP-element toe aan het huidige.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xmpElement | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | Het XMP-element. |

### clearAttributes() {#clearAttributes--}
```
public void clearAttributes()
```


Verwijdert alle attributen.

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpElementBase deepClone_internalized()
```


Kloont deze instantie.

**Returns:**
[XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) - The cloned object
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Bepaalt of het opgegeven  System.Object , gelijk is aan dit exemplaar.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| anders | java.lang.Object | Het  System.Object  om te vergelijken met dit exemplaar. |

**Returns:**
boolean -  true  als het opgegeven  System.Object  gelijk is aan deze instantie; anders,  false .
### getAdobeXmpToolkit() {#getAdobeXmpToolkit--}
```
public String getAdobeXmpToolkit()
```


Haalt of stelt de Adobe Xmp toolkit-versie in.

**Returns:**
java.lang.String
### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public String getAttribute(String attribute)
```


Haalt het attribuut op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| attribuut | java.lang.String | Het attribuut. |

**Returns:**
java.lang.String - Retourneert het attribuut voor de opgegeven attribuutnaam.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converteert XMP-waarde naar de XML-representatie.

**Returns:**
java.lang.String - Retourneert de XMP-waarde geconverteerd naar de XML-representatie.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hashcode voor dit exemplaar.

**Returns:**
int - Een hashcode voor deze instantie, geschikt voor gebruik in hash-algoritmen en datastructuren zoals een hashtabel.
### isEquals(XmpElementBase other) {#isEquals-com.aspose.psd.xmp.XmpElementBase-}
```
public boolean isEquals(XmpElementBase other)
```


Geeft aan of het huidige object gelijk is aan een ander object van hetzelfde type.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | Een object om te vergelijken met dit object. |

**Returns:**
boolean - true als het huidige object gelijk is aan de  other  parameter; anders, false.
### isEquals(XmpMeta other) {#isEquals-com.aspose.psd.xmp.XmpMeta-}
```
public boolean isEquals(XmpMeta other)
```


Geeft aan of het huidige object gelijk is aan een ander object van hetzelfde type.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | Een object om te vergelijken met dit object. |

**Returns:**
boolean - true als het huidige object gelijk is aan de  other  parameter; anders, false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAdobeXmpToolkit(String value) {#setAdobeXmpToolkit-java.lang.String-}
```
public void setAdobeXmpToolkit(String value)
```


Haalt of stelt de Adobe Xmp toolkit-versie in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

