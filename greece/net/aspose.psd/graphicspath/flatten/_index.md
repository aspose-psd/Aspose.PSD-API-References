---
title: "GraphicsPath.Flatten"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος GraphicsPath. Μετατρέπει κάθε καμπύλη σε αυτό το μονοπάτι σε μια ακολουθία συνδεδεμένων τμημάτων γραμμής."
type: docs
weight: 90
url: /el/net/aspose.psd/graphicspath/flatten/
---
{{< psd/tize >}}
## Flatten() {#flatten}

Μετατρέπει κάθε καμπύλη σε αυτή τη διαδρομή σε μια ακολουθία συνδεδεμένων τμημάτων γραμμής.

```csharp
public void Flatten()
```

### Δείτε επίσης

* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix) {#flatten_1}

Εφαρμόζει τον καθορισμένο μετασχηματισμό και στη συνέχεια μετατρέπει κάθε καμπύλη σε αυτό το [`GraphicsPath`](../) σε μια ακολουθία συνδεδεμένων τμημάτων γραμμής.

```csharp
public void Flatten(Matrix matrix)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | Matrix | Ένα [`Matrix`](../../matrix/) με το οποίο θα μετασχηματιστεί αυτό το [`GraphicsPath`](../) πριν την εξομάλυνση. |

### Δείτε επίσης

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

Μετατρέπει κάθε καμπύλη σε αυτό το [`GraphicsPath`](../) σε μια ακολουθία συνδεδεμένων τμημάτων γραμμής.

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | Matrix | Ένα [`Matrix`](../../matrix/) με το οποίο θα μετασχηματιστεί αυτό το [`GraphicsPath`](../) πριν την εξομάλυνση. |
| επίπεδο | Single | Καθορίζει το μέγιστο επιτρεπόμενο σφάλμα μεταξύ της καμπύλης και της εξομαλυνμένης προσέγγισής της. Μια τιμή 0.25 είναι η προεπιλογή. Η μείωση της τιμής επίπεδοτητας θα αυξήσει τον αριθμό των τμημάτων γραμμής στην προσέγγιση. |

### Δείτε επίσης

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


