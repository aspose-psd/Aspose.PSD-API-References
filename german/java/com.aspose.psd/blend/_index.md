---
title: "Blend"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Definiert ein Mischmuster."
type: docs
weight: 11
url: /de/java/com.aspose.psd/blend/
---

**Inheritance:**
java.lang.Object
```
public final class Blend
```

Definiert ein Blend-Muster. Diese Klasse kann nicht abgeleitet werden.

Die typische Verwendung der Blend-Klasse besteht darin, ein Blend-Muster für einen Pinsel zu definieren. Daher sollten die Blend-Eigenschaften sorgfältig initialisiert werden. Null‑Arrays sind nicht zulässig. Der Pinsel wirft die entsprechende Ausnahme, wenn das Blend-Faktoren- oder Positions-Array leer ist oder deren Länge nicht gleich ist. Wenn das Positions-Array zwei oder mehr Elemente enthält, muss das erste Element 0 und das letzte Element 1 sein.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Blend()](#Blend--) | Initialisiert eine neue Instanz der  Blend  Klasse. |
| [Blend(int count)](#Blend-int-) | Initialisiert eine neue Instanz der  Blend  Klasse mit der angegebenen Anzahl von Faktoren und Positionen. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Prüft, ob das angegebene Objekt eine  com.aspose.psd.Blend  Klasse ist und dieser  com.aspose.psd.Blend  Klasse entspricht. |
| [getClass()](#getClass--) |  |
| [getFactors()](#getFactors--) | Liefert das Array der Blend‑Faktoren für den Farbverlauf. |
| [getPositions()](#getPositions--) | Liefert das Array der Blend‑Positionen für den Farbverlauf. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFactors(float[] value)](#setFactors-float---) | Setzt das Array der Blend‑Faktoren für den Farbverlauf. |
| [setPositions(float[] value)](#setPositions-float---) | Setzt das Array der Blend‑Positionen für den Farbverlauf. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Blend() {#Blend--}
```
public Blend()
```


Initialisiert eine neue Instanz der  Blend  Klasse. Die Anzahl der Elemente in den Faktor‑ und Blend‑Arrays wird 1 sein.

### Blend(int count) {#Blend-int-}
```
public Blend(int count)
```


Initialisiert eine neue Instanz der  Blend  Klasse mit der angegebenen Anzahl von Faktoren und Positionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| count | int | Die Anzahl der Elemente in den Faktor‑ und Positions‑Arrays. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Prüft, ob das angegebene Objekt eine  com.aspose.psd.Blend  Klasse ist und dieser  com.aspose.psd.Blend  Klasse entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das zu testende Objekt. |

**Returns:**
boolean - Wahr, wenn  obj  eine  com.aspose.psd.Blend  Klasse ist, die dieser  com.aspose.psd.Blend  Klasse entspricht; andernfalls falsch.
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


Liefert das Array der Blend‑Faktoren für den Farbverlauf.

**Returns:**
float[] - Das Array der Blend‑Faktoren, das die Prozentsätze der Start‑ und Endfarbe angibt, die an der entsprechenden Position verwendet werden.
### getPositions() {#getPositions--}
```
public float[] getPositions()
```


Liefert das Array der Blend‑Positionen für den Farbverlauf.

**Returns:**
float[] - Das Array der Blend‑Positionen, das die Prozentsätze der Entfernung entlang der Farbverlaufs‑Linie angibt.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese Instanz zurück.

**Returns:**
int - Ein Hashcode für diese Instanz, geeignet für die Verwendung in Hash‑Algorithmen und Datenstrukturen wie einer Hashtabelle.
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


Setzt das Array der Blend‑Faktoren für den Farbverlauf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float[] | Das Array der Blend‑Faktoren, das die Prozentsätze der Start‑ und Endfarbe angibt, die an der entsprechenden Position verwendet werden. |

### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```


Setzt das Array der Blend‑Positionen für den Farbverlauf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float[] | Das Array der Blend‑Positionen, das die Prozentsätze der Entfernung entlang der Farbverlaufs‑Linie angibt. |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

