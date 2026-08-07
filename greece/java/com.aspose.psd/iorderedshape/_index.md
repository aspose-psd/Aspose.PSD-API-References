---
title: "IOrderedShape"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αντιπροσωπεύει ένα διατεταγμένο σχήμα."
type: docs
weight: 129
url: /el/java/com.aspose.psd/iorderedshape/
---
```
public interface IOrderedShape
```

Αναπαριστά ένα διατεταγμένο σχήμα. Ένα διατεταγμένο σχήμα είναι ένα συνεχές σύνολο σημείων που έχει σημείο έναρξης και σημείο λήξης. Το συνεχές σύνολο σημείων συνδέεται χρησιμοποιώντας έναν συγκεκριμένο κανόνα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getEndPoint()](#getEndPoint--) | Λαμβάνει το σημείο λήξης του σχήματος. |
| [getStartPoint()](#getStartPoint--) | Λαμβάνει το σημείο έναρξης του σχήματος. |
| [isClosed()](#isClosed--) | Λαμβάνει μια τιμή που υποδεικνύει εάν το διατεταγμένο σχήμα είναι κλειστό. |
| [reverse()](#reverse--) | Αντιστρέφει τη σειρά των σημείων για αυτό το σχήμα. |
| [setClosed(boolean value)](#setClosed-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν το διατεταγμένο σχήμα είναι κλειστό. |
### getEndPoint() {#getEndPoint--}
```
public abstract PointF getEndPoint()
```


Λαμβάνει το σημείο λήξης του σχήματος.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The ending shape point.
### getStartPoint() {#getStartPoint--}
```
public abstract PointF getStartPoint()
```


Λαμβάνει το σημείο έναρξης του σχήματος.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The starting shape point.
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν το διατεταγμένο σχήμα είναι κλειστό. Κατά την επεξεργασία κλειστού διατεταγμένου σχήματος τα σημεία έναρξης και λήξης δεν έχουν νόημα.

**Returns:**
boolean -  true  αν αυτό το διατεταγμένο σχήμα είναι κλειστό· διαφορετικά,  false .
### reverse() {#reverse--}
```
public abstract void reverse()
```


Αντιστρέφει τη σειρά των σημείων για αυτό το σχήμα.

### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει αν το διατεταγμένο σχήμα είναι κλειστό. Κατά την επεξεργασία κλειστού διατεταγμένου σχήματος τα αρχικά και τελικά σημεία δεν έχουν νόημα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | true  αν αυτό το διατεταγμένο σχήμα είναι κλειστό· διαφορετικά,  false . |

