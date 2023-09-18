---
title: MultiPageOptions
second_title: Aspose.PSD for Java API Reference
description: Base class for multiple pages supported formats
type: docs
weight: 17
url: /java/com.aspose.psd.imageoptions/multipageoptions/
---

**Inheritance:**
java.lang.Object
```
public class MultiPageOptions
```

Base class for multiple pages supported formats
## Constructors

| Constructor | Description |
| --- | --- |
| [MultiPageOptions()](#MultiPageOptions--) | Initializes a new instance of the  MultiPageOptions  class. |
| [MultiPageOptions(int[] pages)](#MultiPageOptions-int---) | Initializes a new instance of the  MultiPageOptions  class. |
| [MultiPageOptions(int[] pages, Rectangle exportArea)](#MultiPageOptions-int---com.aspose.psd.Rectangle-) | Initializes a new instance of the  MultiPageOptions  class. |
| [MultiPageOptions(String[] pageTitles)](#MultiPageOptions-java.lang.String---) | Initializes a new instance of the  MultiPageOptions  class. |
| [MultiPageOptions(String[] pageTitles, Rectangle exportArea)](#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-) | Initializes a new instance of the  MultiPageOptions  class. |
| [MultiPageOptions(IntRange[] ranges)](#MultiPageOptions-com.aspose.psd.IntRange---) | Initializes a new instance of the  MultiPageOptions  class. |
| [MultiPageOptions(IntRange[] ranges, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-) | Initializes a new instance of the  MultiPageOptions  class. |
| [MultiPageOptions(IntRange range)](#MultiPageOptions-com.aspose.psd.IntRange-) | Initializes a new instance of the  MultiPageOptions  class. |
| [MultiPageOptions(IntRange range, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-) | Initializes a new instance of the  MultiPageOptions  class. |
| [MultiPageOptions(int page)](#MultiPageOptions-int-) | Initializes a new instance of the  MultiPageOptions  class. |
| [MultiPageOptions(int page, Rectangle exportArea)](#MultiPageOptions-int-com.aspose.psd.Rectangle-) | Initializes a new instance of the  MultiPageOptions  class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExportArea()](#getExportArea--) | Gets or sets the export area. |
| [getMergeLayers()](#getMergeLayers--) | Gets a value indicating whether [merege layers]. |
| [getMode()](#getMode--) | Gets or sets the mode. |
| [getOutputLayersNames()](#getOutputLayersNames--) | Gets or sets the output layers names(Works if export format supports layers naming, for example for Psd) |
| [getPageRasterizationOptions()](#getPageRasterizationOptions--) | Gets the page rasterization options. |
| [getPageTitles()](#getPageTitles--) | Gets or sets the page titles. |
| [getPages()](#getPages--) | Gets or sets the pages. |
| [getTimeInterval_internalized()](#getTimeInterval-internalized--) | Gets the time interval. |
| [hashCode()](#hashCode--) |  |
| [initPages(IntRange[] ranges)](#initPages-com.aspose.psd.IntRange---) | Initializes the pages from ranges array |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setExportArea(Rectangle value)](#setExportArea-com.aspose.psd.Rectangle-) | Gets or sets the export area. |
| [setMergeLayers(boolean value)](#setMergeLayers-boolean-) | Sets a value indicating whether [merege layers]. |
| [setMode(int value)](#setMode-int-) | Gets or sets the mode. |
| [setOutputLayersNames(String[] value)](#setOutputLayersNames-java.lang.String---) | Gets or sets the output layers names(Works if export format supports layers naming, for example for Psd) |
| [setPageRasterizationOptions(VectorRasterizationOptions[] value)](#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---) | Sets the page rasterization options. |
| [setPageTitles(String[] value)](#setPageTitles-java.lang.String---) | Gets or sets the page titles. |
| [setPages(int[] value)](#setPages-int---) | Gets or sets the pages. |
| [setTimeInterval_internalized(TimeInterval value)](#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-) | Sets the time interval. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiPageOptions() {#MultiPageOptions--}
```
public MultiPageOptions()
```


Initializes a new instance of the  MultiPageOptions  class.

### MultiPageOptions(int[] pages) {#MultiPageOptions-int---}
```
public MultiPageOptions(int[] pages)
```


Initializes a new instance of the  MultiPageOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pages | int[] | The pages. |

### MultiPageOptions(int[] pages, Rectangle exportArea) {#MultiPageOptions-int---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int[] pages, Rectangle exportArea)
```


Initializes a new instance of the  MultiPageOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pages | int[] | The array of pages. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | The export area. |

### MultiPageOptions(String[] pageTitles) {#MultiPageOptions-java.lang.String---}
```
public MultiPageOptions(String[] pageTitles)
```


Initializes a new instance of the  MultiPageOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageTitles | java.lang.String[] | The page titles. |

### MultiPageOptions(String[] pageTitles, Rectangle exportArea) {#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(String[] pageTitles, Rectangle exportArea)
```


Initializes a new instance of the  MultiPageOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageTitles | java.lang.String[] | The page titles. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | The export area. |

### MultiPageOptions(IntRange[] ranges) {#MultiPageOptions-com.aspose.psd.IntRange---}
```
public MultiPageOptions(IntRange[] ranges)
```


Initializes a new instance of the  MultiPageOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | The  IntRange . |

### MultiPageOptions(IntRange[] ranges, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange[] ranges, Rectangle exportArea)
```


Initializes a new instance of the  MultiPageOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | The  IntRange . |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | The export area. |

### MultiPageOptions(IntRange range) {#MultiPageOptions-com.aspose.psd.IntRange-}
```
public MultiPageOptions(IntRange range)
```


Initializes a new instance of the  MultiPageOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | The  IntRange . |

### MultiPageOptions(IntRange range, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange range, Rectangle exportArea)
```


Initializes a new instance of the  MultiPageOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | The  IntRange . |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | The export area. |

### MultiPageOptions(int page) {#MultiPageOptions-int-}
```
public MultiPageOptions(int page)
```


Initializes a new instance of the  MultiPageOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | int | The page index. |

### MultiPageOptions(int page, Rectangle exportArea) {#MultiPageOptions-int-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int page, Rectangle exportArea)
```


Initializes a new instance of the  MultiPageOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | int | The page index. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | The export area. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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


Gets or sets the export area.

Value: The export area.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getMergeLayers() {#getMergeLayers--}
```
public final boolean getMergeLayers()
```


Gets a value indicating whether [merege layers].

Value:  true  if [merege layers]; otherwise,  false .

**Returns:**
boolean - a value indicating whether [merege layers].
### getMode() {#getMode--}
```
public int getMode()
```


Gets or sets the mode.

Value: The mode.

**Returns:**
int
### getOutputLayersNames() {#getOutputLayersNames--}
```
public String[] getOutputLayersNames()
```


Gets or sets the output layers names(Works if export format supports layers naming, for example for Psd)

Value: The output layers names.

**Returns:**
java.lang.String[]
### getPageRasterizationOptions() {#getPageRasterizationOptions--}
```
public final VectorRasterizationOptions[] getPageRasterizationOptions()
```


Gets the page rasterization options.

**Returns:**
com.aspose.psd.imageoptions.VectorRasterizationOptions[] - the page rasterization options.
### getPageTitles() {#getPageTitles--}
```
public String[] getPageTitles()
```


Gets or sets the page titles.

Value: The page titles.

**Returns:**
java.lang.String[]
### getPages() {#getPages--}
```
public int[] getPages()
```


Gets or sets the pages.

Value: The pages.

**Returns:**
int[]
### getTimeInterval_internalized() {#getTimeInterval-internalized--}
```
public final TimeInterval getTimeInterval_internalized()
```


Gets the time interval.

Value: The time interval.

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


Initializes the pages from ranges array

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | The ranges. |

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


Gets or sets the export area.

Value: The export area.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setMergeLayers(boolean value) {#setMergeLayers-boolean-}
```
public final void setMergeLayers(boolean value)
```


Sets a value indicating whether [merege layers].

Value:  true  if [merege layers]; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether [merege layers]. |

### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Gets or sets the mode.

Value: The mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setOutputLayersNames(String[] value) {#setOutputLayersNames-java.lang.String---}
```
public void setOutputLayersNames(String[] value)
```


Gets or sets the output layers names(Works if export format supports layers naming, for example for Psd)

Value: The output layers names.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setPageRasterizationOptions(VectorRasterizationOptions[] value) {#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---}
```
public final void setPageRasterizationOptions(VectorRasterizationOptions[] value)
```


Sets the page rasterization options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VectorRasterizationOptions\[\]](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) | the page rasterization options. |

### setPageTitles(String[] value) {#setPageTitles-java.lang.String---}
```
public void setPageTitles(String[] value)
```


Gets or sets the page titles.

Value: The page titles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


Gets or sets the pages.

Value: The pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### setTimeInterval_internalized(TimeInterval value) {#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-}
```
public final void setTimeInterval_internalized(TimeInterval value)
```


Sets the time interval.

Value: The time interval.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TimeInterval](../../com.aspose.psd.imageoptions/timeinterval) | the time interval. |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

