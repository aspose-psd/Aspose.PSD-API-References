---
title: ClassID.ClassID
second_title: Справочник по Aspose.PSD для .NET API
description: ClassID строитель. Инициализирует новый экземплярClassID класс.
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/classid/classid/
---
## ClassID(byte[]) {#constructor}

Инициализирует новый экземпляр[`ClassID`](../) класс.

```csharp
public ClassID(byte[] classID)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| classID | Byte[] | Идентификатор класса в виде последовательности байтов. |

### Смотрите также

* class [ClassID](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* сборка [Aspose.PSD](../../../)

---

## ClassID(byte[], bool) {#constructor_1}

Инициализирует новый экземпляр[`ClassID`](../) класс.

```csharp
public ClassID(byte[] classID, bool isZeroLength)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| classID | Byte[] | Идентификатор класса в виде последовательности байтов. |
| isZeroLength | Boolean | если установлено`истинный` [нулевая длина]. Записанная длина строки равна нулю, но фактическая длина равна четырем. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | идентификатор класса равен нулю. |

### Смотрите также

* class [ClassID](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* сборка [Aspose.PSD](../../../)

---

## ClassID(int) {#constructor_2}

Инициализирует новый экземпляр[`ClassID`](../) класс.

```csharp
public ClassID(int classID)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| classID | Int32 | Идентификатор класса. |

### Смотрите также

* class [ClassID](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* сборка [Aspose.PSD](../../../)

---

## ClassID(uint) {#constructor_5}

Инициализирует новый экземпляр[`ClassID`](../) класс.

```csharp
public ClassID(uint classID)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| classID | UInt32 | Идентификатор класса. |

### Смотрите также

* class [ClassID](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* сборка [Aspose.PSD](../../../)

---

## ClassID(string, bool) {#constructor_4}

Инициализирует новый экземпляр[`ClassID`](../) класс.

```csharp
public ClassID(string classID, bool isZeroLength)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| classID | String | Идентификатор класса в кодировке ASCII. |
| isZeroLength | Boolean | если установлено`истинный` [нулевая длина]. |

### Примеры

Этот пример демонстрирует, что слой, импортированный из изображения, преобразуется в слой смарт-объекта, а сохраненный файл PSD является правильным.

```csharp
[C#]

// Проверяет, что слой, импортированный из изображения, преобразован в слой смарт-объекта, а сохраненный PSD-файл правильный.

string outputFilePath = outputFolder + Path.DirectorySeparatorChar + "layerTest2.psd";
string outputPngFilePath = Path.ChangeExtension(outputFilePath, ".png");
using (PsdImage image = (PsdImage)Image.Load(baseFolder + Path.DirectorySeparatorChar + "layerTest1.psd"))
{
    string layerFilePath = baseFolder + Path.DirectorySeparatorChar + "picture.jpg";
    using (var stream = new FileStream(layerFilePath, FileMode.Open))
    {
        Layer layer = null;
        try
        {
            layer = new Layer(stream);
            image.AddLayer(layer);
        }
        catch (Exception)
        {
            if (layer != null)
            {
                layer.Dispose();
            }

            throw;
        }

        var layer2 = image.Layers[2];
        var layer3 = image.SmartObjectProvider.ConvertToSmartObject(image.Layers.Length - 1);
        var bounds = layer3.Bounds;
        layer3.Left = (image.Width - layer3.Width) / 2;
        layer3.Top = layer2.Top;
        layer3.Right = layer3.Left + bounds.Width;
        layer3.Bottom = layer3.Top + bounds.Height;

        image.Save(outputFilePath);
        image.Save(outputPngFilePath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Смотрите также

* class [ClassID](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* сборка [Aspose.PSD](../../../)

---

## ClassID(string) {#constructor_3}

Инициализирует новый экземпляр[`ClassID`](../) класс.

```csharp
public ClassID(string classID)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| classID | String | Идентификатор класса в кодировке ASCII. |

### Смотрите также

* class [ClassID](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* сборка [Aspose.PSD](../../../)


