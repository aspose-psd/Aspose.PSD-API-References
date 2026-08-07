---
title: "License"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt Methoden bereit, um die Komponente zu lizenzieren."
type: docs
weight: 65
url: /de/java/com.aspose.psd/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

Stellt Methoden bereit, um die Komponente zu lizenzieren.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [License()](#License--) | Initialisiert eine neue Instanz dieser Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getErrorCodeMessages()](#getErrorCodeMessages--) | Liefert die Fehlermeldungen der Fehlercodes. |
| [getRenewSubscriptionStartMessage()](#getRenewSubscriptionStartMessage--) | Liefert die Startnachricht für die Erneuerung des Abonnements. |
| [hashCode()](#hashCode--) |  |
| [isLicensed_internalized()](#isLicensed-internalized--) | Liefert einen Wert, der angibt, ob das Produkt lizenziert ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeLicense()](#removeLicense--) |  |
| [setLicense(File licenseFile)](#setLicense-java.io.File-) | Lizenziert die Komponente. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Lizenziert die Komponente. |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Lizenziert die Komponente. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### License() {#License--}
```
public License()
```


Initialisiert eine neue Instanz dieser Klasse.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getErrorCodeMessages() {#getErrorCodeMessages--}
```
public static ByteObjDictionary<String> getErrorCodeMessages()
```


Liefert die Fehlermeldungen der Fehlercodes.

Wert: Die Fehlermeldungen der Fehlercodes.

**Returns:**
com.aspose.java.optimization.maps.ByteObjDictionary<java.lang.String> - die Fehlermeldungen der Fehlercodes.
### getRenewSubscriptionStartMessage() {#getRenewSubscriptionStartMessage--}
```
public static String getRenewSubscriptionStartMessage()
```


Liefert die Startnachricht für die Erneuerung des Abonnements.

Wert: Die Nachricht zum Start der Abonnementverlängerung.

**Returns:**
java.lang.String - die Nachricht zum Start der Abonnementverlängerung.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isLicensed_internalized() {#isLicensed-internalized--}
```
public static boolean isLicensed_internalized()
```


Liefert einen Wert, der angibt, ob das Produkt lizenziert ist.

**Returns:**
boolean -  true  wenn das Produkt lizenziert ist; andernfalls  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeLicense() {#removeLicense--}
```
public static void removeLicense()
```




### setLicense(File licenseFile) {#setLicense-java.io.File-}
```
public void setLicense(File licenseFile)
```


Lizenziert die Komponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| licenseFile | java.io.File | Darstellung des Dateipfads |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


Lizenziert die Komponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Ein Stream, der die Lizenz enthält. |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


Lizenziert die Komponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| licenseName | java.lang.String | Kann ein voller oder kurzer Dateiname sein Verwenden Sie eine leere Zeichenkette, um in den Evaluierungsmodus zu wechseln. |

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

