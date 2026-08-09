---
title: "Color.FromArgb"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة Color. تنشئ بنية Color من قيمة ARGB 32‑بت"
type: docs
weight: 1430
url: /ar/net/aspose.psd/color/fromargb/
---
{{< psd/tize >}}
## FromArgb(int) {#fromargb}

ينشئ بنية [`Color`](../) من قيمة ARGB 32‑بت.

```csharp
public static Color FromArgb(int argb)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| argb | Int32 | قيمة تحدد قيمة ARGB 32‑بت. |

### قيمة الإرجاع

بنية [`Color`](../) التي تنشئها هذه الطريقة.

### انظر أيضًا

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

ينشئ بنية [`Color`](../) من القيم الأربعة لمكوّنات ARGB (alpha، red، green، و blue). على الرغم من أن هذه الطريقة تسمح بتمرير قيمة 32‑بت لكل مكوّن، فإن قيمة كل مكوّن محدودة بـ 8‑بت.

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| alpha | Int32 | المكوّن alpha. القيم الصالحة هي من 0 إلى 255. |
| أحمر | Int32 | المكوّن red. القيم الصالحة هي من 0 إلى 255. |
| أخضر | Int32 | المكوّن green. القيم الصالحة هي من 0 إلى 255. |
| أزرق | Int32 | المكوّن blue. القيم الصالحة هي من 0 إلى 255. |

### قيمة الإرجاع

الـ [`Color`](../) الذي تنشئه هذه الطريقة.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | *alpha*، *red*، *green* أو *blue* أصغر من 0 أو أكبر من 255. |

### انظر أيضًا

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

ينشئ بنية [`Color`](../) من بنية [`Color`](../) المحددة، ولكن مع قيمة ألفا الجديدة المحددة. على الرغم من أن هذه الطريقة تسمح بتمرير قيمة 32‑بت لقيمة ألفا، فإن القيمة محدودة بـ 8‑بت.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| alpha | Int32 | قيمة ألفا للـ [`Color`](../) الجديد. القيم الصالحة هي من 0 إلى 255. |
| baseColor | Color | الـ [`Color`](../) الذي يُنشأ منه الـ [`Color`](../) الجديد. |

### قيمة الإرجاع

الـ [`Color`](../) الذي تنشئه هذه الطريقة.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* أصغر من 0 أو أكبر من 255. |

### انظر أيضًا

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

ينشئ بنية [`Color`](../) من قيم الألوان 8‑بت المحددة (أحمر، أخضر، وأزرق). قيمة ألفا هي 255 ضمنيًا (معتمة تمامًا). على الرغم من أن هذه الطريقة تسمح بتمرير قيمة 32‑بت لكل مكوّن لون، فإن قيمة كل مكوّن محدودة بـ 8‑بت.

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| red | Int32 | قيمة المكوّن الأحمر للـ [`Color`](../) الجديد. القيم الصالحة هي من 0 إلى 255. |
| green | Int32 | قيمة المكوّن الأخضر للـ [`Color`](../) الجديد. القيم الصالحة هي من 0 إلى 255. |
| blue | Int32 | قيمة المكوّن الأزرق للـ [`Color`](../) الجديد. القيم الصالحة هي من 0 إلى 255. |

### قيمة الإرجاع

الـ [`Color`](../) الذي تنشئه هذه الطريقة.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | *red*، *green* أو *blue* أصغر من 0 أو أكبر من 255. |

### انظر أيضًا

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


