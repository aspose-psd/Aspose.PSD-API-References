---
title: "IOrderedShape"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل شكلًا مرتبًا."
type: docs
weight: 129
url: /ar/java/com.aspose.psd/iorderedshape/
---
```
public interface IOrderedShape
```

يمثل شكلًا مرتبًا. الشكل المرتب هو مجموعة مستمرة من النقاط لها نقطة بداية ونقطة نهاية. مجموعة النقاط المستمرة متصلة باستخدام قاعدة محددة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getEndPoint()](#getEndPoint--) | يحصل على نقطة النهاية للشكل. |
| [getStartPoint()](#getStartPoint--) | يحصل على نقطة البداية للشكل. |
| [isClosed()](#isClosed--) | يحصل على قيمة تشير إلى ما إذا كان الشكل المرتب مغلقًا. |
| [reverse()](#reverse--) | يعكس ترتيب النقاط لهذا الشكل. |
| [setClosed(boolean value)](#setClosed-boolean-) | يضبط قيمة تشير إلى ما إذا كان الشكل المرتب مغلقًا. |
### getEndPoint() {#getEndPoint--}
```
public abstract PointF getEndPoint()
```


يحصل على نقطة النهاية للشكل.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The ending shape point.
### getStartPoint() {#getStartPoint--}
```
public abstract PointF getStartPoint()
```


يحصل على نقطة البداية للشكل.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The starting shape point.
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


يحصل على قيمة تشير إلى ما إذا كان الشكل المرتب مغلقًا. عند معالجة شكل مرتب مغلق لا تكون نقطتا البداية والنهاية ذات معنى.

**Returns:**
منطقي -  true  إذا كان هذا الشكل المرتب مغلقًا؛ وإلا،  false .
### reverse() {#reverse--}
```
public abstract void reverse()
```


يعكس ترتيب النقاط لهذا الشكل.

### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان الشكل المرتب مغلقًا. عند معالجة شكل مرتب مغلق لا تكون نقطتا البداية والنهاية ذات معنى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | true  إذا كان هذا الشكل المرتب مغلقًا؛ وإلا،  false . |

