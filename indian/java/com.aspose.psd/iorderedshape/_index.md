---
title: "IOrderedShape"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "क्रमबद्ध आकार को दर्शाता है."
type: docs
weight: 129
url: /hi/java/com.aspose.psd/iorderedshape/
---
```
public interface IOrderedShape
```

एक क्रमबद्ध आकार का प्रतिनिधित्व करता है। एक क्रमबद्ध आकार बिंदुओं का निरंतर सेट है जिसमें एक प्रारंभ बिंदु और अंत बिंदु होता है। बिंदुओं का निरंतर सेट एक विशिष्ट नियम का उपयोग करके जुड़ा होता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getEndPoint()](#getEndPoint--) | समाप्ति आकार बिंदु प्राप्त करता है। |
| [getStartPoint()](#getStartPoint--) | प्रारंभिक आकार बिंदु प्राप्त करता है। |
| [isClosed()](#isClosed--) | एक मान प्राप्त करता है जो दर्शाता है कि क्रमबद्ध आकार बंद है या नहीं। |
| [reverse()](#reverse--) | इस आकार के बिंदुओं का क्रम उलटता है। |
| [setClosed(boolean value)](#setClosed-boolean-) | एक मान सेट करता है जो दर्शाता है कि क्रमबद्ध आकार बंद है या नहीं। |
### getEndPoint() {#getEndPoint--}
```
public abstract PointF getEndPoint()
```


समाप्ति आकार बिंदु प्राप्त करता है।

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The ending shape point.
### getStartPoint() {#getStartPoint--}
```
public abstract PointF getStartPoint()
```


प्रारंभिक आकार बिंदु प्राप्त करता है।

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The starting shape point.
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


एक मान प्राप्त करता है जो दर्शाता है कि क्रमबद्ध आकार बंद है या नहीं। जब बंद क्रमबद्ध आकार को प्रोसेस किया जाता है तो प्रारंभ और समाप्ति बिंदुओं का कोई अर्थ नहीं रहता।

**Returns:**
बूलियन -  true  यदि यह क्रमबद्ध आकार बंद है; अन्यथा,  false .
### reverse() {#reverse--}
```
public abstract void reverse()
```


इस आकार के बिंदुओं का क्रम उलटता है।

### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


एक मान सेट करता है जो दर्शाता है कि क्रमबद्ध आकार बंद है या नहीं। जब बंद क्रमबद्ध आकार को प्रोसेस किया जाता है तो प्रारंभ और समाप्त बिंदुओं का कोई अर्थ नहीं रहता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | true  यदि यह क्रमबद्ध आकार बंद है; अन्यथा,  false . |

