---
title: "ColorMatrix"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "RGBA स्थान के लिए निर्देशांक शामिल करने वाला 5 x 5 मैट्रिक्स परिभाषित करता है।"
type: docs
weight: 25
url: /hi/java/com.aspose.psd/colormatrix/
---

**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

एक 5 x 5 मैट्रिक्स को परिभाषित करता है जिसमें RGBA स्थान के निर्देशांक होते हैं।  com.aspose.psd.ImageAttributes  वर्ग की कई विधियाँ रंग मैट्रिक्स का उपयोग करके छवि रंगों को समायोजित करती हैं। इस वर्ग को विरासत में नहीं लिया जा सकता।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | Aspose.Imaging.ColorMatrix  वर्ग का एक नया उदाहरण प्रारंभ करता है। |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | निर्दिष्ट मैट्रिक्स  newColorMatrix  के तत्वों का उपयोग करके Aspose.Imaging.ColorMatrix  वर्ग का एक नया उदाहरण प्रारंभ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [MatrixDimensionElementsCount](#MatrixDimensionElementsCount) | मैट्रिक्स आयाम में तत्वों की संख्या। |
| [MatrixDimensionsCount](#MatrixDimensionsCount) | मैट्रिक्स आयामों की संख्या। |
| [MatrixTotalElementsCount](#MatrixTotalElementsCount) | मैट्रिक्स में तत्वों की कुल संख्या। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMatrix()](#getMatrix--) | मैट्रिक्स मान प्राप्त करता है। |
| [getMatrix00()](#getMatrix00--) | इस  Aspose.Imaging.ColorMatrix  के 0 (शून्य) पंक्ति और 0 कॉलम पर तत्व प्राप्त करता है। |
| [getMatrix01()](#getMatrix01--) | इस  Aspose.Imaging.ColorMatrix  के 0 (शून्य) पंक्ति और पहली कॉलम पर तत्व प्राप्त करता है। |
| [getMatrix02()](#getMatrix02--) | इस  Aspose.Imaging.ColorMatrix  के 0 (शून्य) पंक्ति और दूसरी कॉलम पर तत्व प्राप्त करता है। |
| [getMatrix03()](#getMatrix03--) | इस  Aspose.Imaging.ColorMatrix  के 0 (शून्य) पंक्ति और तीसरी कॉलम पर तत्व प्राप्त करता है। |
| [getMatrix04()](#getMatrix04--) | इस  Aspose.Imaging.ColorMatrix  के 0 (शून्य) पंक्ति और चौथी कॉलम पर तत्व प्राप्त करता है। |
| [getMatrix10()](#getMatrix10--) | इस  Aspose.Imaging.ColorMatrix  के पहली पंक्ति और 0 (शून्य) कॉलम पर तत्व प्राप्त करता है। |
| [getMatrix11()](#getMatrix11--) | इस  Aspose.Imaging.ColorMatrix  के पहली पंक्ति और पहली कॉलम पर तत्व प्राप्त करता है। |
| [getMatrix12()](#getMatrix12--) | इस  Aspose.Imaging.ColorMatrix  के पहली पंक्ति और दूसरी कॉलम पर तत्व प्राप्त करता है। |
| [getMatrix13()](#getMatrix13--) | इस  Aspose.Imaging.ColorMatrix  के पहली पंक्ति और तीसरी कॉलम पर तत्व प्राप्त करता है। |
| [getMatrix14()](#getMatrix14--) | इस  Aspose.Imaging.ColorMatrix  के पहली पंक्ति और चौथी कॉलम पर तत्व प्राप्त करता है। |
| [getMatrix20()](#getMatrix20--) | इस  Aspose.Imaging.ColorMatrix  के दूसरी पंक्ति और 0 (शून्य) कॉलम पर तत्व प्राप्त करता है। |
| [getMatrix21()](#getMatrix21--) | इस  Aspose.Imaging.ColorMatrix  के दूसरी पंक्ति और पहली कॉलम पर तत्व प्राप्त करता है। |
| [getMatrix22()](#getMatrix22--) | इस  Aspose.Imaging.ColorMatrix  के दूसरी पंक्ति और दूसरी कॉलम पर तत्व प्राप्त करता है। |
| [getMatrix23()](#getMatrix23--) | इस  Aspose.Imaging.ColorMatrix  के दूसरी पंक्ति और तीसरी कॉलम पर तत्व प्राप्त करता है। |
| [getMatrix24()](#getMatrix24--) | इस  Aspose.Imaging.ColorMatrix  के दूसरी पंक्ति और चौथी कॉलम पर तत्व प्राप्त करता है। |
| [getMatrix30()](#getMatrix30--) | इस  Aspose.Imaging.ColorMatrix  के तीसरी पंक्ति और 0 (शून्य) कॉलम पर तत्व प्राप्त करता है। |
| [getMatrix31()](#getMatrix31--) | इस  Aspose.Imaging.ColorMatrix  के तीसरी पंक्ति और पहली कॉलम पर तत्व प्राप्त करता है। |
| [getMatrix32()](#getMatrix32--) | इस  Aspose.Imaging.ColorMatrix  के तीसरी पंक्ति और दूसरी कॉलम पर तत्व प्राप्त करता है। |
| [getMatrix33()](#getMatrix33--) | इस  Aspose.Imaging.ColorMatrix  के तीसरी पंक्ति और तीसरी कॉलम पर तत्व प्राप्त करता है। |
| [getMatrix34()](#getMatrix34--) | इस  Aspose.Imaging.ColorMatrix  के तीसरी पंक्ति और चौथी कॉलम पर तत्व प्राप्त करता है। |
| [getMatrix40()](#getMatrix40--) | इस  Aspose.Imaging.ColorMatrix  के चौथी पंक्ति और 0 (शून्य) कॉलम पर तत्व प्राप्त करता है। |
| [getMatrix41()](#getMatrix41--) | इस  Aspose.Imaging.ColorMatrix  के चौथी पंक्ति और पहली कॉलम पर तत्व प्राप्त करता है। |
| [getMatrix42()](#getMatrix42--) | इस Aspose.Imaging.ColorMatrix की चौथी पंक्ति और दूसरे कॉलम में तत्व प्राप्त करता है। |
| [getMatrix43()](#getMatrix43--) | इस Aspose.Imaging.ColorMatrix की चौथी पंक्ति और तीसरे कॉलम में तत्व प्राप्त करता है। |
| [getMatrix44()](#getMatrix44--) | इस Aspose.Imaging.ColorMatrix की चौथी पंक्ति और चौथे कॉलम में तत्व प्राप्त करता है। |
| [get_Item(int row, int column)](#get-Item-int-int-) | इस Aspose.Imaging.ColorMatrix में निर्दिष्ट पंक्ति और कॉलम में तत्व प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMatrix00(float value)](#setMatrix00-float-) | इस Aspose.Imaging.ColorMatrix की 0 (शून्य) पंक्ति और 0 कॉलम में तत्व सेट करता है। |
| [setMatrix01(float value)](#setMatrix01-float-) | इस Aspose.Imaging.ColorMatrix की 0 (शून्य) पंक्ति और पहले कॉलम में तत्व सेट करता है। |
| [setMatrix02(float value)](#setMatrix02-float-) | इस Aspose.Imaging.ColorMatrix की 0 (शून्य) पंक्ति और दूसरे कॉलम में तत्व सेट करता है। |
| [setMatrix03(float value)](#setMatrix03-float-) | इस Aspose.Imaging.ColorMatrix की 0 (शून्य) पंक्ति और तीसरे कॉलम में तत्व सेट करता है। |
| [setMatrix04(float value)](#setMatrix04-float-) | इस Aspose.Imaging.ColorMatrix की 0 (शून्य) पंक्ति और चौथे कॉलम में तत्व सेट करता है। |
| [setMatrix10(float value)](#setMatrix10-float-) | इस Aspose.Imaging.ColorMatrix की पहली पंक्ति और 0 (शून्य) कॉलम में तत्व सेट करता है। |
| [setMatrix11(float value)](#setMatrix11-float-) | इस Aspose.Imaging.ColorMatrix की पहली पंक्ति और पहले कॉलम में तत्व सेट करता है। |
| [setMatrix12(float value)](#setMatrix12-float-) | इस Aspose.Imaging.ColorMatrix की पहली पंक्ति और दूसरे कॉलम में तत्व सेट करता है। |
| [setMatrix13(float value)](#setMatrix13-float-) | इस Aspose.Imaging.ColorMatrix की पहली पंक्ति और तीसरे कॉलम में तत्व सेट करता है। |
| [setMatrix14(float value)](#setMatrix14-float-) | इस Aspose.Imaging.ColorMatrix की पहली पंक्ति और चौथे कॉलम में तत्व सेट करता है। |
| [setMatrix20(float value)](#setMatrix20-float-) | इस Aspose.Imaging.ColorMatrix की दूसरी पंक्ति और 0 (शून्य) कॉलम में तत्व सेट करता है। |
| [setMatrix21(float value)](#setMatrix21-float-) | इस Aspose.Imaging.ColorMatrix की दूसरी पंक्ति और पहले कॉलम में तत्व सेट करता है। |
| [setMatrix22(float value)](#setMatrix22-float-) | इस Aspose.Imaging.ColorMatrix की दूसरी पंक्ति और दूसरे कॉलम में तत्व सेट करता है। |
| [setMatrix23(float value)](#setMatrix23-float-) | इस Aspose.Imaging.ColorMatrix की दूसरी पंक्ति और तीसरे कॉलम में तत्व सेट करता है। |
| [setMatrix24(float value)](#setMatrix24-float-) | इस Aspose.Imaging.ColorMatrix की दूसरी पंक्ति और चौथे कॉलम में तत्व सेट करता है। |
| [setMatrix30(float value)](#setMatrix30-float-) | इस Aspose.Imaging.ColorMatrix की तीसरी पंक्ति और 0 (शून्य) कॉलम में तत्व सेट करता है। |
| [setMatrix31(float value)](#setMatrix31-float-) | इस Aspose.Imaging.ColorMatrix की तीसरी पंक्ति और पहले कॉलम में तत्व सेट करता है। |
| [setMatrix32(float value)](#setMatrix32-float-) | इस Aspose.Imaging.ColorMatrix की तीसरी पंक्ति और दूसरे कॉलम में तत्व सेट करता है। |
| [setMatrix33(float value)](#setMatrix33-float-) | इस Aspose.Imaging.ColorMatrix की तीसरी पंक्ति और तीसरे कॉलम में तत्व सेट करता है। |
| [setMatrix34(float value)](#setMatrix34-float-) | इस Aspose.Imaging.ColorMatrix की तीसरी पंक्ति और चौथे कॉलम में तत्व सेट करता है। |
| [setMatrix40(float value)](#setMatrix40-float-) | इस Aspose.Imaging.ColorMatrix की चौथी पंक्ति और 0 (शून्य) कॉलम में तत्व सेट करता है। |
| [setMatrix41(float value)](#setMatrix41-float-) | इस Aspose.Imaging.ColorMatrix के चौथे पंक्ति और पहले कॉलम में तत्व सेट करता है। |
| [setMatrix42(float value)](#setMatrix42-float-) | इस Aspose.Imaging.ColorMatrix के चौथे पंक्ति और दूसरे कॉलम में तत्व सेट करता है। |
| [setMatrix43(float value)](#setMatrix43-float-) | इस Aspose.Imaging.ColorMatrix के चौथे पंक्ति और तीसरे कॉलम में तत्व सेट करता है। |
| [setMatrix44(float value)](#setMatrix44-float-) | इस Aspose.Imaging.ColorMatrix के चौथे पंक्ति और चौथे कॉलम में तत्व सेट करता है। |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | Aspose.Imaging.ColorMatrix में निर्दिष्ट पंक्ति और कॉलम पर तत्व सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


Aspose.Imaging.ColorMatrix  वर्ग का एक नया उदाहरण प्रारंभ करता है।

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


निर्दिष्ट मैट्रिक्स  newColorMatrix  के तत्वों का उपयोग करके Aspose.Imaging.ColorMatrix  वर्ग का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newColorMatrix | float[][] | नए Aspose.Imaging.ColorMatrix के तत्वों के मान। |

### MatrixDimensionElementsCount {#MatrixDimensionElementsCount}
```
public static final int MatrixDimensionElementsCount
```


मैट्रिक्स आयाम में तत्वों की संख्या।

### MatrixDimensionsCount {#MatrixDimensionsCount}
```
public static final int MatrixDimensionsCount
```


मैट्रिक्स आयामों की संख्या।

### MatrixTotalElementsCount {#MatrixTotalElementsCount}
```
public static final int MatrixTotalElementsCount
```


मैट्रिक्स में तत्वों की कुल संख्या।

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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
### getMatrix() {#getMatrix--}
```
public float[][] getMatrix()
```


मैट्रिक्स मान प्राप्त करता है।

**Returns:**
float[][] - मैट्रिक्स मानों की एरे।
### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


इस  Aspose.Imaging.ColorMatrix  के 0 (शून्य) पंक्ति और 0 कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस Aspose.Imaging.ColorMatrix की 0 पंक्ति और 0 कॉलम पर तत्व।
### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


इस  Aspose.Imaging.ColorMatrix  के 0 (शून्य) पंक्ति और पहली कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस Aspose.Imaging.ColorMatrix की 0 पंक्ति और पहले कॉलम पर तत्व।
### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


इस  Aspose.Imaging.ColorMatrix  के 0 (शून्य) पंक्ति और दूसरी कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस Aspose.Imaging.ColorMatrix की 0 पंक्ति और दूसरे कॉलम पर तत्व।
### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


इस  Aspose.Imaging.ColorMatrix  के 0 (शून्य) पंक्ति और तीसरी कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस Aspose.Imaging.ColorMatrix की 0 पंक्ति और तीसरे कॉलम पर तत्व।
### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


इस  Aspose.Imaging.ColorMatrix  के 0 (शून्य) पंक्ति और चौथी कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस Aspose.Imaging.ColorMatrix की 0 पंक्ति और चौथे कॉलम पर तत्व।
### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


इस  Aspose.Imaging.ColorMatrix  के पहली पंक्ति और 0 (शून्य) कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस Aspose.Imaging.ColorMatrix की पहली पंक्ति और 0 कॉलम पर तत्व।
### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


इस  Aspose.Imaging.ColorMatrix  के पहली पंक्ति और पहली कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस Aspose.Imaging.ColorMatrix की पहली पंक्ति और पहले कॉलम पर तत्व।
### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


इस  Aspose.Imaging.ColorMatrix  के पहली पंक्ति और दूसरी कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस Aspose.Imaging.ColorMatrix की पहली पंक्ति और दूसरे कॉलम पर तत्व।
### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


इस  Aspose.Imaging.ColorMatrix  के पहली पंक्ति और तीसरी कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस Aspose.Imaging.ColorMatrix की पहली पंक्ति और तीसरे कॉलम पर तत्व।
### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


इस  Aspose.Imaging.ColorMatrix  के पहली पंक्ति और चौथी कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस Aspose.Imaging.ColorMatrix की पहली पंक्ति और चौथे कॉलम पर तत्व।
### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


इस  Aspose.Imaging.ColorMatrix  के दूसरी पंक्ति और 0 (शून्य) कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस Aspose.Imaging.ColorMatrix की दूसरी पंक्ति और 0 कॉलम पर तत्व।
### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


इस  Aspose.Imaging.ColorMatrix  के दूसरी पंक्ति और पहली कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस Aspose.Imaging.ColorMatrix की दूसरी पंक्ति और पहले कॉलम पर तत्व।
### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


इस  Aspose.Imaging.ColorMatrix  के दूसरी पंक्ति और दूसरी कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस Aspose.Imaging.ColorMatrix की दूसरी पंक्ति और दूसरे कॉलम पर तत्व।
### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


इस  Aspose.Imaging.ColorMatrix  के दूसरी पंक्ति और तीसरी कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस Aspose.Imaging.ColorMatrix की दूसरी पंक्ति और तीसरे कॉलम पर तत्व।
### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


इस  Aspose.Imaging.ColorMatrix  के दूसरी पंक्ति और चौथी कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस Aspose.Imaging.ColorMatrix की दूसरी पंक्ति और चौथे कॉलम पर तत्व।
### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


इस  Aspose.Imaging.ColorMatrix  के तीसरी पंक्ति और 0 (शून्य) कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस Aspose.Imaging.ColorMatrix की तीसरी पंक्ति और 0 कॉलम पर तत्व।
### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


इस  Aspose.Imaging.ColorMatrix  के तीसरी पंक्ति और पहली कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस Aspose.Imaging.ColorMatrix की तीसरी पंक्ति और प्रथम कॉलम में तत्व।
### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


इस  Aspose.Imaging.ColorMatrix  के तीसरी पंक्ति और दूसरी कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस Aspose.Imaging.ColorMatrix की तीसरी पंक्ति और दूसरे कॉलम में तत्व।
### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


इस  Aspose.Imaging.ColorMatrix  के तीसरी पंक्ति और तीसरी कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस Aspose.Imaging.ColorMatrix की तीसरी पंक्ति और तीसरे कॉलम में तत्व।
### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


इस  Aspose.Imaging.ColorMatrix  के तीसरी पंक्ति और चौथी कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस Aspose.Imaging.ColorMatrix की तीसरी पंक्ति और चौथे कॉलम में तत्व।
### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


इस  Aspose.Imaging.ColorMatrix  के चौथी पंक्ति और 0 (शून्य) कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस Aspose.Imaging.ColorMatrix की चौथी पंक्ति और 0 कॉलम में तत्व।
### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


इस  Aspose.Imaging.ColorMatrix  के चौथी पंक्ति और पहली कॉलम पर तत्व प्राप्त करता है।

**Returns:**
float - इस Aspose.Imaging.ColorMatrix की चौथी पंक्ति और प्रथम कॉलम में तत्व।
### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


इस Aspose.Imaging.ColorMatrix की चौथी पंक्ति और दूसरे कॉलम में तत्व प्राप्त करता है।

**Returns:**
float - इस Aspose.Imaging.ColorMatrix की चौथी पंक्ति और दूसरे कॉलम में तत्व।
### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


इस Aspose.Imaging.ColorMatrix की चौथी पंक्ति और तीसरे कॉलम में तत्व प्राप्त करता है।

**Returns:**
float - इस Aspose.Imaging.ColorMatrix की चौथी पंक्ति और तीसरे कॉलम में तत्व।
### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


इस Aspose.Imaging.ColorMatrix की चौथी पंक्ति और चौथे कॉलम में तत्व प्राप्त करता है।

**Returns:**
float - इस Aspose.Imaging.ColorMatrix की चौथी पंक्ति और चौथे कॉलम में तत्व।
### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


इस Aspose.Imaging.ColorMatrix में निर्दिष्ट पंक्ति और कॉलम में तत्व प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पंक्ति | int | पंक्ति संख्या। |
| कॉलम | int | कॉलम संख्या। |

**Returns:**
float - निर्दिष्ट पंक्ति और कॉलम में तत्व।
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




### setMatrix00(float value) {#setMatrix00-float-}
```
public void setMatrix00(float value)
```


इस Aspose.Imaging.ColorMatrix की 0 (शून्य) पंक्ति और 0 कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस Aspose.Imaging.ColorMatrix की 0 पंक्ति और 0 कॉलम में तत्व। |

### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


इस Aspose.Imaging.ColorMatrix की 0 (शून्य) पंक्ति और पहले कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस Aspose.Imaging.ColorMatrix की 0 पंक्ति और प्रथम कॉलम में तत्व। |

### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


इस Aspose.Imaging.ColorMatrix की 0 (शून्य) पंक्ति और दूसरे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस Aspose.Imaging.ColorMatrix की 0 पंक्ति और दूसरे कॉलम में तत्व। |

### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


इस Aspose.Imaging.ColorMatrix की 0 (शून्य) पंक्ति और तीसरे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस Aspose.Imaging.ColorMatrix की 0 पंक्ति और तीसरे कॉलम में तत्व। |

### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


इस Aspose.Imaging.ColorMatrix की 0 (शून्य) पंक्ति और चौथे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस Aspose.Imaging.ColorMatrix की 0 पंक्ति और चौथे कॉलम में तत्व। |

### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


इस Aspose.Imaging.ColorMatrix की पहली पंक्ति और 0 (शून्य) कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस Aspose.Imaging.ColorMatrix की प्रथम पंक्ति और 0 कॉलम में तत्व। |

### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


इस Aspose.Imaging.ColorMatrix की पहली पंक्ति और पहले कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस Aspose.Imaging.ColorMatrix की प्रथम पंक्ति और प्रथम कॉलम में तत्व। |

### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


इस Aspose.Imaging.ColorMatrix की पहली पंक्ति और दूसरे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस Aspose.Imaging.ColorMatrix की प्रथम पंक्ति और दूसरे कॉलम में तत्व। |

### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


इस Aspose.Imaging.ColorMatrix की पहली पंक्ति और तीसरे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस Aspose.Imaging.ColorMatrix की प्रथम पंक्ति और तीसरे कॉलम में तत्व। |

### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


इस Aspose.Imaging.ColorMatrix की पहली पंक्ति और चौथे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस Aspose.Imaging.ColorMatrix की प्रथम पंक्ति और चौथे कॉलम में तत्व। |

### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


इस Aspose.Imaging.ColorMatrix की दूसरी पंक्ति और 0 (शून्य) कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस Aspose.Imaging.ColorMatrix की दूसरी पंक्ति और 0 कॉलम में तत्व। |

### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


इस Aspose.Imaging.ColorMatrix की दूसरी पंक्ति और पहले कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस  Aspose.Imaging.ColorMatrix  की दूसरी पंक्ति और पहले कॉलम में तत्व। |

### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


इस Aspose.Imaging.ColorMatrix की दूसरी पंक्ति और दूसरे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस  Aspose.Imaging.ColorMatrix  की दूसरी पंक्ति और दूसरे कॉलम में तत्व। |

### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


इस Aspose.Imaging.ColorMatrix की दूसरी पंक्ति और तीसरे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस  Aspose.Imaging.ColorMatrix  की दूसरी पंक्ति और तीसरे कॉलम में तत्व। |

### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


इस Aspose.Imaging.ColorMatrix की दूसरी पंक्ति और चौथे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस  Aspose.Imaging.ColorMatrix  की दूसरी पंक्ति और चौथे कॉलम में तत्व। |

### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


इस Aspose.Imaging.ColorMatrix की तीसरी पंक्ति और 0 (शून्य) कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस  Aspose.Imaging.ColorMatrix  की तीसरी पंक्ति और 0 कॉलम में तत्व। |

### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


इस Aspose.Imaging.ColorMatrix की तीसरी पंक्ति और पहले कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस  Aspose.Imaging.ColorMatrix  की तीसरी पंक्ति और पहले कॉलम में तत्व। |

### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


इस Aspose.Imaging.ColorMatrix की तीसरी पंक्ति और दूसरे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस  Aspose.Imaging.ColorMatrix  की तीसरी पंक्ति और दूसरे कॉलम में तत्व। |

### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


इस Aspose.Imaging.ColorMatrix की तीसरी पंक्ति और तीसरे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस  Aspose.Imaging.ColorMatrix  की तीसरी पंक्ति और तीसरे कॉलम में तत्व। |

### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


इस Aspose.Imaging.ColorMatrix की तीसरी पंक्ति और चौथे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस  Aspose.Imaging.ColorMatrix  की तीसरी पंक्ति और चौथे कॉलम में तत्व। |

### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


इस Aspose.Imaging.ColorMatrix की चौथी पंक्ति और 0 (शून्य) कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस  Aspose.Imaging.ColorMatrix  की चौथी पंक्ति और 0 कॉलम में तत्व। |

### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


इस Aspose.Imaging.ColorMatrix के चौथे पंक्ति और पहले कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस  Aspose.Imaging.ColorMatrix  की चौथी पंक्ति और पहले कॉलम में तत्व। |

### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


इस Aspose.Imaging.ColorMatrix के चौथे पंक्ति और दूसरे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस  Aspose.Imaging.ColorMatrix  की चौथी पंक्ति और दूसरे कॉलम में तत्व। |

### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


इस Aspose.Imaging.ColorMatrix के चौथे पंक्ति और तीसरे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस  Aspose.Imaging.ColorMatrix  की चौथी पंक्ति और तीसरे कॉलम में तत्व। |

### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


इस Aspose.Imaging.ColorMatrix के चौथे पंक्ति और चौथे कॉलम में तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस  Aspose.Imaging.ColorMatrix  की चौथी पंक्ति और चौथे कॉलम में तत्व। |

### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


Aspose.Imaging.ColorMatrix में निर्दिष्ट पंक्ति और कॉलम पर तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पंक्ति | int | पंक्ति संख्या। |
| कॉलम | int | कॉलम संख्या। |
| मान | float | मान |

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

