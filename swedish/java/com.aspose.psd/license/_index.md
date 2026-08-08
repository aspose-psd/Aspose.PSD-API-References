---
title: "License"
second_title: "Aspose.PSD för Java API-referens"
description: "Tillhandahåller metoder för att licensiera komponenten."
type: docs
weight: 65
url: /sv/java/com.aspose.psd/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

Tillhandahåller metoder för att licensiera komponenten.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [License()](#License--) | Initierar en ny instans av denna klass. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getErrorCodeMessages()](#getErrorCodeMessages--) | Hämtar felkodmeddelandena. |
| [getRenewSubscriptionStartMessage()](#getRenewSubscriptionStartMessage--) | Hämtar meddelandet för förnyelse av prenumerationens start. |
| [hashCode()](#hashCode--) |  |
| [isLicensed_internalized()](#isLicensed-internalized--) | Hämtar ett värde som indikerar om produkten är licensierad. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeLicense()](#removeLicense--) |  |
| [setLicense(File licenseFile)](#setLicense-java.io.File-) | Licensierar komponenten. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licensierar komponenten. |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licensierar komponenten. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### License() {#License--}
```
public License()
```


Initierar en ny instans av denna klass.

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


Hämtar felkodmeddelandena.

Värde: Felkodmeddelandena.

**Returns:**
com.aspose.java.optimization.maps.ByteObjDictionary<java.lang.String> - felkodmeddelandena.
### getRenewSubscriptionStartMessage() {#getRenewSubscriptionStartMessage--}
```
public static String getRenewSubscriptionStartMessage()
```


Hämtar meddelandet för förnyelse av prenumerationens start.

Värde: Meddelandet för förnyelse av prenumerationens start.

**Returns:**
java.lang.String - meddelandet för förnyelse av prenumerationens start.
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


Hämtar ett värde som indikerar om produkten är licensierad.

**Returns:**
boolean -  true  om produkten är licensierad; annars  false .
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


Licensierar komponenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licenseFile | java.io.File | representation av filsökväg |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


Licensierar komponenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | En ström som innehåller licensen. |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


Licensierar komponenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licenseName | java.lang.String | Kan vara ett fullständigt eller kort filnamn. Använd en tom sträng för att växla till utvärderingsläge. |

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

