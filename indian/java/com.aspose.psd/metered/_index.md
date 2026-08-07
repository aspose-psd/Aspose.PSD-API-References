---
title: "मापित"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "इंटीग्रेशन के लिए मीटरड मेथड प्रदान करता है"
type: docs
weight: 71
url: /hi/java/com.aspose.psd/metered/
---

**Inheritance:**
java.lang.Object
```
public class Metered
```

इंटीग्रेशन के लिए मीटरड मेथड प्रदान करता है

इस उदाहरण में, मापित सार्वजनिक और निजी कुंजी सेट करने का प्रयास किया जाएगा।

// घटक jar फ़ाइल: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey");
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [Metered()](#Metered--) |  |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [FlushTimeout_internalized](#FlushTimeout-internalized) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट इस उदाहरण के बराबर है या नहीं। |
| [getClass()](#getClass--) |  |
| [getConsumptionCredit()](#getConsumptionCredit--) | उपभोग क्रेडिट प्राप्त करता है |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | उपभोग फ़ाइल आकार प्राप्त करता है |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | मापित सार्वजनिक और निजी कुंजी सेट करता है |
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


निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट इस उदाहरण के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस इंस्टेंस के साथ तुलना करने के लिए ऑब्जेक्ट। |

**Returns:**
बूलियन -  true  यदि निर्दिष्ट ऑब्जेक्ट इस इंस्टेंस के बराबर है; अन्यथा,  false .
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


उपभोग क्रेडिट प्राप्त करता है

**Returns:**
java.math.BigDecimal - उपभोग मात्रा
### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


उपभोग फ़ाइल आकार प्राप्त करता है

**Returns:**
java.math.BigDecimal - उपभोग फ़ाइल आकार
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


मापित सार्वजनिक और निजी कुंजी सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| publicKey | java.lang.String | सार्वजनिक कुंजी |
| privateKey | java.lang.String | निजी कुंजी |

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

