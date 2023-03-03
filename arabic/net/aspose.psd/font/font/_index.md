---
title: Font.Font
second_title: Aspose.PSD لمرجع .NET API
description: Font البناء. يقوم بتهيئة ملفFont يستخدم المحدد الموجودFont وFontStyle التعداد .
type: docs
weight: 10
url: /ar/net/aspose.psd/font/font/
---
## Font(Font, FontStyle) {#constructor}

يقوم بتهيئة ملف[`Font`](../) يستخدم المحدد الموجود[`Font`](../) و[`FontStyle`](../../fontstyle/) التعداد .

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| prototype | Font | الموجود[`Font`](../) التي يتم إنشاء الجديد منها[`Font`](../). |
| newStyle | FontStyle | ال[`FontStyle`](../../fontstyle/) للتقديم على الجديد[`Font`](../) . قيم متعددة لـ[`FontStyle`](../../fontstyle/) يمكن دمج التعداد مع عامل التشغيل OR. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *prototype* باطل. |

### أنظر أيضا

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* مساحة الاسم [Aspose.PSD](../../font/)
* المجسم [Aspose.PSD](../../../)

---

## Font(string, float) {#constructor_1}

يقوم بتهيئة ملف[`Font`](../) باستخدام حجم محدد. تم تعيين مجموعة الأحرف علىDefault ، وحدة الرسوماتPoint ، نمط الخط إلىRegular .

```csharp
public Font(string fontName, float emSize)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fontName | String | تمثيل سلسلة من[`Font`](../) اسم. |
| emSize | Single | حجم em ، بالنقاط ، للخط الجديد. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* أصغر من أو يساوي 0 ، يتم تقييمه إلى ما لا نهاية أو أنه ليس رقمًا صالحًا. |
| ArgumentNullException | *fontName* باطل. |

### أنظر أيضا

* class [Font](../)
* مساحة الاسم [Aspose.PSD](../../font/)
* المجسم [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

يقوم بتهيئة ملف[`Font`](../) باستخدام حجم وأسلوب محددين. تم تعيين مجموعة الأحرف علىDefault ، وحدة الرسوماتPoint .

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fontName | String | تمثيل سلسلة من[`Font`](../) اسم. |
| emSize | Single | حجم em ، بالنقاط ، للخط الجديد. |
| style | FontStyle | ال[`FontStyle`](../../fontstyle/) من الخط الجديد. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* أصغر من أو يساوي 0 ، يتم تقييمه إلى ما لا نهاية أو أنه ليس رقمًا صالحًا. |
| ArgumentNullException | *fontName* باطل. |

### أنظر أيضا

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* مساحة الاسم [Aspose.PSD](../../font/)
* المجسم [Aspose.PSD](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

يقوم بتهيئة ملف[`Font`](../) باستخدام حجم ووحدة محددين. تم تعيين مجموعة الأحرف علىDefault، تم تعيين النمط علىRegular .

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fontName | String | تمثيل سلسلة من[`Font`](../) اسم. |
| emSize | Single | حجم em للخط الجديد في الوحدات المحددة بواسطة*unit* معامل. |
| unit | GraphicsUnit | ال[`GraphicsUnit`](../../graphicsunit/) من الخط الجديد. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* أصغر من أو يساوي 0 ، يتم تقييمه إلى ما لا نهاية أو أنه ليس رقمًا صالحًا. |
| ArgumentNullException | *fontName* باطل. |

### أنظر أيضا

* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* مساحة الاسم [Aspose.PSD](../../font/)
* المجسم [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

يقوم بتهيئة ملف[`Font`](../) باستخدام حجم ونمط ووحدة ومجموعة أحرف محددة.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fontName | String | تمثيل سلسلة من[`Font`](../) اسم. |
| emSize | Single | حجم em للخط الجديد في الوحدات المحددة بواسطة*unit* معامل. |
| style | FontStyle | ال[`FontStyle`](../../fontstyle/) من الخط الجديد. |
| unit | GraphicsUnit | ال[`GraphicsUnit`](../../graphicsunit/) من الخط الجديد. |
| characterSet | CharacterSet | مجموعة أحرف لاستخدامها لهذا الخط. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* أصغر من أو يساوي 0 ، يتم تقييمه إلى ما لا نهاية أو أنه ليس رقمًا صالحًا. |
| ArgumentNullException | *fontName* باطل. |

### أنظر أيضا

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* enum [CharacterSet](../../characterset/)
* class [Font](../)
* مساحة الاسم [Aspose.PSD](../../font/)
* المجسم [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

يقوم بتهيئة ملف[`Font`](../) باستخدام حجم ونمط ووحدة محددة.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fontName | String | تمثيل سلسلة من[`Font`](../) اسم. |
| emSize | Single | حجم em للخط الجديد في الوحدات المحددة بواسطة*unit* معامل. |
| style | FontStyle | ال[`FontStyle`](../../fontstyle/) من الخط الجديد. |
| unit | GraphicsUnit | ال[`GraphicsUnit`](../../graphicsunit/) من الخط الجديد. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* أصغر من أو يساوي 0 ، يتم تقييمه إلى ما لا نهاية أو أنه ليس رقمًا صالحًا. |
| ArgumentNullException | *fontName* باطل. |

### أنظر أيضا

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* مساحة الاسم [Aspose.PSD](../../font/)
* المجسم [Aspose.PSD](../../../)


