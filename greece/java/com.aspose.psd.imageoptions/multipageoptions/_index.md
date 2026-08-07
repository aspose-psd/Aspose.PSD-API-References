---
title: "MultiPageOptions"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Βασική κλάση για μορφές που υποστηρίζουν πολλαπλές σελίδες"
type: docs
weight: 17
url: /el/java/com.aspose.psd.imageoptions/multipageoptions/
---

**Inheritance:**
java.lang.Object
```
public class MultiPageOptions
```

Βασική κλάση για μορφές που υποστηρίζουν πολλαπλές σελίδες
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MultiPageOptions()](#MultiPageOptions--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  MultiPageOptions . |
| [MultiPageOptions(int[] pages)](#MultiPageOptions-int---) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  MultiPageOptions . |
| [MultiPageOptions(int[] pages, Rectangle exportArea)](#MultiPageOptions-int---com.aspose.psd.Rectangle-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  MultiPageOptions . |
| [MultiPageOptions(String[] pageTitles)](#MultiPageOptions-java.lang.String---) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  MultiPageOptions . |
| [MultiPageOptions(String[] pageTitles, Rectangle exportArea)](#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  MultiPageOptions . |
| [MultiPageOptions(IntRange[] ranges)](#MultiPageOptions-com.aspose.psd.IntRange---) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  MultiPageOptions . |
| [MultiPageOptions(IntRange[] ranges, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  MultiPageOptions . |
| [MultiPageOptions(IntRange range)](#MultiPageOptions-com.aspose.psd.IntRange-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  MultiPageOptions . |
| [MultiPageOptions(IntRange range, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  MultiPageOptions . |
| [MultiPageOptions(int page)](#MultiPageOptions-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  MultiPageOptions . |
| [MultiPageOptions(int page, Rectangle exportArea)](#MultiPageOptions-int-com.aspose.psd.Rectangle-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  MultiPageOptions . |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExportArea()](#getExportArea--) | Λαμβάνει ή ορίζει την περιοχή εξαγωγής. |
| [getMergeLayers()](#getMergeLayers--) | Λαμβάνει μια τιμή που υποδεικνύει αν [merege layers]. |
| [getMode()](#getMode--) | Λαμβάνει ή ορίζει τη λειτουργία. |
| [getOutputLayersNames()](#getOutputLayersNames--) | Λαμβάνει ή ορίζει τα ονόματα των εξόδων επιπέδων (Λειτουργεί εάν η μορφή εξαγωγής υποστηρίζει ονομασία επιπέδων, για παράδειγμα για Psd) |
| [getPageRasterizationOptions()](#getPageRasterizationOptions--) | Λαμβάνει τις επιλογές rasterization της σελίδας. |
| [getPageTitles()](#getPageTitles--) | Λαμβάνει ή ορίζει τους τίτλους της σελίδας. |
| [getPages()](#getPages--) | Λαμβάνει ή ορίζει τις σελίδες. |
| [getTimeInterval_internalized()](#getTimeInterval-internalized--) | Λαμβάνει το χρονικό διάστημα. |
| [hashCode()](#hashCode--) |  |
| [initPages(IntRange[] ranges)](#initPages-com.aspose.psd.IntRange---) | Αρχικοποιεί τις σελίδες από τον πίνακα περιοχών |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setExportArea(Rectangle value)](#setExportArea-com.aspose.psd.Rectangle-) | Λαμβάνει ή ορίζει την περιοχή εξαγωγής. |
| [setMergeLayers(boolean value)](#setMergeLayers-boolean-) | Ορίζει μια τιμή που υποδεικνύει αν [merege layers]. |
| [setMode(int value)](#setMode-int-) | Λαμβάνει ή ορίζει τη λειτουργία. |
| [setOutputLayersNames(String[] value)](#setOutputLayersNames-java.lang.String---) | Λαμβάνει ή ορίζει τα ονόματα των εξόδων επιπέδων (Λειτουργεί εάν η μορφή εξαγωγής υποστηρίζει ονομασία επιπέδων, για παράδειγμα για Psd) |
| [setPageRasterizationOptions(VectorRasterizationOptions[] value)](#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---) | Ορίζει τις επιλογές rasterization της σελίδας. |
| [setPageTitles(String[] value)](#setPageTitles-java.lang.String---) | Λαμβάνει ή ορίζει τους τίτλους της σελίδας. |
| [setPages(int[] value)](#setPages-int---) | Λαμβάνει ή ορίζει τις σελίδες. |
| [setTimeInterval_internalized(TimeInterval value)](#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-) | Ορίζει το χρονικό διάστημα. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiPageOptions() {#MultiPageOptions--}
```
public MultiPageOptions()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  MultiPageOptions .

### MultiPageOptions(int[] pages) {#MultiPageOptions-int---}
```
public MultiPageOptions(int[] pages)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  MultiPageOptions .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| σελίδες | int[] | Οι σελίδες. |

### MultiPageOptions(int[] pages, Rectangle exportArea) {#MultiPageOptions-int---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int[] pages, Rectangle exportArea)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  MultiPageOptions .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| σελίδες | int[] | Ο πίνακας των σελίδων. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | Η περιοχή εξαγωγής. |

### MultiPageOptions(String[] pageTitles) {#MultiPageOptions-java.lang.String---}
```
public MultiPageOptions(String[] pageTitles)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  MultiPageOptions .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Οι τίτλοι της σελίδας. |

### MultiPageOptions(String[] pageTitles, Rectangle exportArea) {#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(String[] pageTitles, Rectangle exportArea)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  MultiPageOptions .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Οι τίτλοι της σελίδας. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | Η περιοχή εξαγωγής. |

### MultiPageOptions(IntRange[] ranges) {#MultiPageOptions-com.aspose.psd.IntRange---}
```
public MultiPageOptions(IntRange[] ranges)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  MultiPageOptions .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | Το  IntRange . |

### MultiPageOptions(IntRange[] ranges, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange[] ranges, Rectangle exportArea)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  MultiPageOptions .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | Το  IntRange . |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | Η περιοχή εξαγωγής. |

### MultiPageOptions(IntRange range) {#MultiPageOptions-com.aspose.psd.IntRange-}
```
public MultiPageOptions(IntRange range)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  MultiPageOptions .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | Το  IntRange . |

### MultiPageOptions(IntRange range, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange range, Rectangle exportArea)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  MultiPageOptions .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | Το  IntRange . |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | Η περιοχή εξαγωγής. |

### MultiPageOptions(int page) {#MultiPageOptions-int-}
```
public MultiPageOptions(int page)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  MultiPageOptions .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| σελίδα | int | Ο δείκτης της σελίδας. |

### MultiPageOptions(int page, Rectangle exportArea) {#MultiPageOptions-int-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int page, Rectangle exportArea)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  MultiPageOptions .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| σελίδα | int | Ο δείκτης της σελίδας. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | Η περιοχή εξαγωγής. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExportArea() {#getExportArea--}
```
public Rectangle getExportArea()
```


Λαμβάνει ή ορίζει την περιοχή εξαγωγής.

Τιμή: Η περιοχή εξαγωγής.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getMergeLayers() {#getMergeLayers--}
```
public final boolean getMergeLayers()
```


Λαμβάνει μια τιμή που υποδεικνύει αν [merege layers].

Τιμή:  true  εάν [merege layers]; διαφορετικά,  false .

**Returns:**
boolean - μια τιμή που υποδεικνύει αν [merege layers].
### getMode() {#getMode--}
```
public int getMode()
```


Λαμβάνει ή ορίζει τη λειτουργία.

Τιμή: Η λειτουργία.

**Returns:**
int
### getOutputLayersNames() {#getOutputLayersNames--}
```
public String[] getOutputLayersNames()
```


Λαμβάνει ή ορίζει τα ονόματα των εξόδων επιπέδων (Λειτουργεί εάν η μορφή εξαγωγής υποστηρίζει ονομασία επιπέδων, για παράδειγμα για Psd)

Τιμή: Τα ονόματα των εξόδων επιπέδων.

**Returns:**
java.lang.String[]
### getPageRasterizationOptions() {#getPageRasterizationOptions--}
```
public final VectorRasterizationOptions[] getPageRasterizationOptions()
```


Λαμβάνει τις επιλογές rasterization της σελίδας.

**Returns:**
com.aspose.psd.imageoptions.VectorRasterizationOptions[] - οι επιλογές rasterization της σελίδας.
### getPageTitles() {#getPageTitles--}
```
public String[] getPageTitles()
```


Λαμβάνει ή ορίζει τους τίτλους της σελίδας.

Τιμή: Οι τίτλοι της σελίδας.

**Returns:**
java.lang.String[]
### getPages() {#getPages--}
```
public int[] getPages()
```


Λαμβάνει ή ορίζει τις σελίδες.

Τιμή: Οι σελίδες.

**Returns:**
int[]
### getTimeInterval_internalized() {#getTimeInterval-internalized--}
```
public final TimeInterval getTimeInterval_internalized()
```


Λαμβάνει το χρονικό διάστημα.

Τιμή: Το χρονικό διάστημα.

**Returns:**
[TimeInterval](../../com.aspose.psd.imageoptions/timeinterval) - the time interval.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initPages(IntRange[] ranges) {#initPages-com.aspose.psd.IntRange---}
```
public void initPages(IntRange[] ranges)
```


Αρχικοποιεί τις σελίδες από τον πίνακα περιοχών

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | Τα εύρη. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setExportArea(Rectangle value) {#setExportArea-com.aspose.psd.Rectangle-}
```
public void setExportArea(Rectangle value)
```


Λαμβάνει ή ορίζει την περιοχή εξαγωγής.

Τιμή: Η περιοχή εξαγωγής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setMergeLayers(boolean value) {#setMergeLayers-boolean-}
```
public final void setMergeLayers(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει αν [merege layers].

Τιμή:  true  εάν [merege layers]; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | μια τιμή που υποδεικνύει εάν [merege layers]. |

### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Λαμβάνει ή ορίζει τη λειτουργία.

Τιμή: Η λειτουργία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setOutputLayersNames(String[] value) {#setOutputLayersNames-java.lang.String---}
```
public void setOutputLayersNames(String[] value)
```


Λαμβάνει ή ορίζει τα ονόματα των εξόδων επιπέδων (Λειτουργεί εάν η μορφή εξαγωγής υποστηρίζει ονομασία επιπέδων, για παράδειγμα για Psd)

Τιμή: Τα ονόματα των εξόδων επιπέδων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String[] |  |

### setPageRasterizationOptions(VectorRasterizationOptions[] value) {#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---}
```
public final void setPageRasterizationOptions(VectorRasterizationOptions[] value)
```


Ορίζει τις επιλογές rasterization της σελίδας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [VectorRasterizationOptions\[\]](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) | οι επιλογές rasterization της σελίδας. |

### setPageTitles(String[] value) {#setPageTitles-java.lang.String---}
```
public void setPageTitles(String[] value)
```


Λαμβάνει ή ορίζει τους τίτλους της σελίδας.

Τιμή: Οι τίτλοι της σελίδας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String[] |  |

### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


Λαμβάνει ή ορίζει τις σελίδες.

Τιμή: Οι σελίδες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int[] |  |

### setTimeInterval_internalized(TimeInterval value) {#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-}
```
public final void setTimeInterval_internalized(TimeInterval value)
```


Ορίζει το χρονικό διάστημα.

Τιμή: Το χρονικό διάστημα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TimeInterval](../../com.aspose.psd.imageoptions/timeinterval) | το χρονικό διάστημα. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

