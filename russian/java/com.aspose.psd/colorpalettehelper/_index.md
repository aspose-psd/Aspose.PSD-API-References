---
title: "ColorPaletteHelper"
second_title: "Aspose.PSD for Java API Справочник"
description: "Вспомогательный класс для манипуляций с цветовыми палитрами."
type: docs
weight: 28
url: /ru/java/com.aspose.psd/colorpalettehelper/
---

**Inheritance:**
java.lang.Object
```
public final class ColorPaletteHelper
```

Вспомогательный класс для манипуляций с цветовыми палитрами.
## Методы

| Метод | Описание |
| --- | --- |
| [create4Bit()](#create4Bit--) | Создаёт 4-битную цветовую палитру. |
| [create4BitGrayscale(boolean minIsWhite)](#create4BitGrayscale-boolean-) | Создаёт 4-битную палитру градаций серого. |
| [create8Bit()](#create8Bit--) | Создаёт 8-битную цветовую палитру. |
| [create8BitGrayscale(boolean minIsWhite)](#create8BitGrayscale-boolean-) | Создаёт 8-битную палитру градаций серого. |
| [createMonochrome()](#createMonochrome--) | Создаёт монохромную цветовую палитру, содержащую только 2 цвета. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-) | Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения нет палитры. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-) | Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения нет палитры. |
| [getCloseImagePalette(RasterImage image, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-int-) | Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения нет палитры. |
| [getDownscalePalette(RasterImage image)](#getDownscalePalette-com.aspose.psd.RasterImage-) | Получить 256‑цветную палитру, составленную из старших битов исходных цветовых значений изображения. |
| [getUniformColorPalette(RasterImage image)](#getUniformColorPalette-com.aspose.psd.RasterImage-) | Получить единообразную 256‑цветную палитру. |
| [hasTransparentColors(IColorPalette palette)](#hasTransparentColors-com.aspose.psd.IColorPalette-) | Определяет, содержит ли указанная палитра прозрачные цвета. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create4Bit() {#create4Bit--}
```
public static IColorPalette create4Bit()
```


Создаёт 4-битную цветовую палитру.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit color palette.
### create4BitGrayscale(boolean minIsWhite) {#create4BitGrayscale-boolean-}
```
public static IColorPalette create4BitGrayscale(boolean minIsWhite)
```


Создаёт 4-битную палитру градаций серого.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| minIsWhite | boolean | если установить в  true  палитра начинается с белого цвета, иначе она начинается с черного цвета. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit grayscale palette.
### create8Bit() {#create8Bit--}
```
public static IColorPalette create8Bit()
```


Создаёт 8-битную цветовую палитру.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit color palette.
### create8BitGrayscale(boolean minIsWhite) {#create8BitGrayscale-boolean-}
```
public static IColorPalette create8BitGrayscale(boolean minIsWhite)
```


Создаёт 8-битную палитру градаций серого.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| minIsWhite | boolean | если установить в  true  палитра начинается с белого цвета, иначе она начинается с черного цвета. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit grayscale palette.
### createMonochrome() {#createMonochrome--}
```
public static IColorPalette createMonochrome()
```


Создаёт монохромную цветовую палитру, содержащую только 2 цвета.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Color palette for monochrome images.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
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
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount) {#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)
```


Получает цветовую палитру из растрового изображения (палитризует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Растровое изображение. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | Границы целевого изображения. |
| entriesCount | int | Желаемое количество записей. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette) {#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)
```


Получает цветовую палитру из растрового изображения (палитризует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Растровое изображение. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | Границы целевого изображения. |
| entriesCount | int | Желаемое количество записей. |
| useImagePalette | boolean | Если установлено, будет использовать собственную палитру изображения, если она доступна |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, int entriesCount) {#getCloseImagePalette-com.aspose.psd.RasterImage-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount)
```


Получает цветовую палитру из растрового изображения (палитризует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Растровое изображение. |
| entriesCount | int | Желаемое количество записей. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getDownscalePalette(RasterImage image) {#getDownscalePalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getDownscalePalette(RasterImage image)
```


Получить 256‑цветную палитру, составленную из старших битов исходных цветовых значений изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Изображение. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### getUniformColorPalette(RasterImage image) {#getUniformColorPalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getUniformColorPalette(RasterImage image)
```


Получить единообразную 256‑цветную палитру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Изображение. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### hasTransparentColors(IColorPalette palette) {#hasTransparentColors-com.aspose.psd.IColorPalette-}
```
public static boolean hasTransparentColors(IColorPalette palette)
```


Определяет, содержит ли указанная палитра прозрачные цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Палитра. |

**Returns:**
логический -  true  если указанная палитра содержит прозрачные цвета; иначе  false .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

