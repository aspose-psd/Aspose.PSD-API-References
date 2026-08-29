---
title: "ITextStyle"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Διεπαφή για εργασία με Text Style"
type: docs
weight: 14
url: /el/java/com.aspose.psd.fileformats.psd.layers.text/itextstyle/
---
```
public interface ITextStyle
```

Διεπαφή για εργασία με Text Style
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [apply(ITextStyle style)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | Εφαρμόζει το καθορισμένο στυλ. |
| [getAutoKerning()](#getAutoKerning--) | Λαμβάνει ή ορίζει το αυτόματο kerning. |
| [getAutoLeading()](#getAutoLeading--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [automatic leading]. |
| [getBaselineShift()](#getBaselineShift--) | Η μετατόπιση της βάσης. |
| [getContextualAlternates()](#getContextualAlternates--) | Οι εναλλακτικές συμφραζόμενων που χρησιμοποιούνται για τη σύνδεση των γραμμάτων μεταξύ τους. |
| [getDiscretionaryLigatures()](#getDiscretionaryLigatures--) | Οι προαιρετικές συνδέσεις γραμμάτων που χρησιμοποιούνται για τη σύνδεση των γραμμάτων, ειδικά σε γραμματοσειρές σκριπτ. |
| [getFauxBold()](#getFauxBold--) | Λαμβάνει ή ορίζει αν η ψεύτικη έντονη γραφή είναι ενεργοποιημένη. |
| [getFauxItalic()](#getFauxItalic--) | Λαμβάνει ή ορίζει αν η ψεύτικη έντονη γραφή είναι ενεργοποιημένη. |
| [getFillColor()](#getFillColor--) | Λαμβάνει ή ορίζει το χρώμα του γεμίσματος. |
| [getFontBaseline()](#getFontBaseline--) | Η γραμμή βάσης της γραμματοσειράς. |
| [getFontCaps()](#getFontCaps--) | Τα κεφαλαία της γραμματοσειράς. |
| [getFontIndex()](#getFontIndex--) | Λαμβάνει τον δείκτη της γραμματοσειράς. |
| [getFontName()](#getFontName--) | Λαμβάνει ή ορίζει το όνομα της γραμματοσειράς. |
| [getFontSize()](#getFontSize--) | Λαμβάνει ή ορίζει το μέγεθος της γραμματοσειράς. |
| [getFractions()](#getFractions--) | Τα σύμβολα κλασμάτων μπορούν να αντικατασταθούν με ειδικό γλύφο. |
| [getHindiNumbers()](#getHindiNumbers--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [hindi numbers]. |
| [getHorizontalScale()](#getHorizontalScale--) | Η οριζόντια κλίμακα. |
| [getKerning()](#getKerning--) | Λαμβάνει ή ορίζει το διαχωρισμό χαρακτήρων. |
| [getLanguageIndex()](#getLanguageIndex--) | Λαμβάνει τον δείκτη της γλώσσας. |
| [getLeading()](#getLeading--) | Λαμβάνει ή ορίζει το leading. |
| [getStandardLigatures()](#getStandardLigatures--) | Οι τυπικές εναλλακτικές συμφραζόμενων που χρησιμοποιούνται για τη σύνδεση των γραμμάτων μεταξύ τους. |
| [getStrikethrough()](#getStrikethrough--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [strikethrough]. |
| [getStrokeColor()](#getStrokeColor--) | Λαμβάνει ή ορίζει το χρώμα του περιγράμματος. |
| [getTracking()](#getTracking--) | Λαμβάνει ή ορίζει την παρακολούθηση. |
| [getUnderline()](#getUnderline--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [underline]. |
| [getVerticalScale()](#getVerticalScale--) | Η κάθετη κλίμακα. |
| [get_noBreak()](#get-noBreak--) | Λαμβάνει ot ορίζει την τιμή χωρίς διάσπαση. |
| [isEqual(ITextStyle style)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | Καθορίζει αν το καθορισμένο στυλ είναι ίσο. |
| [is_isStandardVerticalRomanAlignmentEnabled()](#is-isStandardVerticalRomanAlignmentEnabled--) | Λαμβάνει ή ορίζει την τυπική κάθετη Ρωμαϊκή στοίχιση. |
| [setAutoKerning(int value)](#setAutoKerning-int-) | Λαμβάνει ή ορίζει το αυτόματο kerning. |
| [setAutoLeading(boolean value)](#setAutoLeading-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [automatic leading]. |
| [setBaselineShift(double value)](#setBaselineShift-double-) | Η μετατόπιση της βάσης. |
| [setContextualAlternates(boolean value)](#setContextualAlternates-boolean-) | Οι εναλλακτικές συμφραζόμενων που χρησιμοποιούνται για τη σύνδεση των γραμμάτων μεταξύ τους. |
| [setDiscretionaryLigatures(boolean value)](#setDiscretionaryLigatures-boolean-) | Οι προαιρετικές συνδέσεις γραμμάτων που χρησιμοποιούνται για τη σύνδεση των γραμμάτων, ειδικά σε γραμματοσειρές σκριπτ. |
| [setFauxBold(boolean value)](#setFauxBold-boolean-) | Λαμβάνει ή ορίζει αν η ψεύτικη έντονη γραφή είναι ενεργοποιημένη. |
| [setFauxItalic(boolean value)](#setFauxItalic-boolean-) | Λαμβάνει ή ορίζει αν η ψεύτικη έντονη γραφή είναι ενεργοποιημένη. |
| [setFillColor(Color value)](#setFillColor-com.aspose.psd.Color-) | Λαμβάνει ή ορίζει το χρώμα του γεμίσματος. |
| [setFontBaseline(int value)](#setFontBaseline-int-) | Η γραμμή βάσης της γραμματοσειράς. |
| [setFontCaps(int value)](#setFontCaps-int-) | Τα κεφαλαία της γραμματοσειράς. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα της γραμματοσειράς. |
| [setFontSize(double value)](#setFontSize-double-) | Λαμβάνει ή ορίζει το μέγεθος της γραμματοσειράς. |
| [setFractions(boolean value)](#setFractions-boolean-) | Τα σύμβολα κλασμάτων μπορούν να αντικατασταθούν με ειδικό γλύφο. |
| [setHindiNumbers(boolean value)](#setHindiNumbers-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [hindi numbers]. |
| [setHorizontalScale(double value)](#setHorizontalScale-double-) | Η οριζόντια κλίμακα. |
| [setKerning(int value)](#setKerning-int-) | Λαμβάνει ή ορίζει το διαχωρισμό χαρακτήρων. |
| [setLeading(double value)](#setLeading-double-) | Λαμβάνει ή ορίζει το leading. |
| [setStandardLigatures(boolean value)](#setStandardLigatures-boolean-) | Οι τυπικές εναλλακτικές συμφραζόμενων που χρησιμοποιούνται για τη σύνδεση των γραμμάτων μεταξύ τους. |
| [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [strikethrough]. |
| [setStrokeColor(Color value)](#setStrokeColor-com.aspose.psd.Color-) | Λαμβάνει ή ορίζει το χρώμα του περιγράμματος. |
| [setTracking(int value)](#setTracking-int-) | Λαμβάνει ή ορίζει την παρακολούθηση. |
| [setUnderline(boolean value)](#setUnderline-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [underline]. |
| [setVerticalScale(double value)](#setVerticalScale-double-) | Η κάθετη κλίμακα. |
| [set_isStandardVerticalRomanAlignmentEnabled(boolean value)](#set-isStandardVerticalRomanAlignmentEnabled-boolean-) | Λαμβάνει ή ορίζει την τυπική κάθετη Ρωμαϊκή στοίχιση. |
| [set_noBreak(boolean value)](#set-noBreak-boolean-) | Λαμβάνει ot ορίζει την τιμή χωρίς διάσπαση. |
### apply(ITextStyle style) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract void apply(ITextStyle style)
```


Εφαρμόζει το καθορισμένο στυλ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | Το στυλ. |

### getAutoKerning() {#getAutoKerning--}
```
public abstract int getAutoKerning()
```


Λαμβάνει ή ορίζει το αυτόματο kerning.

Τιμή: Η αυτόματη kerning μεταξύ δύο χαρακτήρων.

**Returns:**
int
### getAutoLeading() {#getAutoLeading--}
```
public abstract boolean getAutoLeading()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [automatic leading].

Τιμή: true εάν [automatic leading]; διαφορετικά, false.

**Returns:**
boolean
### getBaselineShift() {#getBaselineShift--}
```
public abstract double getBaselineShift()
```


Η μετατόπιση της βάσης.

**Returns:**
double
### getContextualAlternates() {#getContextualAlternates--}
```
public abstract boolean getContextualAlternates()
```


Οι εναλλακτικές συμφραζόμενων που χρησιμοποιούνται για τη σύνδεση των γραμμάτων μεταξύ τους.

**Returns:**
boolean
### getDiscretionaryLigatures() {#getDiscretionaryLigatures--}
```
public abstract boolean getDiscretionaryLigatures()
```


Οι προαιρετικές συνδέσεις γραμμάτων που χρησιμοποιούνται για τη σύνδεση των γραμμάτων, ειδικά σε γραμματοσειρές σκριπτ.

**Returns:**
boolean
### getFauxBold() {#getFauxBold--}
```
public abstract boolean getFauxBold()
```


Λαμβάνει ή ορίζει αν η ψεύτικη έντονη γραφή είναι ενεργοποιημένη.

**Returns:**
boolean
### getFauxItalic() {#getFauxItalic--}
```
public abstract boolean getFauxItalic()
```


Λαμβάνει ή ορίζει αν η ψεύτικη έντονη γραφή είναι ενεργοποιημένη.

**Returns:**
boolean
### getFillColor() {#getFillColor--}
```
public abstract Color getFillColor()
```


Λαμβάνει ή ορίζει το χρώμα του γεμίσματος.

Τιμή: Το χρώμα του γεμίσματος.

**Returns:**
[Color](../../com.aspose.psd/color)
### getFontBaseline() {#getFontBaseline--}
```
public abstract int getFontBaseline()
```


Η γραμμή βάσης της γραμματοσειράς.

**Returns:**
int
### getFontCaps() {#getFontCaps--}
```
public abstract int getFontCaps()
```


Τα κεφαλαία της γραμματοσειράς.

**Returns:**
int
### getFontIndex() {#getFontIndex--}
```
public abstract int getFontIndex()
```


Λαμβάνει τον δείκτη της γραμματοσειράς.

Τιμή: Η γραμματοσειρά.

**Returns:**
int
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Λαμβάνει ή ορίζει το όνομα της γραμματοσειράς.

**Returns:**
java.lang.String
### getFontSize() {#getFontSize--}
```
public abstract double getFontSize()
```


Λαμβάνει ή ορίζει το μέγεθος της γραμματοσειράς.

Τιμή: Το μέγεθος της γραμματοσειράς.

**Returns:**
double
### getFractions() {#getFractions--}
```
public abstract boolean getFractions()
```


Τα σύμβολα κλασμάτων μπορούν να αντικατασταθούν με ειδικό γλύφο.

**Returns:**
boolean
### getHindiNumbers() {#getHindiNumbers--}
```
public abstract boolean getHindiNumbers()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [hindi numbers].

Τιμή: true εάν [hindi numbers]; διαφορετικά, false.

**Returns:**
boolean
### getHorizontalScale() {#getHorizontalScale--}
```
public abstract double getHorizontalScale()
```


Η οριζόντια κλίμακα.

**Returns:**
double
### getKerning() {#getKerning--}
```
public abstract int getKerning()
```


Λαμβάνει ή ορίζει το διαχωρισμό χαρακτήρων.

Τιμή: Η kerning μεταξύ δύο χαρακτήρων.

**Returns:**
int
### getLanguageIndex() {#getLanguageIndex--}
```
public abstract int getLanguageIndex()
```


Λαμβάνει τον δείκτη της γλώσσας.

**Returns:**
int
### getLeading() {#getLeading--}
```
public abstract double getLeading()
```


Λαμβάνει ή ορίζει το leading.

Τιμή: Το leading.

**Returns:**
double
### getStandardLigatures() {#getStandardLigatures--}
```
public abstract boolean getStandardLigatures()
```


Οι τυπικές εναλλακτικές συμφραζόμενων που χρησιμοποιούνται για τη σύνδεση των γραμμάτων μεταξύ τους.

**Returns:**
boolean
### getStrikethrough() {#getStrikethrough--}
```
public abstract boolean getStrikethrough()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [strikethrough].

**Returns:**
boolean
### getStrokeColor() {#getStrokeColor--}
```
public abstract Color getStrokeColor()
```


Λαμβάνει ή ορίζει το χρώμα του περιγράμματος.

Τιμή: Το χρώμα του περιγράμματος.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTracking() {#getTracking--}
```
public abstract int getTracking()
```


Λαμβάνει ή ορίζει την παρακολούθηση.

Τιμή: Το tracking.

**Returns:**
int
### getUnderline() {#getUnderline--}
```
public abstract boolean getUnderline()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [underline].

**Returns:**
boolean
### getVerticalScale() {#getVerticalScale--}
```
public abstract double getVerticalScale()
```


Η κάθετη κλίμακα.

**Returns:**
double
### get_noBreak() {#get-noBreak--}
```
public abstract boolean get_noBreak()
```


Λαμβάνει ot ορίζει την τιμή χωρίς διάσπαση.

**Returns:**
boolean
### isEqual(ITextStyle style) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract boolean isEqual(ITextStyle style)
```


Καθορίζει αν το καθορισμένο στυλ είναι ίσο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | Το στυλ. |

**Returns:**
boolean - true εάν το καθορισμένο στυλ είναι ίσο; διαφορετικά, false.
### is_isStandardVerticalRomanAlignmentEnabled() {#is-isStandardVerticalRomanAlignmentEnabled--}
```
public abstract boolean is_isStandardVerticalRomanAlignmentEnabled()
```


Λαμβάνει ή ορίζει την τυπική κατακόρυφη Ρωμαϊκή στοίχιση. Αυτό, βασισμένο στην τιμή πόρου BaselineDirection, εφαρμόζεται μόνο όταν ο προσανατολισμός κειμένου είναι [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical).

**Returns:**
boolean
### setAutoKerning(int value) {#setAutoKerning-int-}
```
public abstract void setAutoKerning(int value)
```


Λαμβάνει ή ορίζει το αυτόματο kerning.

Τιμή: Η αυτόματη kerning μεταξύ δύο χαρακτήρων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setAutoLeading(boolean value) {#setAutoLeading-boolean-}
```
public abstract void setAutoLeading(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [automatic leading].

Τιμή: true εάν [automatic leading]; διαφορετικά, false.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setBaselineShift(double value) {#setBaselineShift-double-}
```
public abstract void setBaselineShift(double value)
```


Η μετατόπιση της βάσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setContextualAlternates(boolean value) {#setContextualAlternates-boolean-}
```
public abstract void setContextualAlternates(boolean value)
```


Οι εναλλακτικές συμφραζόμενων που χρησιμοποιούνται για τη σύνδεση των γραμμάτων μεταξύ τους.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setDiscretionaryLigatures(boolean value) {#setDiscretionaryLigatures-boolean-}
```
public abstract void setDiscretionaryLigatures(boolean value)
```


Οι προαιρετικές συνδέσεις γραμμάτων που χρησιμοποιούνται για τη σύνδεση των γραμμάτων, ειδικά σε γραμματοσειρές σκριπτ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setFauxBold(boolean value) {#setFauxBold-boolean-}
```
public abstract void setFauxBold(boolean value)
```


Λαμβάνει ή ορίζει αν η ψεύτικη έντονη γραφή είναι ενεργοποιημένη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setFauxItalic(boolean value) {#setFauxItalic-boolean-}
```
public abstract void setFauxItalic(boolean value)
```


Λαμβάνει ή ορίζει αν η ψεύτικη έντονη γραφή είναι ενεργοποιημένη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setFillColor(Color value) {#setFillColor-com.aspose.psd.Color-}
```
public abstract void setFillColor(Color value)
```


Λαμβάνει ή ορίζει το χρώμα του γεμίσματος.

Τιμή: Το χρώμα του γεμίσματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setFontBaseline(int value) {#setFontBaseline-int-}
```
public abstract void setFontBaseline(int value)
```


Η γραμμή βάσης της γραμματοσειράς.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setFontCaps(int value) {#setFontCaps-int-}
```
public abstract void setFontCaps(int value)
```


Τα κεφαλαία της γραμματοσειράς.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public abstract void setFontName(String value)
```


Λαμβάνει ή ορίζει το όνομα της γραμματοσειράς.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setFontSize(double value) {#setFontSize-double-}
```
public abstract void setFontSize(double value)
```


Λαμβάνει ή ορίζει το μέγεθος της γραμματοσειράς.

Τιμή: Το μέγεθος της γραμματοσειράς.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setFractions(boolean value) {#setFractions-boolean-}
```
public abstract void setFractions(boolean value)
```


Τα σύμβολα κλασμάτων μπορούν να αντικατασταθούν με ειδικό γλύφο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setHindiNumbers(boolean value) {#setHindiNumbers-boolean-}
```
public abstract void setHindiNumbers(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [hindi numbers].

Τιμή: true εάν [hindi numbers]; διαφορετικά, false.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setHorizontalScale(double value) {#setHorizontalScale-double-}
```
public abstract void setHorizontalScale(double value)
```


Η οριζόντια κλίμακα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setKerning(int value) {#setKerning-int-}
```
public abstract void setKerning(int value)
```


Λαμβάνει ή ορίζει το διαχωρισμό χαρακτήρων.

Τιμή: Η kerning μεταξύ δύο χαρακτήρων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setLeading(double value) {#setLeading-double-}
```
public abstract void setLeading(double value)
```


Λαμβάνει ή ορίζει το leading.

Τιμή: Το leading.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setStandardLigatures(boolean value) {#setStandardLigatures-boolean-}
```
public abstract void setStandardLigatures(boolean value)
```


Οι τυπικές εναλλακτικές συμφραζόμενων που χρησιμοποιούνται για τη σύνδεση των γραμμάτων μεταξύ τους.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public abstract void setStrikethrough(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [strikethrough].

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setStrokeColor(Color value) {#setStrokeColor-com.aspose.psd.Color-}
```
public abstract void setStrokeColor(Color value)
```


Λαμβάνει ή ορίζει το χρώμα του περιγράμματος.

Τιμή: Το χρώμα του περιγράμματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setTracking(int value) {#setTracking-int-}
```
public abstract void setTracking(int value)
```


Λαμβάνει ή ορίζει την παρακολούθηση.

Τιμή: Το tracking.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public abstract void setUnderline(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [underline].

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setVerticalScale(double value) {#setVerticalScale-double-}
```
public abstract void setVerticalScale(double value)
```


Η κάθετη κλίμακα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### set_isStandardVerticalRomanAlignmentEnabled(boolean value) {#set-isStandardVerticalRomanAlignmentEnabled-boolean-}
```
public abstract void set_isStandardVerticalRomanAlignmentEnabled(boolean value)
```


Λαμβάνει ή ορίζει την τυπική κατακόρυφη Ρωμαϊκή στοίχιση. Αυτό, βασισμένο στην τιμή πόρου BaselineDirection, εφαρμόζεται μόνο όταν ο προσανατολισμός κειμένου είναι [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### set_noBreak(boolean value) {#set-noBreak-boolean-}
```
public abstract void set_noBreak(boolean value)
```


Λαμβάνει ot ορίζει την τιμή χωρίς διάσπαση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

