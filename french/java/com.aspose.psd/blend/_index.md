---
title: "Blend"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Définit un motif de mélange."
type: docs
weight: 11
url: /fr/java/com.aspose.psd/blend/
---

**Inheritance:**
java.lang.Object
```
public final class Blend
```

Définit un motif de fusion. Cette classe ne peut pas être héritée.

L'utilisation typique de la classe blend consiste à définir un motif de blend pour brush. Ainsi, les propriétés de blend doivent être initialisées avec soin. Les tableaux null ne sont pas autorisés. Le brush lèvera l'exception appropriée si les tableaux de facteurs de blend ou de positions sont vides ou si leur longueur n'est pas identique. S'il y a deux éléments ou plus dans le tableau des positions, le premier élément doit être 0 et le dernier 1.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Blend()](#Blend--) | Initialise une nouvelle instance de la classe  Blend  . |
| [Blend(int count)](#Blend-int-) | Initialise une nouvelle instance de la classe  Blend  avec le nombre spécifié de facteurs et de positions. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Teste si l'objet spécifié est une classe  com.aspose.psd.Blend  et est équivalente à cette classe  com.aspose.psd.Blend . |
| [getClass()](#getClass--) |  |
| [getFactors()](#getFactors--) | Obtient le tableau des facteurs de mélange pour le dégradé. |
| [getPositions()](#getPositions--) | Obtient le tableau des positions de mélange pour le dégradé. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFactors(float[] value)](#setFactors-float---) | Définit le tableau des facteurs de mélange pour le dégradé. |
| [setPositions(float[] value)](#setPositions-float---) | Définit le tableau des positions de mélange pour le dégradé. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Blend() {#Blend--}
```
public Blend()
```


Initialise une nouvelle instance de la classe  Blend . Le nombre d'éléments dans les tableaux de facteurs et de mélanges sera égal à 1.

### Blend(int count) {#Blend-int-}
```
public Blend(int count)
```


Initialise une nouvelle instance de la classe  Blend  avec le nombre spécifié de facteurs et de positions.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| count | int | Le nombre d'éléments dans les tableaux de facteurs et de positions. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Teste si l'objet spécifié est une classe  com.aspose.psd.Blend  et est équivalente à cette classe  com.aspose.psd.Blend .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'objet à tester. |

**Returns:**
boolean - Vrai si  obj  est une classe  com.aspose.psd.Blend  équivalente à cette classe  com.aspose.psd.Blend ; sinon, faux.
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


Obtient le tableau des facteurs de mélange pour le dégradé.

**Returns:**
float[] - Le tableau des facteurs de mélange qui spécifient les pourcentages de la couleur de départ et de la couleur d'arrivée à utiliser à la position correspondante.
### getPositions() {#getPositions--}
```
public float[] getPositions()
```


Obtient le tableau des positions de mélange pour le dégradé.

**Returns:**
float[] - Le tableau des positions de mélange qui spécifient les pourcentages de distance le long de la ligne du dégradé.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette instance.

**Returns:**
int - Un code de hachage pour cette instance, adapté à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage.
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


Définit le tableau des facteurs de mélange pour le dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float[] | Le tableau des facteurs de mélange qui spécifient les pourcentages de la couleur de départ et de la couleur d'arrivée à utiliser à la position correspondante. |

### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```


Définit le tableau des positions de mélange pour le dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float[] | Le tableau des positions de mélange qui spécifient les pourcentages de distance le long de la ligne du dégradé. |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

