---
title: "ResizeType"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Καθορίζει τον τύπο αλλαγής μεγέθους."
type: docs
weight: 91
url: /el/java/com.aspose.psd/resizetype/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResizeType extends System.Enum
```

Καθορίζει τον τύπο αλλαγής μεγέθους.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [AdaptiveResample](#AdaptiveResample) | Επαναδειγματοληψία χρησιμοποιώντας προσαρμοστικό αλγόριθμο βασισμένο σε σταθμισμένη και συνδυασμένη ρητή συνάρτηση και αλγόριθμούς παρεμβολής lanczos3. |
| [Bell](#Bell) | Η μέθοδος παρεμβολής Bell |
| [BilinearResample](#BilinearResample) | Επαναδειγματοληψία χρησιμοποιώντας δισιζυγική παρεμβολή. |
| [CatmullRom](#CatmullRom) | Η κυβική μέθοδος παρεμβολής Catmull-Rom. |
| [CenterToCenter](#CenterToCenter) | Το κέντρο της νέας εικόνας θα συμπίπτει με το κέντρο της αρχικής εικόνας. |
| [CubicBSpline](#CubicBSpline) | Η κυβική μέθοδος παρεμβολής CubicBSpline |
| [CubicConvolution](#CubicConvolution) | Η κυβική μέθοδος παρεμβολής Cubic Convolution |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [HighQualityResample](#HighQualityResample) | Η υψηλής ποιότητας επαναδειγματοληψία |
| [LanczosResample](#LanczosResample) | Επαναδειγματοληψία χρησιμοποιώντας αλγόριθμο lanczos με a=3. |
| [LeftBottomToLeftBottom](#LeftBottomToLeftBottom) | Το αριστερό κάτω σημείο της νέας εικόνας θα συμπίπτει με το αριστερό κάτω σημείο της αρχικής εικόνας. |
| [LeftTopToLeftTop](#LeftTopToLeftTop) | Το αριστερό άνω σημείο της νέας εικόνας θα συμπίπτει με το αριστερό άνω σημείο της αρχικής εικόνας. |
| [Mitchell](#Mitchell) | Η κυβική μέθοδος παρεμβολής Mitchell |
| [NearestNeighbourResample](#NearestNeighbourResample) | Επαναδειγματοληψία χρησιμοποιώντας αλγόριθμο πλησιέστερου γείτονα. |
| [None](#None) | Τα pixel δεν διατηρούνται κατά τη λειτουργία αλλαγής μεγέθους. |
| [RightBottomToRightBottom](#RightBottomToRightBottom) | Το δεξιό κάτω σημείο της νέας εικόνας θα συμπίπτει με το δεξιό κάτω σημείο της αρχικής εικόνας. |
| [RightTopToRightTop](#RightTopToRightTop) | Το δεξιό άνω σημείο της νέας εικόνας θα συμπίπτει με το δεξιό άνω σημείο της αρχικής εικόνας. |
| [SinC](#SinC) | Η κυβική μέθοδος παρεμβολής Sinc (Lanczos3) |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(System.Enum arg0)](#CloneTo-com.aspose.ms.System.Enum-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [format(System.Type arg0, Object arg1, String arg2)](#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-) |  |
| [format(Class<?> arg0, long arg1, String arg2)](#format-java.lang.Class----long-java.lang.String-) |  |
| [getClass()](#getClass--) |  |
| [getName(System.Type arg0, Object arg1)](#getName-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [getName(Class<?> arg0, long arg1)](#getName-java.lang.Class----long-) |  |
| [getNames()](#getNames--) |  |
| [getNames(System.Type arg0)](#getNames-com.aspose.ms.System.Type-) |  |
| [getNames(Class<?> arg0)](#getNames-java.lang.Class----) |  |
| [getUnderlyingType(System.Type arg0)](#getUnderlyingType-com.aspose.ms.System.Type-) |  |
| [getUnderlyingType(Class<?> arg0)](#getUnderlyingType-java.lang.Class----) |  |
| [getValue(Class<?> arg0, String arg1)](#getValue-java.lang.Class----java.lang.String-) |  |
| [getValues()](#getValues--) |  |
| [getValues(System.Type arg0)](#getValues-com.aspose.ms.System.Type-) |  |
| [getValues(Class<?> arg0)](#getValues-java.lang.Class----) |  |
| [get_Caption()](#get-Caption--) |  |
| [get_Value()](#get-Value--) |  |
| [hashCode()](#hashCode--) |  |
| [isDefined(System.Type arg0, Object arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [isDefined(System.Type arg0, String arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.String-) |  |
| [isDefined(System.Type arg0, long arg1)](#isDefined-com.aspose.ms.System.Type-long-) |  |
| [isDefined(Class<?> arg0, String arg1)](#isDefined-java.lang.Class----java.lang.String-) |  |
| [isDefined(Class<?> arg0, long arg1)](#isDefined-java.lang.Class----long-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(System.Type arg0, String arg1)](#parse-com.aspose.ms.System.Type-java.lang.String-) |  |
| [parse(System.Type arg0, String arg1, Boolean arg2)](#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-) |  |
| [parse(Class<?> arg0, String arg1)](#parse-java.lang.Class----java.lang.String-) |  |
| [parse(Class<?> arg0, String arg1, Boolean arg2)](#parse-java.lang.Class----java.lang.String-java.lang.Boolean-) |  |
| [register(System.Enum.AbstractEnum arg0)](#register-com.aspose.ms.System.Enum.AbstractEnum-) |  |
| [toObject(System.Type arg0, Object arg1)](#toObject-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [toString()](#toString--) |  |
| [toString(Class<?> arg0, long arg1)](#toString-java.lang.Class----long-) |  |
| [toString(long arg0)](#toString-long-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AdaptiveResample {#AdaptiveResample}
```
public static final int AdaptiveResample
```


Επαναδειγματοληψία χρησιμοποιώντας προσαρμοστικό αλγόριθμο βασισμένο σε σταθμισμένη και συνδυασμένη ρητή συνάρτηση και αλγόριθμούς παρεμβολής lanczos3.

### Bell {#Bell}
```
public static final int Bell
```


Η μέθοδος παρεμβολής Bell

### BilinearResample {#BilinearResample}
```
public static final int BilinearResample
```


Επαναδειγματοληψία χρησιμοποιώντας δισιζυγική παρεμβολή. Επιτρέπεται προφιλτράρισμα εικόνας για την αφαίρεση του θορύβου πριν την επαναδειγματοληψία, όταν χρειάζεται.

### CatmullRom {#CatmullRom}
```
public static final int CatmullRom
```


Η κυβική μέθοδος παρεμβολής Catmull-Rom.

### CenterToCenter {#CenterToCenter}
```
public static final int CenterToCenter
```


Το κέντρο της νέας εικόνας θα συμπίπτει με το κέντρο της αρχικής εικόνας. Η περικοπή θα γίνει εάν απαιτηθεί.

### CubicBSpline {#CubicBSpline}
```
public static final int CubicBSpline
```


Η κυβική μέθοδος παρεμβολής CubicBSpline

### CubicConvolution {#CubicConvolution}
```
public static final int CubicConvolution
```


Η κυβική μέθοδος παρεμβολής Cubic Convolution

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### HighQualityResample {#HighQualityResample}
```
public static final int HighQualityResample
```


Η υψηλής ποιότητας επαναδειγματοληψία

### LanczosResample {#LanczosResample}
```
public static final int LanczosResample
```


Επαναδειγματοληψία χρησιμοποιώντας αλγόριθμο lanczos με a=3.

### LeftBottomToLeftBottom {#LeftBottomToLeftBottom}
```
public static final int LeftBottomToLeftBottom
```


Το αριστερό κάτω σημείο της νέας εικόνας θα συμπίπτει με το αριστερό κάτω σημείο της αρχικής εικόνας. Η περικοπή θα γίνει εάν απαιτηθεί.

### LeftTopToLeftTop {#LeftTopToLeftTop}
```
public static final int LeftTopToLeftTop
```


Το αριστερό άνω σημείο της νέας εικόνας θα συμπίπτει με το αριστερό άνω σημείο της αρχικής εικόνας. Η περικοπή θα γίνει εάν απαιτηθεί.

### Mitchell {#Mitchell}
```
public static final int Mitchell
```


Η κυβική μέθοδος παρεμβολής Mitchell

### NearestNeighbourResample {#NearestNeighbourResample}
```
public static final int NearestNeighbourResample
```


Επαναδειγματοληψία χρησιμοποιώντας αλγόριθμο πλησιέστερου γείτονα.

### None {#None}
```
public static final int None
```


Τα pixel δεν διατηρούνται κατά τη λειτουργία αλλαγής μεγέθους.

### RightBottomToRightBottom {#RightBottomToRightBottom}
```
public static final int RightBottomToRightBottom
```


Το δεξιό κάτω σημείο της νέας εικόνας θα συμπίπτει με το δεξιό κάτω σημείο της αρχικής εικόνας. Η περικοπή θα γίνει εάν απαιτηθεί.

### RightTopToRightTop {#RightTopToRightTop}
```
public static final int RightTopToRightTop
```


Το δεξιό άνω σημείο της νέας εικόνας θα συμπίπτει με το δεξιό άνω σημείο της αρχικής εικόνας. Η περικοπή θα γίνει εάν απαιτηθεί.

### SinC {#SinC}
```
public static final int SinC
```


Η κυβική μέθοδος παρεμβολής Sinc (Lanczos3)

### Clone() {#Clone--}
```
public System.Enum Clone()
```




**Returns:**
com.aspose.ms.System.Enum
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### format(Class<?> arg0, long arg1, String arg2) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> arg0, long arg1, String arg2)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName(System.Type arg0, Object arg1) {#getName-com.aspose.ms.System.Type-java.lang.Object-}
```
public static String getName(System.Type arg0, Object arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.String
### getName(Class<?> arg0, long arg1) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> arg0, long arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
java.lang.String
### getNames() {#getNames--}
```
public String[] getNames()
```




**Returns:**
java.lang.String[]
### getNames(System.Type arg0) {#getNames-com.aspose.ms.System.Type-}
```
public static String[] getNames(System.Type arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### getValues() {#getValues--}
```
public Long[] getValues()
```




**Returns:**
java.lang.Long[]
### getValues(System.Type arg0) {#getValues-com.aspose.ms.System.Type-}
```
public static System.Array getValues(System.Type arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Array
### getValues(Class<?> arg0) {#getValues-java.lang.Class----}
```
public static Long[] getValues(Class<?> arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Long[]
### get_Caption() {#get-Caption--}
```
public String get_Caption()
```




**Returns:**
java.lang.String
### get_Value() {#get-Value--}
```
public long get_Value()
```




**Returns:**
long
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDefined(System.Type arg0, Object arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.Object-}
```
public static boolean isDefined(System.Type arg0, Object arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
boolean
### isDefined(System.Type arg0, String arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type arg0, String arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
boolean
### isDefined(System.Type arg0, long arg1) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type arg0, long arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | long |  |

**Returns:**
boolean
### isDefined(Class<?> arg0, String arg1) {#isDefined-java.lang.Class----java.lang.String-}
```
public static boolean isDefined(Class<?> arg0, String arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
boolean
### isDefined(Class<?> arg0, long arg1) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> arg0, long arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parse(System.Type arg0, String arg1) {#parse-com.aspose.ms.System.Type-java.lang.String-}
```
public static long parse(System.Type arg0, String arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(System.Type arg0, String arg1, Boolean arg2) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type arg0, String arg1, Boolean arg2)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> arg0, String arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1, Boolean arg2) {#parse-java.lang.Class----java.lang.String-java.lang.Boolean-}
```
public static long parse(Class<?> arg0, String arg1, Boolean arg2)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### register(System.Enum.AbstractEnum arg0) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toString(Class<?> arg0, long arg1) {#toString-java.lang.Class----long-}
```
public static String toString(Class<?> arg0, long arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
java.lang.String
### toString(long arg0) {#toString-long-}
```
public String toString(long arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

