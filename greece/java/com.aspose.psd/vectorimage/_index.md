---
title: "VectorImage"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Η διανυσματική εικόνα είναι η βασική κλάση για όλους τους τύπους διανυσματικών εικόνων."
type: docs
weight: 111
url: /el/java/com.aspose.psd/vectorimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image)

**All Implemented Interfaces:**
[com.aspose.psd.interfaces.IObjectWithSizeF](../../com.aspose.psd.interfaces/iobjectwithsizef)
```
public abstract class VectorImage extends Image implements IObjectWithSizeF
```

Η διανυσματική εικόνα είναι η βασική κλάση για όλους τους τύπους διανυσματικών εικόνων.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [VectorImage()](#VectorImage--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [OnCreate_internalized](#OnCreate-internalized) | Συμβαίνει όταν η εικόνα φορτώθηκε |
| [OnLoad_internalized](#OnLoad-internalized) | Συμβαίνει όταν η εικόνα φορτώθηκε από το createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | Συμβαίνει όταν η εικόνα φορτώθηκε ή αποθηκεύτηκε |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Συμβαίνει όταν χρησιμοποιήθηκε η πίστωση |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [cacheData()](#cacheData--) | Αποθηκεύει στην κρυφή μνήμη τα δεδομένα και διασφαλίζει ότι δεν θα γίνει πρόσθετη φόρτωση δεδομένων από το υποκείμενο DataStreamSupporter.DataStreamContainer. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη ροή. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη ροή και προαιρετικά χρησιμοποιώντας τις καθορισμένες loadOptions. |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη διαδρομή αρχείου. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη διαδρομή αρχείου και προαιρετικά χρησιμοποιώντας τις καθορισμένες open options. |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | Καθορίζει εάν η εικόνα μπορεί να αποθηκευτεί στο συγκεκριμένο μορφότυπο αρχείου που αντιπροσωπεύεται από τις παρεχόμενες save options. |
| [close()](#close--) | Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. |
| [convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Μετατρέπει σε aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Δημιουργεί μια νέα εικόνα χρησιμοποιώντας τις καθορισμένες create options. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Δημιουργεί μια νέα εικόνα χρησιμοποιώντας τις καθορισμένες εικόνες ως σελίδες |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Δημιουργεί μια νέα εικόνα με τις καθορισμένες εικόνες ως σελίδες. |
| [dispose()](#dispose--) | Αποδεσμεύει την τρέχουσα παρουσία. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η αυτόματη προσαρμογή παλέτας. |
| [getBackgroundColor()](#getBackgroundColor--) | Λαμβάνει ή ορίζει μια τιμή για το χρώμα φόντου. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Λαμβάνει τον αριθμό bits ανά pixel της εικόνας. |
| [getBounds()](#getBounds--) | Λαμβάνει τα όρια της εικόνας. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Λαμβάνει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | Λαμβάνει το περιέκτη Image. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Λαμβάνει τη ροή δεδομένων του αντικειμένου. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Λαμβάνει την παλέτα βαθιάς προσαρμογής. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Λαμβάνει τις προεπιλεγμένες επιλογές. |
| [getDisposed()](#getDisposed--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί. |
| [getFileFormat()](#getFileFormat--) | Λαμβάνει μια τιμή μορφής αρχείου. |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Λαμβάνει τη μορφή αρχείου. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Λαμβάνει τη μορφή αρχείου. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Λαμβάνει τη μορφή αρχείου. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Λαμβάνει το ορθογώνιο που ταιριάζει στην τρέχουσα εικόνα. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Λαμβάνει το ορθογώνιο που ταιριάζει στην τρέχουσα εικόνα. |
| [getHeight()](#getHeight--) | Λαμβάνει το ύψος της εικόνας. |
| [getHeightF()](#getHeightF--) | Λαμβάνει το ύψος του αντικειμένου, σε ίντσες. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Λαμβάνει τον παρακολουθητή διακοπής. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Λαμβάνει τον διαχειριστή μνήμης. |
| [getOriginalOptions()](#getOriginalOptions--) | Λαμβάνει τις επιλογές βάσει των αρχικών ρυθμίσεων του αρχείου. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Λαμβάνει την εικόνα που μπορεί να βαφτεί. |
| [getPalette()](#getPalette--) | Λαμβάνει την παλέτα χρωμάτων. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Δημιουργεί την ιδιωτική κρυφή μνήμη γραμματοσειρών. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Λαμβάνει τις πληροφορίες του χειριστή συμβάντος προόδου. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Λαμβάνει τις πληροφορίες του χειριστή συμβάντος προόδου. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Λαμβάνει ένα αναλογικό ύψος. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Λαμβάνει ένα αναλογικό πλάτος. |
| [getSize()](#getSize--) | Λαμβάνει το μέγεθος της εικόνας. |
| [getSizeF()](#getSizeF--) | Λαμβάνει το μέγεθος του αντικειμένου, σε ίντσες. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Λαμβάνει τη διαδρομή αρχείου της πηγαίας εικόνας εάν υπάρχει. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν το αντικείμενο χρησιμοποιεί στρατηγική βελτιστοποίησης μνήμης |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Λαμβάνει την άδεια venture. |
| [getWidth()](#getWidth--) | Λαμβάνει το πλάτος της εικόνας. |
| [getWidthF()](#getWidthF--) | Λαμβάνει το πλάτος του αντικειμένου, σε ίντσες. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα έχει χρώμα φόντου. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία της εικόνας έχει αλλάξει μετά τη φόρτωση. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Λαμβάνει ή ορίζει τη μέγιστη τιμή προόδου |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Δείχνει την πρόοδο. |
| [isCached()](#isCached--) | Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα του αντικειμένου είναι προσωρινά αποθηκευμένα αυτή τη στιγμή και δεν απαιτείται ανάγνωση δεδομένων. |
| [isUsePalette()](#isUsePalette--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η παλέτα της εικόνας χρησιμοποιείται. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή. |
| [load(String filePath)](#load-java.lang.String-) | Φορτώνει μια νέα εικόνα από το συγκεκριμένο αρχείο. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | Φορτώνει μια νέα εικόνα από το συγκεκριμένο αρχείο. |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή. |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Καλείται όταν ο περιέκτης αυτού του [Image](../../com.aspose.psd/image) έχει οριστεί. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Αλλάζει το μέγεθος της εικόνας. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Αλλάζει το μέγεθος της εικόνας. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Αλλάζει το μέγεθος της εικόνας. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Αλλάζει το ύψος αναλογικά. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | Αλλάζει το ύψος αναλογικά. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Αλλάζει το ύψος αναλογικά. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Αλλάζει το πλάτος αναλογικά. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | Αλλάζει το πλάτος αναλογικά. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Αλλάζει το πλάτος αναλογικά. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα. |
| [save()](#save--) | Αποθηκεύει τα δεδομένα εικόνας στην υποκείμενη ροή. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη ροή. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη ροή. |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [save(String filePath)](#save-java.lang.String-) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) |  |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Ορίζει μια τιμή που υποδεικνύει αν γίνεται αυτόματη προσαρμογή παλέτας. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Ανακτά ή ορίζει μια τιμή που υποδεικνύει αν η εικόνα έχει χρώμα φόντου. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Λαμβάνει ή ορίζει μια τιμή για το χρώμα φόντου. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Ορίζει την υπόδειξη μεγέθους buffer, η οποία ορίζεται ως το μέγιστο επιτρεπτό μέγεθος για όλα τα εσωτερικά buffers. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Ορίζει το Image container. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Ορίζει τη ροή δεδομένων του αντικειμένου. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Ορίζει μια τιμή που υποδεικνύει αν [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία της εικόνας έχει αλλάξει μετά τη φόρτωση. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Ορίζει τον παρατηρητή διακοπής. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Ορίζει τον διαχειριστή μνήμης. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Ορίζει την παλέτα χρωμάτων. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Ορίζει την παλέτα εικόνας. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Όλα τα προϊόντα Aspose πρέπει να υλοποιούν αυτή τη μέθοδο. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorImage() {#VectorImage--}
```
public VectorImage()
```


### OnCreate_internalized {#OnCreate-internalized}
```
public static final Event<AfterCreate> OnCreate_internalized
```


Συμβαίνει όταν η εικόνα φορτώθηκε

### OnLoad_internalized {#OnLoad-internalized}
```
public static final Event<AfterLoad> OnLoad_internalized
```


Συμβαίνει όταν η εικόνα φορτώθηκε από το createFirstSupportedLoader

### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


Συμβαίνει όταν η εικόνα φορτώθηκε ή αποθηκεύτηκε

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


Συμβαίνει όταν χρησιμοποιήθηκε η πίστωση

### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


Αποθηκεύει στην κρυφή μνήμη τα δεδομένα και διασφαλίζει ότι δεν θα γίνει πρόσθετη φόρτωση δεδομένων από το υποκείμενο DataStreamSupporter.DataStreamContainer.

### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή από την οποία θα φορτωθεί. |

**Returns:**
boolean -  true  αν η εικόνα μπορεί να φορτωθεί από το καθορισμένο stream; διαφορετικά,  false .
### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη ροή και προαιρετικά χρησιμοποιώντας τις καθορισμένες loadOptions.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή από την οποία θα φορτωθεί. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Οι επιλογές φόρτωσης. |

**Returns:**
boolean -  true  αν η εικόνα μπορεί να φορτωθεί από το καθορισμένο stream; διαφορετικά,  false .
### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη διαδρομή αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου. |

**Returns:**
boolean -  true  αν η εικόνα μπορεί να φορτωθεί από το καθορισμένο αρχείο; διαφορετικά,  false .
### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη διαδρομή αρχείου και προαιρετικά χρησιμοποιώντας τις καθορισμένες open options.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Οι επιλογές φόρτωσης. |

**Returns:**
boolean -  true  αν η εικόνα μπορεί να φορτωθεί από το καθορισμένο αρχείο; διαφορετικά,  false .
### canLoadInternal_internalized(System.IO.Stream stream) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
boolean
### canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
boolean
### canSave(ImageOptionsBase options) {#canSave-com.aspose.psd.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


Καθορίζει εάν η εικόνα μπορεί να αποθηκευτεί στο συγκεκριμένο μορφότυπο αρχείου που αντιπροσωπεύεται από τις παρεχόμενες save options.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Οι επιλογές αποθήκευσης προς χρήση. |

**Returns:**
boolean -  true  αν η εικόνα μπορεί να αποθηκευτεί στην καθορισμένη μορφή αρχείου που αντιπροσωπεύεται από τις παρεχόμενες επιλογές αποθήκευσης; διαφορετικά,  false .
### close() {#close--}
```
public void close()
```


Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. Αυτή η μέθοδος απλώς καλεί τη μέθοδο dispose.

### convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public abstract ApsPage convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)
```


Μετατρέπει σε aps.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Οι επιλογές εικόνας. |
| mode | int | Η λειτουργία. |
| clippingRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο αποκοπής. |

**Returns:**
com.aspose.foundation.rendering.ApsPage - Η σελίδα APS.
### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


Δημιουργεί μια νέα εικόνα χρησιμοποιώντας τις καθορισμένες create options.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Οι επιλογές εικόνας. |
| πλάτος | int | Το πλάτος. |
| ύψος | int | Το ύψος. |

**Returns:**
[Image](../../com.aspose.psd/image) - The newly created image.
### create(Image[] images) {#create-com.aspose.psd.Image---}
```
public static Image create(Image[] images)
```


Δημιουργεί μια νέα εικόνα χρησιμοποιώντας τις καθορισμένες εικόνες ως σελίδες

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | Οι εικόνες. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### create(Image[] images, boolean disposeImages) {#create-com.aspose.psd.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


Δημιουργεί μια νέα εικόνα με τις καθορισμένες εικόνες ως σελίδες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | Οι εικόνες. |
| disposeImages | boolean | αν οριστεί σε  true  [απόρριψη εικόνων]. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### dispose() {#dispose--}
```
public final void dispose()
```


Αποδεσμεύει την τρέχουσα παρουσία.

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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
### getAutoAdjustPalette() {#getAutoAdjustPalette--}
```
public boolean getAutoAdjustPalette()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η αυτόματη προσαρμογή παλέτας.

**Returns:**
boolean -  true  εάν ενεργοποιηθεί η αυτόματη προσαρμογή παλέτας· διαφορετικά,  false .
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Λαμβάνει ή ορίζει μια τιμή για το χρώμα φόντου.

**Returns:**
[Color](../../com.aspose.psd/color)
### getBitsPerPixel() {#getBitsPerPixel--}
```
public abstract int getBitsPerPixel()
```


Λαμβάνει τον αριθμό bits ανά pixel της εικόνας.

**Returns:**
int - Ο αριθμός των bit ανά εικονοστοιχείο της εικόνας.
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Λαμβάνει τα όρια της εικόνας.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The image bounds.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Λαμβάνει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers.

Τιμή: Η υπόδειξη μεγέθους buffer, σε megabytes. Μη θετική τιμή σημαίνει ότι δεν υπάρχει περιορισμός μνήμης για εσωτερικά buffers

**Returns:**
int - η υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Λαμβάνει το περιέκτη Image.

Τιμή: Ο  Image  container.

Εάν αυτή η ιδιότητα δεν είναι null, υποδεικνύει ότι η εικόνα περιέχεται μέσα σε άλλη εικόνα.

**Returns:**
[Image](../../com.aspose.psd/image)
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Λαμβάνει τη ροή δεδομένων του αντικειμένου.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDeeplyAdjustPalette_internalized() {#getDeeplyAdjustPalette-internalized--}
```
public boolean getDeeplyAdjustPalette_internalized()
```


Λαμβάνει την παλέτα βαθιάς προσαρμογής.

**Returns:**
boolean - Η βαθιά ρύθμιση παλέτας.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Λαμβάνει τις προεπιλεγμένες επιλογές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| args | java.lang.Object[] | Τα επιχειρήματα. |

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Default options
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί.

**Returns:**
boolean -  true  εάν διαγραφεί· διαφορετικά,  false .
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Λαμβάνει μια τιμή μορφής αρχείου.

**Returns:**
long
### getFileFormat(System.IO.Stream stream) {#getFileFormat-com.aspose.ms.System.IO.Stream-}
```
public static long getFileFormat(System.IO.Stream stream)
```


Λαμβάνει τη μορφή αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | Η ροή. |

--------------------

Η καθορισμένη μορφή αρχείου δεν σημαίνει ότι η συγκεκριμένη εικόνα μπορεί να φορτωθεί. Χρησιμοποιήστε μία από τις υπερφορτώσεις της μεθόδου CanLoad για να προσδιορίσετε εάν η ροή μπορεί να φορτωθεί. |

**Returns:**
long - Η καθορισμένη μορφή αρχείου.
### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


Λαμβάνει τη μορφή αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | stream | java.io.InputStream | Η ροή. |

Η καθορισμένη μορφή αρχείου δεν σημαίνει ότι η συγκεκριμένη εικόνα μπορεί να φορτωθεί. Χρησιμοποιήστε μία από τις υπερφορτώσεις της μεθόδου CanLoad για να προσδιορίσετε εάν η ροή μπορεί να φορτωθεί. |

**Returns:**
long - Η καθορισμένη μορφή αρχείου.
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


Λαμβάνει τη μορφή αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή αρχείου. |

Η καθορισμένη μορφή αρχείου δεν σημαίνει ότι η συγκεκριμένη εικόνα μπορεί να φορτωθεί. Χρησιμοποιήστε μία από τις υπερφορτώσεις της μεθόδου CanLoad για να προσδιορίσετε εάν το αρχείο μπορεί να φορτωθεί. |

**Returns:**
long - Η καθορισμένη μορφή αρχείου.
### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


Λαμβάνει το ορθογώνιο που ταιριάζει στην τρέχουσα εικόνα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο για το οποίο λαμβάνεται το κατάλληλο ορθογώνιο. |
| πλάτος | int | Το πλάτος του αντικειμένου. |
| ύψος | int | Το ύψος του αντικειμένου. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


Λαμβάνει το ορθογώνιο που ταιριάζει στην τρέχουσα εικόνα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο για το οποίο λαμβάνεται το κατάλληλο ορθογώνιο. |
| pixels | int[] | Τα 32-bit ARGB pixel. |
| πλάτος | int | Το πλάτος του αντικειμένου. |
| ύψος | int | Το ύψος του αντικειμένου. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Λαμβάνει το ύψος της εικόνας.

**Returns:**
int - το ύψος της εικόνας.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Λαμβάνει το ύψος του αντικειμένου, σε ίντσες.

**Returns:**
float - το ύψος του αντικειμένου, σε ίντσες.
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Λαμβάνει τον παρακολουθητή διακοπής.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


Λαμβάνει τον διαχειριστή μνήμης.

Τιμή: Ο διαχειριστής μνήμης.

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - ο διαχειριστής μνήμης.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Λαμβάνει τις επιλογές βάσει των αρχικών ρυθμίσεων του αρχείου. Αυτό μπορεί να είναι χρήσιμο για να διατηρηθούν το βάθος χρώματος και άλλες παράμετροι της αρχικής εικόνας αμετάβλητες. Για παράδειγμα, εάν φορτώσουμε μια ασπρόμαυρη εικόνα PNG με 1 bit ανά pixel και στη συνέχεια την αποθηκεύσουμε χρησιμοποιώντας τη μέθοδο `DataStreamSupporter.Save(string)`, θα παραχθεί η έξοδος PNG εικόνα με 8-bit ανά pixel. Για να το αποφύγουμε και να αποθηκεύσουμε την εικόνα PNG με 1-bit ανά pixel, χρησιμοποιήστε αυτή τη μέθοδο για να λάβετε τις αντίστοιχες επιλογές αποθήκευσης και περάστε τις στη μέθοδο `Image.Save(string, ImageOptionsBase)` ως δεύτερη παράμετρο.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - The options based on the original file settings.
### getPaintableImage_internalized(ImageOptionsBase paintableOptions) {#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-}
```
public Image getPaintableImage_internalized(ImageOptionsBase paintableOptions)
```


Λαμβάνει την εικόνα που μπορεί να βαφτεί.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| paintableOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

**Returns:**
[Image](../../com.aspose.psd/image) - the paintable image.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Λαμβάνει την παλέτα χρωμάτων. Η παλέτα χρωμάτων δεν χρησιμοποιείται όταν τα pixel αναπαρίστανται άμεσα.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPrivateFontCache_internalized() {#getPrivateFontCache-internalized--}
```
public final PalPrivateFontCache getPrivateFontCache_internalized()
```


Δημιουργεί την ιδιωτική κρυφή μνήμη γραμματοσειρών.

**Returns:**
com.aspose.foundation.pal.PalPrivateFontCache - Η ιδιωτική κρυφή μνήμη γραμματοσειρών.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Λαμβάνει τις πληροφορίες του χειριστή συμβάντος προόδου.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


Λαμβάνει τις πληροφορίες του χειριστή συμβάντος προόδου.

Τιμή: Οι πληροφορίες του χειριστή συμβάντος προόδου.

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


Λαμβάνει ένα αναλογικό ύψος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλάτος | int | Το πλάτος. |
| ύψος | int | Το ύψος. |
| newWidth | int | Το νέο πλάτος. |

**Returns:**
int - Το αναλογικό ύψος.
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


Λαμβάνει ένα αναλογικό πλάτος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλάτος | int | Το πλάτος. |
| ύψος | int | Το ύψος. |
| newHeight | int | Το νέο ύψος. |

**Returns:**
int - Το αναλογικό πλάτος.
### getSize() {#getSize--}
```
public Size getSize()
```


Λαμβάνει το μέγεθος της εικόνας.

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSizeF() {#getSizeF--}
```
public final SizeF getSizeF()
```


Λαμβάνει το μέγεθος του αντικειμένου, σε ίντσες.

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - the object size, in inches.
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Λαμβάνει τη διαδρομή αρχείου της πηγαίας εικόνας εάν υπάρχει. Επιστρέφει μια κενή συμβολοσειρά εάν δεν μπορεί να βρεθεί η πηγαία διαδρομή.

**Returns:**
java.lang.String - Η διαδρομή αρχείου της πηγαίας εικόνας.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν το αντικείμενο χρησιμοποιεί στρατηγική βελτιστοποίησης μνήμης

Τιμή:  true  εάν το αντικείμενο χρησιμοποιεί στρατηγική βελτιστοποίησης μνήμης· διαφορετικά,  false .

**Returns:**
boolean - μια τιμή που υποδεικνύει εάν το αντικείμενο χρησιμοποιεί στρατηγική βελτιστοποίησης μνήμης
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Λαμβάνει την άδεια venture.

**Returns:**
java.lang.Object - Η άδεια venture ως αντικείμενο.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Λαμβάνει το πλάτος της εικόνας.

**Returns:**
int - το πλάτος της εικόνας.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Λαμβάνει το πλάτος του αντικειμένου, σε ίντσες.

**Returns:**
float - το πλάτος του αντικειμένου, σε ίντσες.
### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα έχει χρώμα φόντου.

**Returns:**
boolean
### hasImageChanged_internalized() {#hasImageChanged-internalized--}
```
public boolean hasImageChanged_internalized()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία της εικόνας έχει αλλάξει μετά τη φόρτωση.

**Returns:**
boolean -  true  εάν αυτή η παρουσία έχει τροποποιηθεί η εικόνα· διαφορετικά,  false .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### incrementProgressMaxValue_internalized(int value) {#incrementProgressMaxValue-internalized-int-}
```
public final void incrementProgressMaxValue_internalized(int value)
```


Λαμβάνει ή ορίζει τη μέγιστη τιμή προόδου

Τιμή: Η μέγιστη τιμή προόδου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public final void indicateProgress_internalized(EventType eventType)
```


Δείχνει την πρόοδο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) |  |

### isCached() {#isCached--}
```
public abstract boolean isCached()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα του αντικειμένου είναι προσωρινά αποθηκευμένα αυτή τη στιγμή και δεν απαιτείται ανάγνωση δεδομένων.

**Returns:**
boolean - μια τιμή που υποδεικνύει εάν τα δεδομένα του αντικειμένου είναι προσωρινά αποθηκευμένα αυτή τη στιγμή και δεν απαιτείται ανάγνωση δεδομένων.
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η παλέτα της εικόνας χρησιμοποιείται.

Τιμή:  true  εάν η παλέτα χρησιμοποιείται στην εικόνα· διαφορετικά,  false .

**Returns:**
boolean - μια τιμή που υποδεικνύει εάν η παλέτα εικόνας χρησιμοποιείται.
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Image load(InputStream stream)
```


Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή από την οποία θα φορτωθεί η εικόνα. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή από την οποία θα φορτωθεί η εικόνα. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Οι επιλογές φόρτωσης. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αρχείο | java.io.RandomAccessFile | Το αρχείο από το οποίο θα φορτωθεί η εικόνα. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αρχείο | java.io.RandomAccessFile | Το αρχείο από το οποίο θα φορτωθεί η εικόνα. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Οι επιλογές φόρτωσης. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


Φορτώνει μια νέα εικόνα από το συγκεκριμένο αρχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή του αρχείου από την οποία θα φορτωθεί η εικόνα. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


Φορτώνει μια νέα εικόνα από το συγκεκριμένο αρχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή του αρχείου από την οποία θα φορτωθεί η εικόνα. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Οι επιλογές φόρτωσης. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### loadInternal_internalized(System.IO.Stream stream) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image loadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static Image loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### load_internalized(System.IO.Stream stream) {#load-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image load_internalized(System.IO.Stream stream)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### load_internalized(System.IO.Stream stream, long startPosition) {#load-internalized-com.aspose.ms.System.IO.Stream-long-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition)
```


Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Η ροή από την οποία θα φορτωθεί η εικόνα. |
| startPosition | long | Η αρχική θέση από την οποία θα φορτωθεί η εικόνα. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions) {#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)
```


Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Η ροή από την οποία θα φορτωθεί η εικόνα. |
| startPosition | long | Η αρχική θέση από την οποία θα φορτωθεί η εικόνα. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Οι επιλογές φόρτωσης. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### onContainerSet_internalized() {#onContainerSet-internalized--}
```
public void onContainerSet_internalized()
```


Καλείται όταν ο περιέκτης αυτού του [Image](../../com.aspose.psd/image) έχει οριστεί.

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


Αλλάζει το μέγεθος της εικόνας. Χρησιμοποιείται η προεπιλογή ResizeType.LeftTopToLeftTop.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newWidth | int | Το νέο πλάτος. |
| newHeight | int | Το νέο ύψος. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.psd.ImageResizeSettings-}
```
public abstract void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Αλλάζει το μέγεθος της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newWidth | int | Το νέο πλάτος. |
| newHeight | int | Το νέο ύψος. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Οι ρυθμίσεις αλλαγής μεγέθους. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public abstract void resize(int newWidth, int newHeight, int resizeType)
```


Αλλάζει το μέγεθος της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newWidth | int | Το νέο πλάτος. |
| newHeight | int | Το νέο ύψος. |
| resizeType | int | Ο τύπος αλλαγής μεγέθους. |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


Αλλάζει το ύψος αναλογικά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newHeight | int | Το νέο ύψος. |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


Αλλάζει το ύψος αναλογικά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newHeight | int | Το νέο ύψος. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Οι ρυθμίσεις αλλαγής μεγέθους εικόνας. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Αλλάζει το ύψος αναλογικά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newHeight | int | Το νέο ύψος. |
| resizeType | int | Τύπος αλλαγής μεγέθους. |

### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


Αλλάζει το πλάτος αναλογικά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newWidth | int | Το νέο πλάτος. |

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


Αλλάζει το πλάτος αναλογικά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newWidth | int | Το νέο πλάτος. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Οι ρυθμίσεις αλλαγής μεγέθους εικόνας. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Αλλάζει το πλάτος αναλογικά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newWidth | int | Το νέο πλάτος. |
| resizeType | int | Τύπος αλλαγής μεγέθους. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public abstract void rotateFlip(int rotateFlipType)
```


Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rotateFlipType | int | Τύπος της περιστροφής/αναστροφής. |

### save() {#save--}
```
public final void save()
```


Αποθηκεύει τα δεδομένα εικόνας στην υποκείμενη ροή.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Η ροή για αποθήκευση των δεδομένων του αντικειμένου. |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Η ροή για αποθήκευση των δεδομένων της εικόνας. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Οι επιλογές αποθήκευσης. |

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Η ροή για αποθήκευση των δεδομένων της εικόνας. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Οι επιλογές αποθήκευσης. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο ορίων της εικόνας προορισμού. Ορίστε το κενό ορθογώνιο για χρήση των ορίων της πηγής. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αρχείο | java.io.RandomAccessFile | Η ροή για αποθήκευση των δεδομένων του αντικειμένου. |

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αρχείο | java.io.RandomAccessFile | Το αρχείο για αποθήκευση των δεδομένων της εικόνας. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Οι επιλογές. |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αρχείο | java.io.RandomAccessFile | Το αρχείο για αποθήκευση των δεδομένων της εικόνας. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Οι επιλογές αποθήκευσης. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο ορίων της προορισμένης εικόνας. Ορίστε το κενό ορθογώνιο για χρήση των ορίων πηγής. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου για αποθήκευση των δεδομένων του αντικειμένου. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου για αποθήκευση των δεδομένων του αντικειμένου. |
| overWrite | boolean | εάν οριστεί σε  true  θα αντικαταστήσει το περιεχόμενο του αρχείου, διαφορετικά θα προσαρτηθεί. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Οι επιλογές. |

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Οι επιλογές. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο ορίων της προορισμένης εικόνας. Ορίστε το κενό ορθογώνιο για χρήση των ορίων πηγής. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει αν γίνεται αυτόματη προσαρμογή παλέτας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | true  εάν ενεργοποιηθεί η αυτόματη προσαρμογή παλέτας· διαφορετικά,  false . |

### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Ανακτά ή ορίζει μια τιμή που υποδεικνύει αν η εικόνα έχει χρώμα φόντου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


Λαμβάνει ή ορίζει μια τιμή για το χρώμα φόντου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Ορίζει την υπόδειξη μεγέθους buffer, η οποία ορίζεται ως το μέγιστο επιτρεπτό μέγεθος για όλα τα εσωτερικά buffers.

Τιμή: Η υπόδειξη μεγέθους buffer, σε megabytes. Μη θετική τιμή σημαίνει ότι δεν υπάρχει περιορισμός μνήμης για εσωτερικά buffers

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | η υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


Ορίζει το Image container.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | Το  Image  container. |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Ορίζει τη ροή δεδομένων του αντικειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | Η ροή δεδομένων του αντικειμένου. |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει αν [ignore after save].

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | true  εάν [ignore after save]; διαφορετικά,  false . |

### setImageChanged_internalized(boolean value) {#setImageChanged-internalized-boolean-}
```
public void setImageChanged_internalized(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία της εικόνας έχει αλλάξει μετά τη φόρτωση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | true  εάν αυτή η παρουσία έχει αλλαγή εικόνας· διαφορετικά,  false . |

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Ορίζει τον παρατηρητή διακοπής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | ο παρακολουθητής διακοπής. |

### setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose) {#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-}
```
public void setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)
```


Ορίζει τον διαχειριστή μνήμης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| memoryManager | com.aspose.internal.memorymanagement.MemMgr | Ο διαχειριστής μνήμης. |
| needDispose | boolean | αν οριστεί σε  true  [need dispose]. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Ορίζει την παλέτα χρωμάτων. Η παλέτα χρωμάτων δεν χρησιμοποιείται όταν τα pixel αναπαρίστανται άμεσα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | Η παλέτα χρωμάτων. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.psd.IColorPalette-boolean-}
```
public abstract void setPalette(IColorPalette palette, boolean updateColors)
```


Ορίζει την παλέτα εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Η παλέτα για ορισμό. |
| updateColors | boolean | αν οριστεί σε  true  τα χρώματα θα ενημερωθούν σύμφωνα με τη νέα παλέτα· διαφορετικά οι δείκτες χρωμάτων παραμένουν αμετάβλητοι. Σημειώστε ότι οι αμετάβλητοι δείκτες μπορεί να προκαλέσουν σφάλμα στην εικόνα κατά τη φόρτωση εάν κάποιοι δείκτες δεν έχουν αντίστοιχες καταχωρήσεις στην παλέτα. |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


Όλα τα προϊόντα Aspose πρέπει να υλοποιούν αυτή τη μέθοδο. Καλείται από ένα προϊόν GroupDocs για να υποδείξει εάν το GroupDocs είναι αδειοδοτημένο ή όχι και να καθορίσει ένα προσαρμοσμένο υδατογράφημα. Όταν το GroupDocs είναι αδειοδοτημένο, αυτή η παρουσία του εγγράφου πρέπει να συμπεριφέρεται επίσης ως αδειοδοτημένη ακόμη και αν το προϊόν Aspose δεν είναι αδειοδοτημένο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ventureLicense | java.lang.Object |  |

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

