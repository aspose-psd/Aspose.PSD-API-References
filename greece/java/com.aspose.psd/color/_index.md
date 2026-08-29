---
title: "Χρώμα"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Το χρώμα του pixel."
type: docs
weight: 19
url: /el/java/com.aspose.psd/color/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Color extends Struct<Color>
```

Το χρώμα του pixel.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Color()](#Color--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Color that)](#CloneTo-com.aspose.psd.Color-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Δοκιμάζει εάν το καθορισμένο αντικείμενο είναι μια  com.aspose.psd.Color  δομή και είναι ισοδύναμη με αυτή τη  com.aspose.psd.Color  δομή. |
| [fromArgb(byte red, byte green, byte blue)](#fromArgb-byte-byte-byte-) | Δημιουργεί μια  com.aspose.psd.Color  δομή από τις καθορισμένες 8-bit τιμές χρώματος (κόκκινο, πράσινο και μπλε). |
| [fromArgb(byte alpha, byte red, byte green, byte blue)](#fromArgb-byte-byte-byte-byte-) | Δημιουργεί μια  com.aspose.psd.Color  δομή από τις τέσσερις τιμές των συστατικών ARGB (άλφα, κόκκινο, πράσινο και μπλε). |
| [fromArgb(int argb)](#fromArgb-int-) | Δημιουργεί μια  com.aspose.psd.Color  δομή από μια τιμή ARGB 32-bit. |
| [fromArgb(int alpha, Color baseColor)](#fromArgb-int-com.aspose.psd.Color-) | Δημιουργεί μια  com.aspose.psd.Color  δομή από την καθορισμένη  com.aspose.psd.Color  δομή, αλλά με τη νέα καθορισμένη τιμή άλφα. |
| [fromArgb(int red, int green, int blue)](#fromArgb-int-int-int-) | Δημιουργεί μια  com.aspose.psd.Color  δομή από τις καθορισμένες 8-bit τιμές χρώματος (κόκκινο, πράσινο και μπλε). |
| [fromArgb(int alpha, int red, int green, int blue)](#fromArgb-int-int-int-int-) | Δημιουργεί μια  com.aspose.psd.Color  δομή από τις τέσσερις τιμές των συστατικών ARGB (άλφα, κόκκινο, πράσινο και μπλε). |
| [fromKnownColor(int color)](#fromKnownColor-int-) | Δημιουργεί μια  com.aspose.psd.Color  δομή από το καθορισμένο προεπιλεγμένο χρώμα. |
| [fromName(String name)](#fromName-java.lang.String-) | Δημιουργεί μια  com.aspose.psd.Color  δομή από το καθορισμένο όνομα ενός προεπιλεγμένου χρώματος. |
| [getA()](#getA--) | Αποκτά την τιμή του συστατικού άλφα αυτής της  com.aspose.psd.Color  δομής. |
| [getAliceBlue()](#getAliceBlue--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getAntiqueWhite()](#getAntiqueWhite--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getAqua()](#getAqua--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getAquamarine()](#getAquamarine--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getAzure()](#getAzure--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getB()](#getB--) | Αποκτά την τιμή του μπλε συστατικού αυτής της  com.aspose.psd.Color  δομής. |
| [getBeige()](#getBeige--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getBisque()](#getBisque--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getBlack()](#getBlack--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getBlanchedAlmond()](#getBlanchedAlmond--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getBlue()](#getBlue--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getBlueViolet()](#getBlueViolet--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getBrightness()](#getBrightness--) | Αποκτά την τιμή φωτεινότητας hue-saturation-brightness (HSB) για αυτή τη  com.aspose.psd.Color  δομή. |
| [getBrown()](#getBrown--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getBurlyWood()](#getBurlyWood--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getCadetBlue()](#getCadetBlue--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getChartreuse()](#getChartreuse--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getChocolate()](#getChocolate--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getClass()](#getClass--) |  |
| [getCoral()](#getCoral--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getCornflowerBlue()](#getCornflowerBlue--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getCornsilk()](#getCornsilk--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getCrimson()](#getCrimson--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getCyan()](#getCyan--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkBlue()](#getDarkBlue--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkCyan()](#getDarkCyan--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkGoldenrod()](#getDarkGoldenrod--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkGray()](#getDarkGray--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkGreen()](#getDarkGreen--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkKhaki()](#getDarkKhaki--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkMagenta()](#getDarkMagenta--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkOliveGreen()](#getDarkOliveGreen--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkOrange()](#getDarkOrange--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkOrchid()](#getDarkOrchid--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkRed()](#getDarkRed--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkSalmon()](#getDarkSalmon--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkSeaGreen()](#getDarkSeaGreen--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkSlateBlue()](#getDarkSlateBlue--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkSlateGray()](#getDarkSlateGray--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkTurquoise()](#getDarkTurquoise--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getDarkViolet()](#getDarkViolet--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getDeepPink()](#getDeepPink--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getDeepSkyBlue()](#getDeepSkyBlue--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getDimGray()](#getDimGray--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getDodgerBlue()](#getDodgerBlue--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getEmpty()](#getEmpty--) | Αποκτά ένα κενό  Color . |
| [getFirebrick()](#getFirebrick--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getFloralWhite()](#getFloralWhite--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getForestGreen()](#getForestGreen--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getFuchsia()](#getFuchsia--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getG()](#getG--) | Αποκτά την τιμή του πράσινου συστατικού αυτής της  com.aspose.psd.Color  δομής. |
| [getGainsboro()](#getGainsboro--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getGhostWhite()](#getGhostWhite--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getGold()](#getGold--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getGoldenrod()](#getGoldenrod--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getGray()](#getGray--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getGreen()](#getGreen--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getGreenYellow()](#getGreenYellow--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getHoneydew()](#getHoneydew--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getHotPink()](#getHotPink--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getHue()](#getHue--) | Αποκτά την τιμή απόχρωσης hue-saturation-brightness (HSB), σε μοίρες, για αυτή τη  com.aspose.psd.Color  δομή. |
| [getIndianRed()](#getIndianRed--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getIndigo()](#getIndigo--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getIvory()](#getIvory--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getKhaki()](#getKhaki--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getLavender()](#getLavender--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getLavenderBlush()](#getLavenderBlush--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getLawnGreen()](#getLawnGreen--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getLemonChiffon()](#getLemonChiffon--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightBlue()](#getLightBlue--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightCoral()](#getLightCoral--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightCyan()](#getLightCyan--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightGoldenrodYellow()](#getLightGoldenrodYellow--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightGray()](#getLightGray--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightGreen()](#getLightGreen--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightPink()](#getLightPink--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightSalmon()](#getLightSalmon--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightSeaGreen()](#getLightSeaGreen--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightSkyBlue()](#getLightSkyBlue--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightSlateGray()](#getLightSlateGray--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightSteelBlue()](#getLightSteelBlue--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getLightYellow()](#getLightYellow--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getLime()](#getLime--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getLimeGreen()](#getLimeGreen--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getLinen()](#getLinen--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getMagenta()](#getMagenta--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getMaroon()](#getMaroon--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getMediumAquamarine()](#getMediumAquamarine--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getMediumBlue()](#getMediumBlue--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getMediumOrchid()](#getMediumOrchid--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getMediumPurple()](#getMediumPurple--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getMediumSeaGreen()](#getMediumSeaGreen--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getMediumSlateBlue()](#getMediumSlateBlue--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getMediumSpringGreen()](#getMediumSpringGreen--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getMediumTurquoise()](#getMediumTurquoise--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getMediumVioletRed()](#getMediumVioletRed--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getMidnightBlue()](#getMidnightBlue--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getMintCream()](#getMintCream--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getMistyRose()](#getMistyRose--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getMoccasin()](#getMoccasin--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getName()](#getName--) | Αποκτά το όνομα αυτής της  com.aspose.psd.Color . |
| [getNavajoWhite()](#getNavajoWhite--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getNavy()](#getNavy--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getOldLace()](#getOldLace--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getOlive()](#getOlive--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getOliveDrab()](#getOliveDrab--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getOrange()](#getOrange--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getOrangeRed()](#getOrangeRed--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getOrchid()](#getOrchid--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getPaleGoldenrod()](#getPaleGoldenrod--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getPaleGreen()](#getPaleGreen--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getPaleTurquoise()](#getPaleTurquoise--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getPaleVioletRed()](#getPaleVioletRed--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getPapayaWhip()](#getPapayaWhip--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getPeachPuff()](#getPeachPuff--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getPeru()](#getPeru--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getPink()](#getPink--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getPlum()](#getPlum--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getPowderBlue()](#getPowderBlue--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getPurple()](#getPurple--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getR()](#getR--) | Αποκτά την τιμή του κόκκινου συστατικού αυτής της  com.aspose.psd.Color  δομής. |
| [getRed()](#getRed--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getRosyBrown()](#getRosyBrown--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getRoyalBlue()](#getRoyalBlue--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getSaddleBrown()](#getSaddleBrown--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getSalmon()](#getSalmon--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getSandyBrown()](#getSandyBrown--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getSaturation()](#getSaturation--) | Αποκτά την τιμή κορεσμού hue-saturation-brightness (HSB) για αυτή τη  com.aspose.psd.Color  δομή. |
| [getSeaGreen()](#getSeaGreen--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getSeaShell()](#getSeaShell--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getSienna()](#getSienna--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getSilver()](#getSilver--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getSkyBlue()](#getSkyBlue--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getSlateBlue()](#getSlateBlue--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getSlateGray()](#getSlateGray--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getSnow()](#getSnow--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getSpringGreen()](#getSpringGreen--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getSteelBlue()](#getSteelBlue--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getTan()](#getTan--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getTeal()](#getTeal--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getThistle()](#getThistle--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getTomato()](#getTomato--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getTransparent()](#getTransparent--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getTurquoise()](#getTurquoise--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getViolet()](#getViolet--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getWheat()](#getWheat--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getWhite()](#getWhite--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getWhiteSmoke()](#getWhiteSmoke--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getYellow()](#getYellow--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [getYellowGreen()](#getYellowGreen--) | Αποκτά ένα χρώμα που ορίζεται από το σύστημα. |
| [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού για αυτή τη  com.aspose.psd.Color  δομή. |
| [isEmpty()](#isEmpty--) | Αποκτά μια τιμή που υποδεικνύει εάν αυτή η  com.aspose.psd.Color  δομή δεν έχει αρχικοποιηθεί. |
| [isEquals(Color obj1, Color obj2)](#isEquals-com.aspose.psd.Color-com.aspose.psd.Color-) |  |
| [isKnownColor()](#isKnownColor--) | Αποκτά μια τιμή που υποδεικνύει εάν αυτή η  com.aspose.psd.Color  δομή είναι προεπιλεγμένο χρώμα. |
| [isNamedColor()](#isNamedColor--) | Αποκτά μια τιμή που υποδεικνύει εάν αυτή η  com.aspose.psd.Color  δομή είναι ένα ονομαστικό χρώμα ή μέλος της  Aspose.Imaging.KnownColor  απαρίθμησης. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(Color left, Color right)](#op-Equality-com.aspose.psd.Color-com.aspose.psd.Color-) | Δοκιμάζει εάν δύο καθορισμένες  com.aspose.psd.Color  δομές είναι ισοδύναμες. |
| [op_Inequality(Color left, Color right)](#op-Inequality-com.aspose.psd.Color-com.aspose.psd.Color-) | Δοκιμάζει εάν δύο καθορισμένες  com.aspose.psd.Color  δομές είναι διαφορετικές. |
| [toArgb()](#toArgb--) | Αποκτά την τιμή ARGB 32-bit αυτής της  com.aspose.psd.Color  δομής. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | Η μετατροπή από Color σε CmykColor. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | Η μετατροπή από Color σε CMYKColor. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | Η μετατροπή από Color σε CMYKColor χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | Η μετατροπή από Color σε CMYKColor χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | Η μετατροπή από Color σε CMYKColor χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | Η μετατροπή από Color σε CMYKColor χρησιμοποιώντας μετατροπή icc. |
| [toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIcc-internalized-com.aspose.psd.Color-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toCmykIcc_internalized(Color[] pixels, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIcc-internalized-com.aspose.psd.Color---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toKnownColor()](#toKnownColor--) | Λαμβάνει την τιμή  Aspose.Imaging.KnownColor  του αυτού του δομικού τύπου  com.aspose.psd.Color . |
| [toString()](#toString--) | Μετατρέπει αυτό το δομικό τύπο  com.aspose.psd.Color  σε μια αναγνώσιμη από άνθρωπο συμβολοσειρά. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Color() {#Color--}
```
public Color()
```


### Clone() {#Clone--}
```
public Color Clone()
```




**Returns:**
[Color](../../com.aspose.psd/color)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Color that) {#CloneTo-com.aspose.psd.Color-}
```
public void CloneTo(Color that)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| that | [Color](../../com.aspose.psd/color) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Δοκιμάζει εάν το καθορισμένο αντικείμενο είναι μια  com.aspose.psd.Color  δομή και είναι ισοδύναμη με αυτή τη  com.aspose.psd.Color  δομή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το αντικείμενο για δοκιμή. |

