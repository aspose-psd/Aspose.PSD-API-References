---
title: Color.FromArgb
second_title: Aspose.PSD لمرجع .NET API
description: Color طريقة. ينشئ ملفColor بنية من قيمة ARGB 32 بت.
type: docs
weight: 1430
url: /ar/net/aspose.psd/color/fromargb/
---
## FromArgb(int) {#fromargb}

ينشئ ملف[`Color`](../) بنية من قيمة ARGB 32 بت.

```csharp
public static Color FromArgb(int argb)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| argb | Int32 | قيمة تحدد قيمة ARGB 32 بت. |

### قيمة الإرجاع

ال[`Color`](../) الهيكل الذي تخلقه هذه الطريقة.

### أنظر أيضا

* struct [Color](../)
* مساحة الاسم [Aspose.PSD](../../color/)
* المجسم [Aspose.PSD](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

ينشئ ملف[`Color`](../) هيكل من قيم مكون ARGB الأربعة (ألفا ، أحمر ، أخضر ، وأزرق). على الرغم من أن هذه الطريقة تسمح بتمرير قيمة 32 بت لكل مكون ، فإن قيمة كل مكون تقتصر على 8 بت.

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| alpha | Int32 | مكون ألفا. القيم الصالحة من 0 إلى 255. |
| red | Int32 | المكون الأحمر. القيم الصالحة من 0 إلى 255. |
| green | Int32 | المكون الأخضر. القيم الصالحة من 0 إلى 255. |
| blue | Int32 | المكون الأزرق. القيم الصالحة من 0 إلى 255. |

### قيمة الإرجاع

ال[`Color`](../) التي تخلقها هذه الطريقة.

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* و*red* و*green* ، أو*blue* أصغر من 0 أو أكبر من 255. |

### أنظر أيضا

* struct [Color](../)
* مساحة الاسم [Aspose.PSD](../../color/)
* المجسم [Aspose.PSD](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

ينشئ ملف[`Color`](../) هيكل من المحدد[`Color`](../) ولكن مع قيمة ألفا الجديدة المحددة. على الرغم من أن هذه الطريقة تسمح بتمرير قيمة 32 بت لقيمة ألفا ، فإن القيمة تقتصر على 8 بت.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| alpha | Int32 | قيمة ألفا الجديدة[`Color`](../). القيم الصالحة من 0 إلى 255. |
| baseColor | Color | ال[`Color`](../) التي يتم إنشاء الجديد منها[`Color`](../). |

### قيمة الإرجاع

ال[`Color`](../) التي تخلقها هذه الطريقة.

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* أصغر من 0 أو أكبر من 255. |

### أنظر أيضا

* struct [Color](../)
* مساحة الاسم [Aspose.PSD](../../color/)
* المجسم [Aspose.PSD](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

ينشئ ملف[`Color`](../) هيكل من قيم الألوان المحددة 8 بت (الأحمر والأخضر والأزرق). قيمة ألفا هي ضمنيًا 255 (معتمة تمامًا). على الرغم من أن هذه الطريقة تسمح بتمرير قيمة 32 بت لكل مكون لون ، فإن قيمة كل مكون تقتصر على 8 بت.

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| red | Int32 | قيمة المكون الأحمر للجديد[`Color`](../). القيم الصالحة من 0 إلى 255. |
| green | Int32 | قيمة المكون الأخضر للجديد[`Color`](../). القيم الصالحة من 0 إلى 255. |
| blue | Int32 | قيمة المكون الأزرق للجديد[`Color`](../). القيم الصالحة من 0 إلى 255. |

### قيمة الإرجاع

ال[`Color`](../) التي تخلقها هذه الطريقة.

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | *red* و*green* ، أو*blue* أصغر من 0 أو أكبر من 255. |

### أنظر أيضا

* struct [Color](../)
* مساحة الاسم [Aspose.PSD](../../color/)
* المجسم [Aspose.PSD](../../../)


