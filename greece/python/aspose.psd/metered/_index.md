---
title: "Metered Κλάση"
type: docs
weight: 3030
url: /el/python-net/aspose.psd/metered/
---

**Summary:** Provides methods to set metered key.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Metered

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [Metered()](#Metered__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης Metered |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | Λαμβάνει πίστωση κατανάλωσης |
| [get_consumption_quantity()](#get_consumption_quantity__2) | Λαμβάνει το μέγεθος αρχείου κατανάλωσης |
| [get_product_name()](#get_product_name__3) | Λαμβάνει το όνομα του προϊόντος. |
| [is_metered_licensed()](#is_metered_licensed__4) | Ελέγξτε εάν το Metered είναι αδειοδοτημένο |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_5) | Ορίζει το δημόσιο και ιδιωτικό κλειδί του Metered.<br/>            Εάν αγοράσετε άδεια Metered, όταν ξεκινάτε την εφαρμογή, αυτό το API πρέπει να κληθεί, συνήθως αυτό είναι αρκετό. <br/>            Ωστόσο, εάν αποτυγχάνει συνεχώς η μεταφόρτωση δεδομένων κατανάλωσης και υπερβεί τις 24 ώρες, η άδεια θα οριστεί σε κατάσταση αξιολόγησης, <br/>            για να αποφύγετε τέτοια περίπτωση, θα πρέπει να ελέγχετε τακτικά την κατάσταση της άδειας· εάν είναι σε κατάσταση αξιολόγησης, καλέστε ξανά αυτό το API. |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης Metered

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

Λαμβάνει πίστωση κατανάλωσης

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| δεκαδικός | ποσότητα κατανάλωσης |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

Λαμβάνει το μέγεθος αρχείου κατανάλωσης

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| δεκαδικός | ποσότητα κατανάλωσης |


### Method: get_product_name() {#get_product_name__3}


```
 get_product_name() 
```

Λαμβάνει το όνομα του προϊόντος.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Όνομα αδειοδοτημένου προϊόντος |


### Method: is_metered_licensed()  [static] {#is_metered_licensed__4}


```
 is_metered_licensed() 
```

Ελέγξτε εάν το Metered είναι αδειοδοτημένο

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αληθές ή ψευδές |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_5}


```
 set_metered_key(public_key, private_key) 
```

Ορίζει το δημόσιο και ιδιωτικό κλειδί του Metered.<br/>            Εάν αγοράσετε άδεια Metered, όταν ξεκινάτε την εφαρμογή, αυτό το API πρέπει να κληθεί, συνήθως αυτό είναι αρκετό. <br/>            Ωστόσο, εάν αποτυγχάνει συνεχώς η μεταφόρτωση δεδομένων κατανάλωσης και υπερβεί τις 24 ώρες, η άδεια θα οριστεί σε κατάσταση αξιολόγησης, <br/>            για να αποφύγετε τέτοια περίπτωση, θα πρέπει να ελέγχετε τακτικά την κατάσταση της άδειας· εάν είναι σε κατάσταση αξιολόγησης, καλέστε ξανά αυτό το API.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| public_key | string | δημόσιο κλειδί |
| private_key | string | ιδιωτικό κλειδί |