**Returns:**
boolean - True εάν  obj  είναι ένα δομικό τύπο  com.aspose.psd.Color  ισοδύναμο με αυτό το δομικό τύπο  com.aspose.psd.Color ; διαφορετικά, false.
### fromArgb(byte red, byte green, byte blue) {#fromArgb-byte-byte-byte-}
```
public static Color fromArgb(byte red, byte green, byte blue)
```


Δημιουργεί ένα δομικό τύπο  com.aspose.psd.Color  από τις καθορισμένες τιμές χρώματος 8-bit (κόκκινο, πράσινο και μπλε). Η τιμή alpha είναι έμμεσα 255 (πλήρως αδιαφανής). Αν και αυτή η μέθοδος επιτρέπει τη μεταβίβαση μιας τιμής 32-bit για κάθε συνιστώσα χρώματος, η τιμή κάθε συνιστώσας περιορίζεται στα 8 bits.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κόκκινο | byte | Η τιμή της κόκκινης συνιστώσας για το νέο  com.aspose.psd.Color . Οι έγκυρες τιμές είναι από 0 έως 255. |
| πράσινο | byte | Η τιμή της πράσινης συνιστώσας για το νέο  com.aspose.psd.Color . Οι έγκυρες τιμές είναι από 0 έως 255. |
| μπλε | byte | Η τιμή της μπλε συνιστώσας για το νέο  com.aspose.psd.Color . Οι έγκυρες τιμές είναι από 0 έως 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(byte alpha, byte red, byte green, byte blue) {#fromArgb-byte-byte-byte-byte-}
```
public static Color fromArgb(byte alpha, byte red, byte green, byte blue)
```


Δημιουργεί ένα δομικό τύπο  com.aspose.psd.Color  από τις τέσσερις τιμές συνιστωσών ARGB (alpha, κόκκινο, πράσινο και μπλε). Αν και αυτή η μέθοδος επιτρέπει τη μεταβίβαση μιας τιμής 32-bit για κάθε συνιστώσα, η τιμή κάθε συνιστώσας περιορίζεται στα 8 bits.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alpha | byte | Η συνιστώσα alpha. Οι έγκυρες τιμές είναι από 0 έως 255. |
| κόκκινο | byte | Η κόκκινη συνιστώσα. Οι έγκυρες τιμές είναι από 0 έως 255. |
| πράσινο | byte | Η πράσινη συνιστώσα. Οι έγκυρες τιμές είναι από 0 έως 255. |
| μπλε | byte | Η μπλε συνιστώσα. Οι έγκυρες τιμές είναι από 0 έως 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int argb) {#fromArgb-int-}
```
public static Color fromArgb(int argb)
```


Δημιουργεί μια  com.aspose.psd.Color  δομή από μια τιμή ARGB 32-bit.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| argb | int | Μια τιμή που καθορίζει την τιμή ARGB 32-bit. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  structure that this method creates.
### fromArgb(int alpha, Color baseColor) {#fromArgb-int-com.aspose.psd.Color-}
```
public static Color fromArgb(int alpha, Color baseColor)
```


Δημιουργεί ένα δομικό τύπο  com.aspose.psd.Color  από το καθορισμένο δομικό τύπο  com.aspose.psd.Color , αλλά με τη νέα καθορισμένη τιμή alpha. Αν και αυτή η μέθοδος επιτρέπει τη μεταβίβαση μιας τιμής 32-bit για την τιμή alpha, η τιμή περιορίζεται στα 8 bits.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alpha | int | Η τιμή alpha για το νέο  com.aspose.psd.Color . Οι έγκυρες τιμές είναι από 0 έως 255. |
| baseColor | [Color](../../com.aspose.psd/color) | Το  com.aspose.psd.Color  από το οποίο θα δημιουργηθεί το νέο  com.aspose.psd.Color . |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int red, int green, int blue) {#fromArgb-int-int-int-}
```
public static Color fromArgb(int red, int green, int blue)
```


Δημιουργεί ένα δομικό τύπο  com.aspose.psd.Color  από τις καθορισμένες τιμές χρώματος 8-bit (κόκκινο, πράσινο και μπλε). Η τιμή alpha είναι έμμεσα 255 (πλήρως αδιαφανής). Αν και αυτή η μέθοδος επιτρέπει τη μεταβίβαση μιας τιμής 32-bit για κάθε συνιστώσα χρώματος, η τιμή κάθε συνιστώσας περιορίζεται στα 8 bits.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κόκκινο | int | Η τιμή της κόκκινης συνιστώσας για το νέο  com.aspose.psd.Color . Οι έγκυρες τιμές είναι από 0 έως 255. |
| πράσινο | int | Η τιμή της πράσινης συνιστώσας για το νέο  com.aspose.psd.Color . Οι έγκυρες τιμές είναι από 0 έως 255. |
| μπλε | int | Η τιμή της μπλε συνιστώσας για το νέο  com.aspose.psd.Color . Οι έγκυρες τιμές είναι από 0 έως 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int alpha, int red, int green, int blue) {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int alpha, int red, int green, int blue)
```


Δημιουργεί ένα δομικό τύπο  com.aspose.psd.Color  από τις τέσσερις τιμές συνιστωσών ARGB (alpha, κόκκινο, πράσινο και μπλε). Αν και αυτή η μέθοδος επιτρέπει τη μεταβίβαση μιας τιμής 32-bit για κάθε συνιστώσα, η τιμή κάθε συνιστώσας περιορίζεται στα 8 bits.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alpha | int | Η συνιστώσα alpha. Οι έγκυρες τιμές είναι από 0 έως 255. |
| κόκκινο | int | Η κόκκινη συνιστώσα. Οι έγκυρες τιμές είναι από 0 έως 255. |
| πράσινο | int | Η πράσινη συνιστώσα. Οι έγκυρες τιμές είναι από 0 έως 255. |
| μπλε | int | Η μπλε συνιστώσα. Οι έγκυρες τιμές είναι από 0 έως 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromKnownColor(int color) {#fromKnownColor-int-}
```
public static Color fromKnownColor(int color)
```


Δημιουργεί μια  com.aspose.psd.Color  δομή από το καθορισμένο προεπιλεγμένο χρώμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| color | int | Ένα στοιχείο της απαρίθμησης  Aspose.Imaging.KnownColor . |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromName(String name) {#fromName-java.lang.String-}
```
public static Color fromName(String name)
```


Δημιουργεί μια  com.aspose.psd.Color  δομή από το καθορισμένο όνομα ενός προεπιλεγμένου χρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String | Μια συμβολοσειρά που είναι το όνομα ενός προκαθορισμένου χρώματος. Οι έγκυρα ονόματα είναι τα ίδια με τα ονόματα των στοιχείων της απαρίθμησης  Aspose.Imaging.KnownColor . |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### getA() {#getA--}
```
public byte getA()
```


Αποκτά την τιμή του συστατικού άλφα αυτής της  com.aspose.psd.Color  δομής.

**Returns:**
byte - Η τιμή της συνιστώσας alpha αυτού του  com.aspose.psd.Color .
### getAliceBlue() {#getAliceBlue--}
```
public static Color getAliceBlue()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAntiqueWhite() {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAqua() {#getAqua--}
```
public static Color getAqua()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAquamarine() {#getAquamarine--}
```
public static Color getAquamarine()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAzure() {#getAzure--}
```
public static Color getAzure()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getB() {#getB--}
```
public byte getB()
```


Αποκτά την τιμή του μπλε συστατικού αυτής της  com.aspose.psd.Color  δομής.

**Returns:**
byte - Η τιμή της μπλε συνιστώσας αυτού του  com.aspose.psd.Color .
### getBeige() {#getBeige--}
```
public static Color getBeige()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBisque() {#getBisque--}
```
public static Color getBisque()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlack() {#getBlack--}
```
public static Color getBlack()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlanchedAlmond() {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlue() {#getBlue--}
```
public static Color getBlue()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlueViolet() {#getBlueViolet--}
```
public static Color getBlueViolet()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBrightness() {#getBrightness--}
```
public float getBrightness()
```


Αποκτά την τιμή φωτεινότητας hue-saturation-brightness (HSB) για αυτή τη  com.aspose.psd.Color  δομή.

**Returns:**
float - Η φωτεινότητα αυτού του  com.aspose.psd.Color . Η φωτεινότητα κυμαίνεται από 0.0 έως 1.0, όπου το 0.0 αντιπροσωπεύει το μαύρο και το 1.0 το λευκό.
### getBrown() {#getBrown--}
```
public static Color getBrown()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBurlyWood() {#getBurlyWood--}
```
public static Color getBurlyWood()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCadetBlue() {#getCadetBlue--}
```
public static Color getCadetBlue()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getChartreuse() {#getChartreuse--}
```
public static Color getChartreuse()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getChocolate() {#getChocolate--}
```
public static Color getChocolate()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCoral() {#getCoral--}
```
public static Color getCoral()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCornflowerBlue() {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCornsilk() {#getCornsilk--}
```
public static Color getCornsilk()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCrimson() {#getCrimson--}
```
public static Color getCrimson()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCyan() {#getCyan--}
```
public static Color getCyan()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkBlue() {#getDarkBlue--}
```
public static Color getDarkBlue()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkCyan() {#getDarkCyan--}
```
public static Color getDarkCyan()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGoldenrod() {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGray() {#getDarkGray--}
```
public static Color getDarkGray()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGreen() {#getDarkGreen--}
```
public static Color getDarkGreen()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkKhaki() {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkMagenta() {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOliveGreen() {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOrange() {#getDarkOrange--}
```
public static Color getDarkOrange()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOrchid() {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkRed() {#getDarkRed--}
```
public static Color getDarkRed()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSalmon() {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSeaGreen() {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSlateBlue() {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSlateGray() {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkTurquoise() {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkViolet() {#getDarkViolet--}
```
public static Color getDarkViolet()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDeepPink() {#getDeepPink--}
```
public static Color getDeepPink()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDeepSkyBlue() {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDimGray() {#getDimGray--}
```
public static Color getDimGray()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDodgerBlue() {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getEmpty() {#getEmpty--}
```
public static Color getEmpty()
```


Αποκτά ένα κενό  Color .

**Returns:**
[Color](../../com.aspose.psd/color) - The empty  Color .
### getFirebrick() {#getFirebrick--}
```
public static Color getFirebrick()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getFloralWhite() {#getFloralWhite--}
```
public static Color getFloralWhite()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getForestGreen() {#getForestGreen--}
```
public static Color getForestGreen()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getFuchsia() {#getFuchsia--}
```
public static Color getFuchsia()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getG() {#getG--}
```
public byte getG()
```


Αποκτά την τιμή του πράσινου συστατικού αυτής της  com.aspose.psd.Color  δομής.

**Returns:**
byte - Η τιμή του πράσινου συστατικού αυτού του  com.aspose.psd.Color .
### getGainsboro() {#getGainsboro--}
```
public static Color getGainsboro()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGhostWhite() {#getGhostWhite--}
```
public static Color getGhostWhite()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGold() {#getGold--}
```
public static Color getGold()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGoldenrod() {#getGoldenrod--}
```
public static Color getGoldenrod()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGray() {#getGray--}
```
public static Color getGray()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  structure representing a system-defined color.
### getGreen() {#getGreen--}
```
public static Color getGreen()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGreenYellow() {#getGreenYellow--}
```
public static Color getGreenYellow()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHoneydew() {#getHoneydew--}
```
public static Color getHoneydew()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHotPink() {#getHotPink--}
```
public static Color getHotPink()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHue() {#getHue--}
```
public float getHue()
```


Αποκτά την τιμή απόχρωσης hue-saturation-brightness (HSB), σε μοίρες, για αυτή τη  com.aspose.psd.Color  δομή.

**Returns:**
float - Η απόχρωση, σε μοίρες, αυτού του  com.aspose.psd.Color . Η απόχρωση μετράται σε μοίρες, κυμαινόμενη από 0.0 έως 360.0, στο χρωματικό χώρο HSB.
### getIndianRed() {#getIndianRed--}
```
public static Color getIndianRed()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getIndigo() {#getIndigo--}
```
public static Color getIndigo()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getIvory() {#getIvory--}
```
public static Color getIvory()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getKhaki() {#getKhaki--}
```
public static Color getKhaki()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLavender() {#getLavender--}
```
public static Color getLavender()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLavenderBlush() {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLawnGreen() {#getLawnGreen--}
```
public static Color getLawnGreen()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLemonChiffon() {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightBlue() {#getLightBlue--}
```
public static Color getLightBlue()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightCoral() {#getLightCoral--}
```
public static Color getLightCoral()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightCyan() {#getLightCyan--}
```
public static Color getLightCyan()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGoldenrodYellow() {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGray() {#getLightGray--}
```
public static Color getLightGray()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGreen() {#getLightGreen--}
```
public static Color getLightGreen()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightPink() {#getLightPink--}
```
public static Color getLightPink()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSalmon() {#getLightSalmon--}
```
public static Color getLightSalmon()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSeaGreen() {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSkyBlue() {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSlateGray() {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSteelBlue() {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightYellow() {#getLightYellow--}
```
public static Color getLightYellow()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLime() {#getLime--}
```
public static Color getLime()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLimeGreen() {#getLimeGreen--}
```
public static Color getLimeGreen()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLinen() {#getLinen--}
```
public static Color getLinen()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMagenta() {#getMagenta--}
```
public static Color getMagenta()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMaroon() {#getMaroon--}
```
public static Color getMaroon()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumAquamarine() {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumBlue() {#getMediumBlue--}
```
public static Color getMediumBlue()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumOrchid() {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumPurple() {#getMediumPurple--}
```
public static Color getMediumPurple()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSeaGreen() {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSlateBlue() {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSpringGreen() {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumTurquoise() {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumVioletRed() {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMidnightBlue() {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMintCream() {#getMintCream--}
```
public static Color getMintCream()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMistyRose() {#getMistyRose--}
```
public static Color getMistyRose()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMoccasin() {#getMoccasin--}
```
public static Color getMoccasin()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getName() {#getName--}
```
public String getName()
```


Αποκτά το όνομα αυτής της  com.aspose.psd.Color .

**Returns:**
java.lang.String - Το όνομα αυτού του  com.aspose.psd.Color .
### getNavajoWhite() {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getNavy() {#getNavy--}
```
public static Color getNavy()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOldLace() {#getOldLace--}
```
public static Color getOldLace()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOlive() {#getOlive--}
```
public static Color getOlive()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOliveDrab() {#getOliveDrab--}
```
public static Color getOliveDrab()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrange() {#getOrange--}
```
public static Color getOrange()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrangeRed() {#getOrangeRed--}
```
public static Color getOrangeRed()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrchid() {#getOrchid--}
```
public static Color getOrchid()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleGoldenrod() {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleGreen() {#getPaleGreen--}
```
public static Color getPaleGreen()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleTurquoise() {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleVioletRed() {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPapayaWhip() {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPeachPuff() {#getPeachPuff--}
```
public static Color getPeachPuff()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPeru() {#getPeru--}
```
public static Color getPeru()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPink() {#getPink--}
```
public static Color getPink()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPlum() {#getPlum--}
```
public static Color getPlum()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPowderBlue() {#getPowderBlue--}
```
public static Color getPowderBlue()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPurple() {#getPurple--}
```
public static Color getPurple()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getR() {#getR--}
```
public byte getR()
```


Αποκτά την τιμή του κόκκινου συστατικού αυτής της  com.aspose.psd.Color  δομής.

**Returns:**
byte - Η τιμή του κόκκινου συστατικού αυτού του  com.aspose.psd.Color .
### getRed() {#getRed--}
```
public static Color getRed()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getRosyBrown() {#getRosyBrown--}
```
public static Color getRosyBrown()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getRoyalBlue() {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSaddleBrown() {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSalmon() {#getSalmon--}
```
public static Color getSalmon()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSandyBrown() {#getSandyBrown--}
```
public static Color getSandyBrown()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSaturation() {#getSaturation--}
```
public float getSaturation()
```


Αποκτά την τιμή κορεσμού hue-saturation-brightness (HSB) για αυτή τη  com.aspose.psd.Color  δομή.

**Returns:**
float - Ο κορεσμός αυτού του  com.aspose.psd.Color . Ο κορεσμός κυμαίνεται από 0.0 έως 1.0, όπου το 0.0 είναι γκρι κλίμακα και το 1.0 είναι ο μέγιστος κορεσμός.
### getSeaGreen() {#getSeaGreen--}
```
public static Color getSeaGreen()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSeaShell() {#getSeaShell--}
```
public static Color getSeaShell()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSienna() {#getSienna--}
```
public static Color getSienna()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSilver() {#getSilver--}
```
public static Color getSilver()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSkyBlue() {#getSkyBlue--}
```
public static Color getSkyBlue()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSlateBlue() {#getSlateBlue--}
```
public static Color getSlateBlue()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSlateGray() {#getSlateGray--}
```
public static Color getSlateGray()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSnow() {#getSnow--}
```
public static Color getSnow()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSpringGreen() {#getSpringGreen--}
```
public static Color getSpringGreen()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSteelBlue() {#getSteelBlue--}
```
public static Color getSteelBlue()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTan() {#getTan--}
```
public static Color getTan()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTeal() {#getTeal--}
```
public static Color getTeal()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getThistle() {#getThistle--}
```
public static Color getThistle()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTomato() {#getTomato--}
```
public static Color getTomato()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTransparent() {#getTransparent--}
```
public static Color getTransparent()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTurquoise() {#getTurquoise--}
```
public static Color getTurquoise()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getViolet() {#getViolet--}
```
public static Color getViolet()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWheat() {#getWheat--}
```
public static Color getWheat()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWhite() {#getWhite--}
```
public static Color getWhite()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWhiteSmoke() {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getYellow() {#getYellow--}
```
public static Color getYellow()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getYellowGreen() {#getYellowGreen--}
```
public static Color getYellowGreen()
```


Αποκτά ένα χρώμα που ορίζεται από το σύστημα.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό κατακερματισμού για αυτή τη  com.aspose.psd.Color  δομή.

**Returns:**
int - Μια ακέραια τιμή που καθορίζει τον κωδικό κατακερματισμού για αυτό το  com.aspose.psd.Color .
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Αποκτά μια τιμή που υποδεικνύει εάν αυτή η  com.aspose.psd.Color  δομή δεν έχει αρχικοποιηθεί.

**Returns:**
boolean - Αυτή η ιδιότητα επιστρέφει true εάν αυτό το χρώμα δεν έχει αρχικοποιηθεί· διαφορετικά, false.
### isEquals(Color obj1, Color obj2) {#isEquals-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public static boolean isEquals(Color obj1, Color obj2)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj1 | [Color](../../com.aspose.psd/color) |  |
| obj2 | [Color](../../com.aspose.psd/color) |  |

**Returns:**
boolean
### isKnownColor() {#isKnownColor--}
```
public boolean isKnownColor()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η δομή  com.aspose.psd.Color  είναι προκαθορισμένο χρώμα. Τα προκαθορισμένα χρώματα αντιπροσωπεύονται από τα στοιχεία της απαρίθμησης  Aspose.Imaging.KnownColor .

**Returns:**
boolean - True εάν αυτό το  com.aspose.psd.Color  δημιουργήθηκε από προκαθορισμένο χρώμα χρησιμοποιώντας είτε τη μέθοδο  Aspose.Imaging.Color.FromName(String)  είτε τη μέθοδο  Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) ; διαφορετικά, false.
### isNamedColor() {#isNamedColor--}
```
public boolean isNamedColor()
```


Αποκτά μια τιμή που υποδεικνύει εάν αυτή η  com.aspose.psd.Color  δομή είναι ένα ονομαστικό χρώμα ή μέλος της  Aspose.Imaging.KnownColor  απαρίθμησης.

**Returns:**
boolean - True εάν αυτό το  com.aspose.psd.Color  δημιουργήθηκε χρησιμοποιώντας είτε τη μέθοδο  Aspose.Imaging.Color.FromName(String)  είτε τη μέθοδο  Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) ; διαφορετικά, false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(Color left, Color right) {#op-Equality-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public static boolean op_Equality(Color left, Color right)
```


Δοκιμάζει εάν δύο καθορισμένες  com.aspose.psd.Color  δομές είναι ισοδύναμες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [Color](../../com.aspose.psd/color) | Το  com.aspose.psd.Color  που βρίσκεται στα αριστερά του τελεστή ισότητας. |
| right | [Color](../../com.aspose.psd/color) | Το  com.aspose.psd.Color  που βρίσκεται στα δεξιά του τελεστή ισότητας. |

**Returns:**
boolean - True εάν οι δύο δομές  com.aspose.psd.Color  είναι ίσες· διαφορετικά, false.
### op_Inequality(Color left, Color right) {#op-Inequality-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public static boolean op_Inequality(Color left, Color right)
```


Δοκιμάζει εάν δύο καθορισμένες  com.aspose.psd.Color  δομές είναι διαφορετικές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [Color](../../com.aspose.psd/color) | Το  com.aspose.psd.Color  που βρίσκεται στα αριστερά του τελεστή ανισότητας. |
| right | [Color](../../com.aspose.psd/color) | Το  com.aspose.psd.Color  που βρίσκεται στα δεξιά του τελεστή ανισότητας. |

**Returns:**
boolean - True εάν οι δύο δομές  com.aspose.psd.Color  είναι διαφορετικές· διαφορετικά, false.
### toArgb() {#toArgb--}
```
public int toArgb()
```


Αποκτά την τιμή ARGB 32-bit αυτής της  com.aspose.psd.Color  δομής.

**Returns:**
int - Η 32-bit τιμή ARGB αυτού του  com.aspose.psd.Color .
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static CmykColor toCmyk(Color pixel)
```


Η μετατροπή από Color σε CmykColor. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτική τη μέθοδο  CmykColorHelper.toCmyk(Color) .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Το pixel τύπου Color σε μορφή RGB. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static CmykColor[] toCmyk(Color[] pixels)
```


Η μετατροπή από Color σε CMYKColor. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτική τη μέθοδο  CmykColorHelper.toCmyk(Color[]) .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Τα pixels τύπου Color σε μορφή RGB. |

**Returns:**
com.aspose.psd.CmykColor[] - Το  Aspose:Imaging:CmykColor[] .
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static CmykColor toCmykIcc(Color pixel)
```


Η μετατροπή από Color σε CMYKColor χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτική τη μέθοδο  CmykColorHelper.toCmykIcc(Color) .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Το pixel τύπου Color σε μορφή RGB. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static CmykColor toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


Η μετατροπή από Color σε CMYKColor χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτική τη μέθοδο  CmykColorHelper.toCmykIcc(Color, InputStream, InputStream) .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Το pixel τύπου Color σε μορφή RGB. |
| rgbIccStream | java.io.InputStream | Η ροή που περιέχει το προφίλ icc rgb. |
| cmykIccStream | java.io.InputStream | Η ροή που περιέχει το προφίλ icc cmyk. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor[] .
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static CmykColor[] toCmykIcc(Color[] pixels)
```


Η μετατροπή από Color σε CMYKColor χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποτελεσματικό το CmykColorHelper.toCmykIcc(Color[]).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Τα pixels τύπου Color σε μορφή RGB. |

**Returns:**
com.aspose.psd.CmykColor[] - Το CmykColor[] .
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static CmykColor[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


Η μετατροπή από Color σε CMYKColor χρησιμοποιώντας μετατροπή icc. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποτελεσματικό το CmykColorHelper.toCmykIcc(Color[], InputStream, InputStream).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Τα pixels τύπου Color σε μορφή RGB. |
| rgbIccStream | java.io.InputStream | Η ροή που περιέχει το προφίλ icc rgb. |
| cmykIccStream | java.io.InputStream | Η ροή που περιέχει το προφίλ icc cmyk. |

**Returns:**
com.aspose.psd.CmykColor[] - Το CmykColor[] .
### toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIcc-internalized-com.aspose.psd.Color-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static CmykColor toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) |  |
| rgbIccStream | com.aspose.ms.System.IO.Stream |  |
| cmykIccStream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor)
### toCmykIcc_internalized(Color[] pixels, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIcc-internalized-com.aspose.psd.Color---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static CmykColor[] toCmykIcc_internalized(Color[] pixels, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) |  |
| rgbIccStream | com.aspose.ms.System.IO.Stream |  |
| cmykIccStream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
com.aspose.psd.CmykColor[]
### toKnownColor() {#toKnownColor--}
```
public int toKnownColor()
```


Λαμβάνει την τιμή  Aspose.Imaging.KnownColor  του αυτού του δομικού τύπου  com.aspose.psd.Color .

**Returns:**
int - Ένα στοιχείο της απαρίθμησης Aspose.Imaging.KnownColor, εάν το com.aspose.psd.Color δημιουργείται από προεπιλεγμένο χρώμα χρησιμοποιώντας είτε τη μέθοδο Aspose.Imaging.Color.FromName(String) είτε τη μέθοδο Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor); διαφορετικά, 0.
### toString() {#toString--}
```
public String toString()
```


Μετατρέπει αυτό το δομικό τύπο  com.aspose.psd.Color  σε μια αναγνώσιμη από άνθρωπο συμβολοσειρά.

**Returns:**
java.lang.String - Μια συμβολοσειρά που είναι το όνομα του com.aspose.psd.Color, εάν το com.aspose.psd.Color δημιουργείται από προεπιλεγμένο χρώμα χρησιμοποιώντας είτε τη μέθοδο Aspose.Imaging.Color.FromName(String) είτε τη μέθοδο Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor); διαφορετικά, μια συμβολοσειρά που αποτελείται από τα ονόματα των συνιστωσών ARGB και τις τιμές τους.
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

