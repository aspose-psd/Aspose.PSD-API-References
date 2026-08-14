---
title: "Metered क्लास"
type: docs
weight: 3030
url: /hi/python-net/aspose.psd/metered/
---

**Summary:** Provides methods to set metered key.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Metered

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [Metered()](#Metered__1) | Metered क्लास का नया उदाहरण प्रारंभ करता है |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | उपभोग क्रेडिट प्राप्त करता है |
| [get_consumption_quantity()](#get_consumption_quantity__2) | उपभोग फ़ाइल आकार प्राप्त करता है |
| [get_product_name()](#get_product_name__3) | उत्पाद का नाम प्राप्त करता है। |
| [is_metered_licensed()](#is_metered_licensed__4) | जाँचें कि Metered लाइसेंस प्राप्त है या नहीं |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_5) | Metered सार्वजनिक और निजी कुंजी सेट करता है।<br/>            यदि आप Metered लाइसेंस खरीदते हैं, तो एप्लिकेशन शुरू करने पर इस API को कॉल किया जाना चाहिए, सामान्यतः यह पर्याप्त है। <br/>            हालांकि, यदि उपभोग डेटा अपलोड करने में लगातार विफल रहता है और 24 घंटे से अधिक हो जाता है, तो लाइसेंस को मूल्यांकन स्थिति में सेट कर दिया जाएगा, <br/>            ऐसे मामले से बचने के लिए, आपको नियमित रूप से लाइसेंस स्थिति जाँचनी चाहिए, यदि यह मूल्यांकन स्थिति है, तो इस API को फिर से कॉल करें। |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

Metered क्लास का नया उदाहरण प्रारंभ करता है

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

उपभोग क्रेडिट प्राप्त करता है

**Returns**

| प्रकार | विवरण |
| :- | :- |
| दशमलव | उपभोग मात्रा |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

उपभोग फ़ाइल आकार प्राप्त करता है

**Returns**

| प्रकार | विवरण |
| :- | :- |
| दशमलव | उपभोग मात्रा |


### Method: get_product_name() {#get_product_name__3}


```
 get_product_name() 
```

उत्पाद का नाम प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | लाइसेंस प्राप्त उत्पाद का नाम |


### Method: is_metered_licensed()  [static] {#is_metered_licensed__4}


```
 is_metered_licensed() 
```

जाँचें कि Metered लाइसेंस प्राप्त है या नहीं

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | सही या गलत |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_5}


```
 set_metered_key(public_key, private_key) 
```

Metered सार्वजनिक और निजी कुंजी सेट करता है।<br/>            यदि आप Metered लाइसेंस खरीदते हैं, तो एप्लिकेशन शुरू करने पर इस API को कॉल किया जाना चाहिए, सामान्यतः यह पर्याप्त है। <br/>            हालांकि, यदि उपभोग डेटा अपलोड करने में लगातार विफल रहता है और 24 घंटे से अधिक हो जाता है, तो लाइसेंस को मूल्यांकन स्थिति में सेट कर दिया जाएगा, <br/>            ऐसे मामले से बचने के लिए, आपको नियमित रूप से लाइसेंस स्थिति जाँचनी चाहिए, यदि यह मूल्यांकन स्थिति है, तो इस API को फिर से कॉल करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| public_key | string | सार्वजनिक कुंजी |
| private_key | string | निजी कुंजी |

