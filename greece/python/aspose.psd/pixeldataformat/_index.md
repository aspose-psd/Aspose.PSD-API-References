---
title: "Κλάση PixelDataFormat"
type: docs
weight: 3450
url: /el/python-net/aspose.psd/pixeldataformat/
---

**Summary:** The pixel data format. This is an immutable object.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.PixelDataFormat

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| bits_per_pixel | int | r | Λαμβάνει τα bits ανά pixel. |
| λεζάντα | string | r | Λαμβάνει τη λεζάντα μορφής δεδομένων pixel. |
| channel_bits | int | r | Λαμβάνει τον αριθμό των δυαδικών για κάθε κανάλι. |
| channels_count | int | r | Λαμβάνει τον αριθμό των καναλιών. |
| cmyk [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Λαμβάνει το [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) ορισμένο για 32 bit ανά pixel με 8 bit για το κυανό, ματζέντα, κίτρινο και μαύρο. |
| cmyka [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Λαμβάνει το acmyk. |
| grayscale [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Λαμβάνει το [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) ορισμένο για 8 bit ανά pixel με 8 bit που αντιπροσωπεύουν την ένταση γκρι σε διάστημα 0-255. |
| grayscale_alpha [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Λαμβάνει το [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) ορισμένο για 16 bit ανά pixel με 8 bit που αντιπροσωπεύουν την ένταση γκρι σε διάστημα 0-255 και πρόσθετο 8-bit στοιχείο άλφα. |
| pixel_format | [PixelFormat](/psd/python-net/aspose.psd/pixelformat) | r | Λαμβάνει τη μορφή pixel. |
| rgb_16_bpp_555 [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Λαμβάνει το [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) ορισμένο για 16 bit ανά pixel με 5 bit για το κόκκινο, το πράσινο και το μπλε, το άλφα δεν ορίζεται. |
| rgb_16_bpp_565 [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Λαμβάνει το [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) ορισμένο για 16 bit ανά pixel με 5 bit για το κόκκινο, 6 bit για το πράσινο και 5 bit για το μπλε, το άλφα δεν ορίζεται. |
| rgb_24_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Λαμβάνει το [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) ορισμένο για 24 bit ανά pixel με 8 bit για το άλφα, το κόκκινο, το πράσινο και το μπλε, το άλφα δεν ορίζεται. |
| rgb_24_bpp_png [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Λαμβάνει το [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) ορισμένο για 24 bit ανά pixel με 8 bit για το άλφα, το κόκκινο, το πράσινο και το μπλε, το άλφα δεν ορίζεται. |
| rgb_32_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Λαμβάνει το [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) ορισμένο για 32 bit ανά pixel με 8 bit για το άλφα, το κόκκινο, το πράσινο και το μπλε. |
| rgb_indexed_1_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Λαμβάνει το [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) ορισμένο για ευρετηριασμένο 1 bit ανά χρώμα.<br/>            Η ευρετηριασμένη αποθήκευση δεδομένων pixel προορίζεται να επιτρέπει την αποθήκευση και ανάκτηση δεδομένων όπου χρησιμοποιείται η παλέτα χρωμάτων.<br/>            Χρησιμοποιήστε με προσοχή, επειδή μπορεί να απαιτήσει μετατροπή από μια παλέτα σε άλλη ή από RGBA σε ευρετηριακό μοντέλο χρώματος. |
| rgb_indexed_2_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Λαμβάνει το [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) ορισμένο για ευρετηριασμένο 2 bit ανά χρώμα.<br/>            Η αποθήκευση ευρετηριασμένων δεδομένων pixel προορίζεται να επιτρέπει την αποθήκευση και ανάκτηση δεδομένων όπου χρησιμοποιείται η παλέτα χρωμάτων.<br/>            Χρησιμοποιήστε με προσοχή, επειδή μπορεί να απαιτήσει μετατροπή από μία παλέτα σε άλλη ή από RGBA σε ευρετηριακό μοντέλο χρώματος. |
| rgb_indexed_4_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Λαμβάνει το [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) ορισμένο για ευρετηριασμένο 4 bit ανά χρώμα.<br/>            Η αποθήκευση ευρετηριασμένων δεδομένων pixel προορίζεται να επιτρέπει την αποθήκευση και ανάκτηση δεδομένων όπου χρησιμοποιείται η παλέτα χρωμάτων.<br/>            Χρησιμοποιήστε με προσοχή, επειδή μπορεί να απαιτήσει μετατροπή από μία παλέτα σε άλλη ή από RGBA σε ευρετηριακό μοντέλο χρώματος. |
| rgb_indexed_8_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Λαμβάνει το [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) ορισμένο για ευρετηριασμένο 8 bit ανά χρώμα.<br/>            Η αποθήκευση ευρετηριασμένων δεδομένων pixel προορίζεται να επιτρέπει την αποθήκευση και ανάκτηση δεδομένων όπου χρησιμοποιείται η παλέτα χρωμάτων.<br/>            Χρησιμοποιήστε με προσοχή, επειδή μπορεί να απαιτήσει μετατροπή από μία παλέτα σε άλλη ή από RGBA σε ευρετηριακό μοντέλο χρώματος. |
| rgba_32_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Λαμβάνει το [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) ορισμένο για 32 bit ανά pixel με 8 bit για το άλφα, το κόκκινο, το πράσινο και το μπλε. |
| rgba_64_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Λαμβάνει το [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) ορισμένο για 64 bit ανά pixel με 16 bit για καθένα από τα alpha, red, green και blue. |
| y_cb_cr [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Λαμβάνει το [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) ορισμένο για 24 bit ανά pixel με 8 bit για καθένα από τα luma, blue-difference και red-difference χρωματικά συστατικά. |
| ycck [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Λαμβάνει το [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) ορισμένο για 32 bit ανά pixel με 8 bit για καθένα από τα luma, blue-difference, red-difference και black χρωματικά συστατικά. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_bgr(bits_per_sample)](#get_bgr_bits_per_sample_1) | Λαμβάνει χρώμα BGRA με καθορισμένο αριθμό bits ανά δείγμα. |
| [get_bgra(bits_per_sample)](#get_bgra_bits_per_sample_2) | Λαμβάνει χρώμα BGRA με καθορισμένο αριθμό bits ανά δείγμα. |
| [get_cie_lab(bits_per_l, bits_per_a, bits_per_b)](#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_3) | Λαμβάνει χρώμα CIE Lab με καθορισμένο αριθμό bits ανά δείγμα. |
| [get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)](#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_4) | Λαμβάνει χρώμα CMYK με καθορισμένο αριθμό bits ανά δείγμα. |
| [get_cmyk(bits_per_sample)](#get_cmyk_bits_per_sample_5) | Λαμβάνει χρώμα CMYK με καθορισμένο αριθμό bits ανά δείγμα. |
| [get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)](#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_6) | Λαμβάνει χρώμα CMYKA με καθορισμένο αριθμό bits ανά δείγμα. |
| [get_grayscale(bits_per_sample)](#get_grayscale_bits_per_sample_7) | Λαμβάνει χρώμα Grayscale με καθορισμένο αριθμό bits ανά δείγμα. |
| [get_grayscale_alpha(bits_per_sample)](#get_grayscale_alpha_bits_per_sample_8) | Λαμβάνει χρώμα GrayscaleAlpha με καθορισμένο αριθμό bits ανά δείγμα. |
| [get_grayscale_alpha(bits_per_sample, alpha_channel_bits)](#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_9) | Λαμβάνει χρώμα GrayscaleAlpha με καθορισμένο αριθμό bits ανά δείγμα. |
| [get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)](#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_10) | Λαμβάνει χρώμα RGB με καθορισμένο αριθμό bits ανά δείγμα. |
| [get_rgb(bits_per_sample)](#get_rgb_bits_per_sample_11) | Λαμβάνει χρώμα RGB με καθορισμένο αριθμό bits ανά δείγμα. |
| [get_rgb_indexed(bits_per_sample)](#get_rgb_indexed_bits_per_sample_12) | Λαμβάνει ευρετηριασμένο χρώμα BGRA με καθορισμένο αριθμό bits ανά δείγμα. |
| [get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)](#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_13) | Λαμβάνει χρώμα RGBA με καθορισμένο αριθμό bits ανά δείγμα. |
| [get_rgba(bits_per_sample)](#get_rgba_bits_per_sample_14) | Λαμβάνει χρώμα RGBA με καθορισμένο αριθμό bits ανά δείγμα. |
| [get_y_cb_cr(bits_per_sample)](#get_y_cb_cr_bits_per_sample_15) | Λαμβάνει χρώμα YCbCr με καθορισμένο αριθμό bits ανά δείγμα. |
| [get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)](#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_16) | Λαμβάνει χρώμα YCbCr με καθορισμένο αριθμό bits ανά δείγμα. |
| [get_ycck(bits_per_sample)](#get_ycck_bits_per_sample_17) | Λαμβάνει χρώμα YCCK με καθορισμένο αριθμό bits ανά δείγμα. |


### Method: get_bgr(bits_per_sample)  [static] {#get_bgr_bits_per_sample_1}


```
 get_bgr(bits_per_sample) 
```

Λαμβάνει χρώμα BGRA με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bits_per_sample | int | Ο αριθμός των bits ανά δείγμα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Το χρώμα BGRA. |


### Method: get_bgra(bits_per_sample)  [static] {#get_bgra_bits_per_sample_2}


```
 get_bgra(bits_per_sample) 
```

Λαμβάνει χρώμα BGRA με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bits_per_sample | int | Ο αριθμός των bits ανά δείγμα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Το χρώμα BGRA. |


### Method: get_cie_lab(bits_per_l, bits_per_a, bits_per_b)  [static] {#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_3}


```
 get_cie_lab(bits_per_l, bits_per_a, bits_per_b) 
```

Λαμβάνει χρώμα CIE Lab με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bits_per_l | int | Ο αριθμός των bits ανά κανάλι L. |
| bits_per_a | int | Ο αριθμός των bits ανά κανάλι A. |
| bits_per_b | int | Ο αριθμός των bits ανά κανάλι B. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Το χρώμα CIE Lab. |


### Method: get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)  [static] {#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_4}


```
 get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel) 
```

Λαμβάνει χρώμα CMYK με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bits_per_cyan_channel | int | Ο αριθμός των bits ανά κανάλι Cyan. |
| bits_per_magenta_channel | int | Ο αριθμός των bits ανά κανάλι Magenta. |
| bits_per_yellow_channel | int | Ο αριθμός των bits ανά κανάλι Yellow. |
| bits_per_key_channel | int | Ο αριθμός των bits ανά κανάλι Key. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Το χρώμα CMYK. |


### Method: get_cmyk(bits_per_sample)  [static] {#get_cmyk_bits_per_sample_5}


```
 get_cmyk(bits_per_sample) 
```

Λαμβάνει χρώμα CMYK με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bits_per_sample | int | Ο αριθμός των bits ανά δείγμα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Το χρώμα CMYK. |


### Method: get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)  [static] {#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_6}


```
 get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel) 
```

Λαμβάνει χρώμα CMYKA με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bits_per_cyan_channel | int | Ο αριθμός των bits ανά κανάλι Cyan. |
| bits_per_magenta_channel | int | Ο αριθμός των bits ανά κανάλι Magenta. |
| bits_per_yellow_channel | int | Ο αριθμός των bits ανά κανάλι Yellow. |
| bits_per_key_channel | int | Ο αριθμός των bits ανά κανάλι Key. |
| bits_per_alpha_channel | int | Ο αριθμός των bits ανά κανάλι Alpha. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Το χρώμα CMYK. |


### Method: get_grayscale(bits_per_sample)  [static] {#get_grayscale_bits_per_sample_7}


```
 get_grayscale(bits_per_sample) 
```

Λαμβάνει χρώμα Grayscale με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bits_per_sample | int | Ο αριθμός των bits ανά δείγμα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Το χρώμα Grayscale. |


### Method: get_grayscale_alpha(bits_per_sample)  [static] {#get_grayscale_alpha_bits_per_sample_8}


```
 get_grayscale_alpha(bits_per_sample) 
```

Λαμβάνει χρώμα GrayscaleAlpha με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bits_per_sample | int | Ο αριθμός των bits ανά δείγμα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Το χρώμα GrayscaleAlpha. |


### Method: get_grayscale_alpha(bits_per_sample, alpha_channel_bits)  [static] {#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_9}


```
 get_grayscale_alpha(bits_per_sample, alpha_channel_bits) 
```

Λαμβάνει χρώμα GrayscaleAlpha με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bits_per_sample | int | Ο αριθμός των bits ανά δείγμα. |
| alpha_channel_bits | int | Ο αριθμός των bits ανά δείγμα στο κανάλι alpha. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Το χρώμα GrayscaleAlpha. |


### Method: get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)  [static] {#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_10}


```
 get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel) 
```

Λαμβάνει χρώμα RGB με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bits_per_red_channel | int | Ο αριθμός των bits ανά κανάλι Red. |
| bits_per_green_channel | int | Ο αριθμός των bits ανά κανάλι Green. |
| bits_per_blue_channel | int | Ο αριθμός των bits ανά κανάλι Blue. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Το χρώμα RGB. |


### Method: get_rgb(bits_per_sample)  [static] {#get_rgb_bits_per_sample_11}


```
 get_rgb(bits_per_sample) 
```

Λαμβάνει χρώμα RGB με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bits_per_sample | int | Ο αριθμός των bits ανά δείγμα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Το χρώμα RGB. |


### Method: get_rgb_indexed(bits_per_sample)  [static] {#get_rgb_indexed_bits_per_sample_12}


```
 get_rgb_indexed(bits_per_sample) 
```

Λαμβάνει ευρετηριασμένο χρώμα BGRA με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bits_per_sample | int | Ο αριθμός των bits ανά δείγμα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Το χρώμα BGRA. |


### Method: get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)  [static] {#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_13}


```
 get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel) 
```

Λαμβάνει χρώμα RGBA με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bits_per_red_channel | int | Ο αριθμός των bits ανά κανάλι Red. |
| bits_per_green_channel | int | Ο αριθμός των bits ανά κανάλι Green. |
| bits_per_blue_channel | int | Ο αριθμός των bits ανά κανάλι Blue. |
| bits_per_alpha_channel | int | Ο αριθμός των bits ανά κανάλι Alpha. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Το χρώμα RGBA. |


### Method: get_rgba(bits_per_sample)  [static] {#get_rgba_bits_per_sample_14}


```
 get_rgba(bits_per_sample) 
```

Λαμβάνει χρώμα RGBA με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bits_per_sample | int | Ο αριθμός των bits ανά δείγμα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Το χρώμα RGBA. |


### Method: get_y_cb_cr(bits_per_sample)  [static] {#get_y_cb_cr_bits_per_sample_15}


```
 get_y_cb_cr(bits_per_sample) 
```

Λαμβάνει χρώμα YCbCr με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bits_per_sample | int | Ο αριθμός των bits ανά δείγμα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Το χρώμα YCbCr. |


### Method: get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)  [static] {#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_16}


```
 get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr) 
```

Λαμβάνει χρώμα YCbCr με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bits_per_y | int | Ο αριθμός των bits ανά κανάλι Y. |
| bits_per_cb | int | Ο αριθμός των bits ανά κανάλι Cb. |
| bits_per_cr | int | Ο αριθμός των bits ανά κανάλι Cr. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Το χρώμα YCbCr. |


### Method: get_ycck(bits_per_sample)  [static] {#get_ycck_bits_per_sample_17}


```
 get_ycck(bits_per_sample) 
```

Λαμβάνει χρώμα YCCK με καθορισμένο αριθμό bits ανά δείγμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bits_per_sample | int | Ο αριθμός των bits ανά δείγμα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Το χρώμα YCCK. |


