---
title: "ImageAttributes.SetWrapMode"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة ImageAttributes. تضبط وضع الالتفاف الذي يُستخدم لتحديد كيفية تغطية نسيج عبر شكل أو عند حدود الشكل. يتم تغطية النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يملأه."
type: docs
weight: 210
url: /ar/net/aspose.psd/imageattributes/setwrapmode/
---
{{< psd/tize >}}
## SetWrapMode(WrapMode) {#setwrapmode}

يضبط وضع الالتفاف المستخدم لتحديد كيفية تغطية النسيج عبر الشكل، أو عند حدود الشكل. يتم تغطية النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يتم تغطيته.

```csharp
public void SetWrapMode(WrapMode mode)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| mode | WrapMode | عنصر من [`WrapMode`](../../wrapmode/) يحدد كيفية استخدام النسخ المتكررة لصورة لتغطية منطقة. |

### انظر أيضًا

* enum [WrapMode](../../wrapmode/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color) {#setwrapmode_1}

يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تغطية النسيج عبر الشكل، أو عند حدود الشكل. يتم تغطية النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يتم تغطيته.

```csharp
public void SetWrapMode(WrapMode mode, Color color)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| mode | WrapMode | عنصر من [`WrapMode`](../../wrapmode/) يحدد كيفية استخدام النسخ المتكررة لصورة لتغطية منطقة. |
| color | Color | كائن [`ImageAttributes`](../) يحدد لون البكسلات خارج الصورة المُرَسَمة. يكون هذا اللون مرئياً إذا تم ضبط معلمة الوضع على Clamp وكان المستطيل المصدر الممرّر إلى DrawImage أكبر من الصورة نفسها. |

### انظر أيضًا

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color, bool) {#setwrapmode_2}

يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تغطية النسيج عبر الشكل، أو عند حدود الشكل. يتم تغطية النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يتم تغطيته.

```csharp
public void SetWrapMode(WrapMode mode, Color color, bool clamp)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| mode | WrapMode | عنصر من [`WrapMode`](../../wrapmode/) يحدد كيفية استخدام النسخ المتكررة لصورة لتغطية منطقة. |
| لون | لون | كائن لون يحدد لون البكسلات خارج الصورة المُرَسَمة. يكون هذا اللون مرئياً إذا تم ضبط معلمة الوضع على Clamp وكان المستطيل المصدر الممرّر إلى DrawImage أكبر من الصورة نفسها. |
| قابض | Boolean | هذه المعلمة لا تأثير لها. اضبطها على false. |

### انظر أيضًا

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


