---
title: "Metered"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Fournit des méthodes mesurées pour l'intégration"
type: docs
weight: 71
url: /fr/java/com.aspose.psd/metered/
---

**Inheritance:**
java.lang.Object
```
public class Metered
```

Fournit des méthodes mesurées pour l'intégration

Dans cet exemple, une tentative sera faite pour définir la clé publique et privée mesurée.

// le fichier jar du composant : Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey");
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Metered()](#Metered--) |  |
## Champs

| Champ | Description |
| --- | --- |
| [FlushTimeout_internalized](#FlushTimeout-internalized) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si l'Objet spécifié est égal à cette instance. |
| [getClass()](#getClass--) |  |
| [getConsumptionCredit()](#getConsumptionCredit--) | Obtient le crédit de consommation |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Obtient la taille du fichier de consommation |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Définit la clé publique et privée mesurée |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Metered() {#Metered--}
```
public Metered()
```


### FlushTimeout_internalized {#FlushTimeout-internalized}
```
public static int FlushTimeout_internalized
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si l'Objet spécifié est égal à cette instance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'objet à comparer avec cette instance. |

**Returns:**
booléen -  true  si l'objet spécifié est égal à cette instance ; sinon,  false .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Obtient le crédit de consommation

**Returns:**
java.math.BigDecimal - quantité de consommation
### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Obtient la taille du fichier de consommation

**Returns:**
java.math.BigDecimal - taille du fichier de consommation
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Définit la clé publique et privée mesurée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| publicKey | java.lang.String | clé publique |
| privateKey | java.lang.String | clé privée |

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

