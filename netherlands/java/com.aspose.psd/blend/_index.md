---
title: "Blend"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Definieert een mengpatroon."
type: docs
weight: 11
url: /nl/java/com.aspose.psd/blend/
---

**Inheritance:**
java.lang.Object
```
public final class Blend
```

Definieert een blend‑patroon. Deze klasse kan niet worden geërfd.

Het typische gebruik van de blend‑klasse is het definiëren van een blend‑patroon voor een penseel. Daarom moeten de blend‑eigenschappen zorgvuldig worden geïnitialiseerd. Null‑arrays zijn niet toegestaan. Het penseel zal de juiste uitzondering werpen als de blend‑factoren‑ of posities‑array leeg is of hun lengte niet gelijk is. Als er twee of meer elementen in de posities‑array staan, moet het eerste element 0 zijn en het laatste 1.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Blend()](#Blend--) | Initialiseert een nieuw exemplaar van de  Blend  klasse. |
| [Blend(int count)](#Blend-int-) | Initialiseert een nieuw exemplaar van de  Blend  klasse met het opgegeven aantal factoren en posities. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Test of het opgegeven object een  com.aspose.psd.Blend  klasse is en gelijk is aan deze  com.aspose.psd.Blend  klasse. |
| [getClass()](#getClass--) |  |
| [getFactors()](#getFactors--) | Haalt de array met blend‑factoren voor de gradiënt op. |
| [getPositions()](#getPositions--) | Haalt de array met blend‑posities voor de gradiënt op. |
| [hashCode()](#hashCode--) | Retourneert een hashcode voor dit exemplaar. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFactors(float[] value)](#setFactors-float---) | Stelt de array met blend‑factoren voor de gradiënt in. |
| [setPositions(float[] value)](#setPositions-float---) | Stelt de array met blend‑posities voor de gradiënt in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Blend() {#Blend--}
```
public Blend()
```


Initialiseert een nieuw exemplaar van de  Blend  klasse. Het aantal elementen in de factor‑ en blend‑arrays zal gelijk zijn aan 1.

### Blend(int count) {#Blend-int-}
```
public Blend(int count)
```


Initialiseert een nieuw exemplaar van de  Blend  klasse met het opgegeven aantal factoren en posities.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| count | int | Het aantal elementen in de factor‑ en positie‑arrays. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Test of het opgegeven object een  com.aspose.psd.Blend  klasse is en gelijk is aan deze  com.aspose.psd.Blend  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het object om te testen. |

**Returns:**
boolean - Waar als  obj  een  com.aspose.psd.Blend  klasse is die gelijk is aan deze  com.aspose.psd.Blend  klasse; anders, onwaar.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFactors() {#getFactors--}
```
public float[] getFactors()
```


Haalt de array met blend‑factoren voor de gradiënt op.

**Returns:**
float[] - De array met blend‑factoren die de percentages van de startkleur en eindkleur specificeren die op de overeenkomstige positie worden gebruikt.
### getPositions() {#getPositions--}
```
public float[] getPositions()
```


Haalt de array met blend‑posities voor de gradiënt op.

**Returns:**
float[] - De array met blend‑posities die de percentages van de afstand langs de gradiëntlijn specificeren.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hashcode voor dit exemplaar.

**Returns:**
int - Een hashcode voor deze instantie, geschikt voor gebruik in hash-algoritmen en datastructuren zoals een hashtabel.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setFactors(float[] value) {#setFactors-float---}
```
public void setFactors(float[] value)
```


Stelt de array met blend‑factoren voor de gradiënt in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float[] | De array met blend‑factoren die de percentages van de startkleur en eindkleur specificeren die op de overeenkomstige positie worden gebruikt. |

### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```


Stelt de array met blend‑posities voor de gradiënt in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float[] | De array met blend‑posities die de percentages van de afstand langs de gradiëntlijn specificeren. |

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

