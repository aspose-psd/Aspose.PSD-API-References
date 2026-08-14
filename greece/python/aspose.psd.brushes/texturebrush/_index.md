---
title: "TextureBrush Κλάση"
type: docs
weight: 90
url: /el/python-net/aspose.psd.brushes/texturebrush/
---

**Summary:** Each property of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class is a [Brush](/psd/python-net/aspose.psd/brush/) object that uses an image to fill the interior of a shape. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.TextureBrush

**Inheritance:** TransformBrush

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [TextureBrush(image)](#TextureBrush_image_1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) που χρησιμοποιεί την καθορισμένη εικόνα. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) που χρησιμοποιεί την καθορισμένη εικόνα και το περιοριστικό ορθογώνιο. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_3) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) που χρησιμοποιεί την καθορισμένη εικόνα και το περιοριστικό ορθογώνιο. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_4) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) που χρησιμοποιεί την καθορισμένη εικόνα, το περιοριστικό ορθογώνιο και τα χαρακτηριστικά εικόνας. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_5) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) που χρησιμοποιεί την καθορισμένη εικόνα, το περιοριστικό ορθογώνιο και τα χαρακτηριστικά εικόνας. |
| [TextureBrush(image, wrap_mode)](#TextureBrush_image_wrap_mode_6) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) που χρησιμοποιεί την καθορισμένη εικόνα και τη λειτουργία περιτύλιξης. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_7) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) που χρησιμοποιεί την καθορισμένη εικόνα, τη λειτουργία περιτύλιξης και το περιοριστικό ορθογώνιο. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_8) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) που χρησιμοποιεί την καθορισμένη εικόνα, τη λειτουργία περιτύλιξης και το περιοριστικό ορθογώνιο. |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| απορρίφθηκε | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| image | [Image](/psd/python-net/aspose.psd/image) | r | Λαμβάνει το αντικείμενο [Image](/psd/python-net/aspose.psd/image/) που σχετίζεται με αυτό το αντικείμενο [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | r | Λαμβάνει τα [TextureBrush.image_attributes](/psd/python-net/aspose.psd.brushes/texturebrush/) που σχετίζονται με αυτό το [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| image_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Λαμβάνει το [Rectangle](/psd/python-net/aspose.psd/rectangle/) που σχετίζεται με αυτό το [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| is_transform_changed | bool | r | Λαμβάνει μια τιμή που υποδεικνύει αν οι μετασχηματισμοί άλλαξαν με κάποιον τρόπο. Για παράδειγμα ορίζοντας τη μήτρα μετασχηματισμού ή<br/>            καλώντας οποιαδήποτε από τις μεθόδους που τροποποιούν τη μήτρα μετασχηματισμού. Η ιδιότητα εισάγεται για συμβατότητα με παλαιότερες εκδόσεις του GDI+. |
| opacity | float | r/w | Λαμβάνει ή ορίζει τη διαφάνεια του πινέλου. Η τιμή πρέπει να είναι μεταξύ 0 και 1. Τιμή 0 σημαίνει ότι το πινέλο είναι πλήρως ορατό, τιμή 1 σημαίνει ότι το πινέλο είναι πλήρως αδιαφανές. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Λαμβάνει ή ορίζει ένα αντίγραφο του [Matrix](/psd/python-net/aspose.psd/matrix/) που ορίζει έναν τοπικό γεωμετρικό μετασχηματισμό για αυτό το [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | r/w | Λαμβάνει ή ορίζει μια απαρίθμηση του [WrapMode](/psd/python-net/aspose.psd/wrapmode/) που υποδεικνύει τη λειτουργία περιτύλιξης για αυτό το [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Δημιουργεί ένα νέο βαθύ κλώνο του τρέχοντος [Brush](/psd/python-net/aspose.psd/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | Πολλαπλασιάζει τη [Matrix](/psd/python-net/aspose.psd/matrix/) που αντιπροσωπεύει τον τοπικό γεωμετρικό μετασχηματισμό αυτού του [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) με την καθορισμένη [Matrix](/psd/python-net/aspose.psd/matrix/) προσθέτοντας στην αρχή την καθορισμένη [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | Πολλαπλασιάζει τη [Matrix](/psd/python-net/aspose.psd/matrix/) που αντιπροσωπεύει τον τοπικό γεωμετρικό μετασχηματισμό αυτού του [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) με την καθορισμένη [Matrix](/psd/python-net/aspose.psd/matrix/) σε καθορισμένη σειρά. |
| reset_transform() | Επαναφέρει την ιδιότητα [TransformBrush.transform](/psd/python-net/aspose.psd.brushes/transformbrush/) σε ταυτοτική. |
| [rotate_transform(angle)](#rotate_transform_angle_4) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό. Αυτή η μέθοδος προσθέτει την περιστροφή στον μετασχηματισμό. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό με την καθορισμένη σειρά. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα ποσά. Αυτή η μέθοδος προσθέτει τον πίνακα κλιμάκωσης στον μετασχηματισμό. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα ποσά με την καθορισμένη σειρά. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Μετατοπίζει τον τοπικό γεωμετρικό μετασχηματισμό κατά τις καθορισμένες διαστάσεις. Αυτή η μέθοδος προσθέτει τη μετάφραση στον μετασχηματισμό. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Μετατοπίζει τον τοπικό γεωμετρικό μετασχηματισμό κατά τις καθορισμένες διαστάσεις με την καθορισμένη σειρά. |


### Constructor: TextureBrush(image) {#TextureBrush_image_1}


```
 TextureBrush(image) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) που χρησιμοποιεί την καθορισμένη εικόνα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Το αντικείμενο [Image](/psd/python-net/aspose.psd/image/) με το οποίο αυτό το αντικείμενο [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) γεμίζει εσωτερικούς χώρους. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_2}


```
 TextureBrush(image, destination_rectangle) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) που χρησιμοποιεί την καθορισμένη εικόνα και το περιοριστικό ορθογώνιο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Το αντικείμενο [Image](/psd/python-net/aspose.psd/image/) με το οποίο αυτό το αντικείμενο [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) γεμίζει εσωτερικούς χώρους. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που αντιπροσωπεύει το περιοριστικό ορθογώνιο για αυτό το αντικείμενο [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_3}


```
 TextureBrush(image, destination_rectangle) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) που χρησιμοποιεί την καθορισμένη εικόνα και το περιοριστικό ορθογώνιο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Το αντικείμενο [Image](/psd/python-net/aspose.psd/image/) με το οποίο αυτό το αντικείμενο [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) γεμίζει εσωτερικούς χώρους. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που αντιπροσωπεύει το περιοριστικό ορθογώνιο για αυτό το αντικείμενο [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_4}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) που χρησιμοποιεί την καθορισμένη εικόνα, το περιοριστικό ορθογώνιο και τα χαρακτηριστικά εικόνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Το αντικείμενο [Image](/psd/python-net/aspose.psd/image/) με το οποίο αυτό το αντικείμενο [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) γεμίζει εσωτερικούς χώρους. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που αντιπροσωπεύει το περιοριστικό ορθογώνιο για αυτό το αντικείμενο [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Ένα αντικείμενο [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) που περιέχει πρόσθετες πληροφορίες σχετικά με την εικόνα που χρησιμοποιείται από αυτό το αντικείμενο [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_5}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) που χρησιμοποιεί την καθορισμένη εικόνα, το περιοριστικό ορθογώνιο και τα χαρακτηριστικά εικόνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Το αντικείμενο [Image](/psd/python-net/aspose.psd/image/) με το οποίο αυτό το αντικείμενο [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) γεμίζει εσωτερικούς χώρους. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που αντιπροσωπεύει το περιοριστικό ορθογώνιο για αυτό το αντικείμενο [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Ένα αντικείμενο [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) που περιέχει πρόσθετες πληροφορίες σχετικά με την εικόνα που χρησιμοποιείται από αυτό το αντικείμενο [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, wrap_mode) {#TextureBrush_image_wrap_mode_6}


```
 TextureBrush(image, wrap_mode) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) που χρησιμοποιεί την καθορισμένη εικόνα και τη λειτουργία περιτύλιξης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Το αντικείμενο [Image](/psd/python-net/aspose.psd/image/) με το οποίο αυτό το αντικείμενο [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) γεμίζει εσωτερικούς χώρους. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Μια απαρίθμηση [WrapMode](/psd/python-net/aspose.psd/wrapmode/) που καθορίζει πώς το αντικείμενο [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) τοποθετείται σε πλακίδια. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_7}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) που χρησιμοποιεί την καθορισμένη εικόνα, τη λειτουργία περιτύλιξης και το περιοριστικό ορθογώνιο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Το αντικείμενο [Image](/psd/python-net/aspose.psd/image/) με το οποίο αυτό το αντικείμενο [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) γεμίζει εσωτερικούς χώρους. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Μια απαρίθμηση [WrapMode](/psd/python-net/aspose.psd/wrapmode/) που καθορίζει πώς το αντικείμενο [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) τοποθετείται σε πλακίδια. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που αντιπροσωπεύει το περιοριστικό ορθογώνιο για αυτό το αντικείμενο [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_8}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) που χρησιμοποιεί την καθορισμένη εικόνα, τη λειτουργία περιτύλιξης και το περιοριστικό ορθογώνιο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Το αντικείμενο [Image](/psd/python-net/aspose.psd/image/) με το οποίο αυτό το αντικείμενο [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) γεμίζει εσωτερικούς χώρους. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Μια απαρίθμηση [WrapMode](/psd/python-net/aspose.psd/wrapmode/) που καθορίζει πώς το αντικείμενο [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) τοποθετείται σε πλακίδια. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που αντιπροσωπεύει το περιοριστικό ορθογώνιο για αυτό το αντικείμενο [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Δημιουργεί ένα νέο βαθύ κλώνο του τρέχοντος [Brush](/psd/python-net/aspose.psd/brush/).

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Brush](/psd/python-net/aspose.psd/brush) | Ένα νέο [Brush](/psd/python-net/aspose.psd/brush/) που είναι το βαθύ αντίγραφο αυτής της παρουσίας [Brush](/psd/python-net/aspose.psd/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

Πολλαπλασιάζει τη [Matrix](/psd/python-net/aspose.psd/matrix/) που αντιπροσωπεύει τον τοπικό γεωμετρικό μετασχηματισμό αυτού του [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) με την καθορισμένη [Matrix](/psd/python-net/aspose.psd/matrix/) προσθέτοντας στην αρχή την καθορισμένη [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Ο [Matrix](/psd/python-net/aspose.psd/matrix/) με τον οποίο πολλαπλασιάζεται ο γεωμετρικός μετασχηματισμός. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

Πολλαπλασιάζει τη [Matrix](/psd/python-net/aspose.psd/matrix/) που αντιπροσωπεύει τον τοπικό γεωμετρικό μετασχηματισμό αυτού του [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) με την καθορισμένη [Matrix](/psd/python-net/aspose.psd/matrix/) σε καθορισμένη σειρά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Ο [Matrix](/psd/python-net/aspose.psd/matrix/) με τον οποίο πολλαπλασιάζεται ο γεωμετρικός μετασχηματισμός. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ένα [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) που καθορίζει με ποια σειρά να πολλαπλασιαστούν οι δύο πίνακες. |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό. Αυτή η μέθοδος προσθέτει την περιστροφή στον μετασχηματισμό.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| γωνία | float | Η γωνία περιστροφής. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό με την καθορισμένη σειρά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| γωνία | float | Η γωνία περιστροφής. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ένα [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) που καθορίζει αν θα προσαρτηθεί ή θα προστεθεί ο πίνακας περιστροφής. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα ποσά. Αυτή η μέθοδος προσθέτει τον πίνακα κλιμάκωσης στον μετασχηματισμό.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| sx | float | Το ποσό κατά το οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα x. |
| sy | float | Το ποσό κατά το οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα ποσά με την καθορισμένη σειρά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| sx | float | Το ποσό κατά το οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα x. |
| sy | float | Το ποσό κατά το οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ένα [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) που καθορίζει αν θα προσαρτηθεί ή θα προστεθεί ο πίνακας κλιμάκωσης. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

Μετατοπίζει τον τοπικό γεωμετρικό μετασχηματισμό κατά τις καθορισμένες διαστάσεις. Αυτή η μέθοδος προσθέτει τη μετάφραση στον μετασχηματισμό.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| dx | float | Η τιμή της μετάφρασης στον άξονα x. |
| dy | float | Η τιμή της μετάφρασης στο y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

Μετατοπίζει τον τοπικό γεωμετρικό μετασχηματισμό κατά τις καθορισμένες διαστάσεις με την καθορισμένη σειρά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| dx | float | Η τιμή της μετάφρασης στον άξονα x. |
| dy | float | Η τιμή της μετάφρασης στο y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Η σειρά (prepend ή append) με την οποία να εφαρμόσετε τη μετάφραση. |

