---
title: "Blend"
second_title: "Aspose.PSD för Java API-referens"
description: "Definierar ett blandningsmönster."
type: docs
weight: 11
url: /sv/java/com.aspose.psd/blend/
---

**Inheritance:**
java.lang.Object
```
public final class Blend
```

Definierar ett blandningsmönster. Denna klass kan inte ärvas.

Den typiska användningen av blend-klassen är att definiera ett blandningsmönster för penseln. Därför bör blend‑egenskaperna initieras noggrant. Null‑arrayer är inte tillåtna. Penseln kommer att kasta ett lämpligt undantag om blend‑faktorer eller positionsarray är tomma eller deras längd inte är densamma. Om det finns två eller fler element i positionsarrayen ska det första elementet vara 0 och det sista vara 1.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Blend()](#Blend--) | Initierar en ny instans av klassen  Blend  . |
| [Blend(int count)](#Blend-int-) | Initierar en ny instans av klassen  Blend  med det angivna antalet faktorer och positioner. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Testar om det angivna objektet är en  com.aspose.psd.Blend  klass och är ekvivalent med denna  com.aspose.psd.Blend  klass. |
| [getClass()](#getClass--) |  |
| [getFactors()](#getFactors--) | Hämtar arrayen med blend‑faktorer för gradienten. |
| [getPositions()](#getPositions--) | Hämtar arrayen med blend‑positioner för gradienten. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för den här instansen. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFactors(float[] value)](#setFactors-float---) | Ställer in arrayen med blend‑faktorer för gradienten. |
| [setPositions(float[] value)](#setPositions-float---) | Ställer in arrayen med blend‑positioner för gradienten. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Blend() {#Blend--}
```
public Blend()
```


Initierar en ny instans av klassen  Blend . Antalet element i faktor‑ och blend‑arrayerna kommer att vara lika med 1.

### Blend(int count) {#Blend-int-}
```
public Blend(int count)
```


Initierar en ny instans av klassen  Blend  med det angivna antalet faktorer och positioner.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| count | int | Antalet element i faktor‑ och positionsarrayerna. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Testar om det angivna objektet är en  com.aspose.psd.Blend  klass och är ekvivalent med denna  com.aspose.psd.Blend  klass.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att testa. |

**Returns:**
boolean - Sant om  obj  är en  com.aspose.psd.Blend  klass som är ekvivalent med denna  com.aspose.psd.Blend  klass; annars falskt.
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


Hämtar arrayen med blend‑faktorer för gradienten.

**Returns:**
float[] - Arrayen med blend‑faktorer som specificerar procentsatserna för startfärgen och slutfärgen som ska användas vid motsvarande position.
### getPositions() {#getPositions--}
```
public float[] getPositions()
```


Hämtar arrayen med blend‑positioner för gradienten.

**Returns:**
float[] - Arrayen med blend‑positioner som specificerar procentsatserna för avståndet längs gradientlinjen.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för den här instansen.

**Returns:**
int - En hashkod för den här instansen, lämplig för användning i hash‑algoritmer och datastrukturer som en hashtabell.
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


Ställer in arrayen med blend‑faktorer för gradienten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float[] | Arrayen med blend‑faktorer som specificerar procentsatserna för startfärgen och slutfärgen som ska användas vid motsvarande position. |

### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```


Ställer in arrayen med blend‑positioner för gradienten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float[] | Arrayen med blend‑positioner som specificerar procentsatserna för avståndet längs gradientlinjen. |

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

