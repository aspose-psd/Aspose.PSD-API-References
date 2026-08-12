---
title: "ClassID.ClassID"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Конструктор ClassID. Инициализирует новый экземпляр класса ClassID"
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/classid/classid/
---
{{< psd/tize >}}
## ClassID(byte[]) {#constructor}

Инициализирует новый экземпляр класса [`ClassID`](../).

```csharp
public ClassID(byte[] classID)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| classID | Byte[] | Идентификатор класса в виде последовательности байтов. |

### См. также

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(byte[], bool) {#constructor_1}

Инициализирует новый экземпляр класса [`ClassID`](../).

```csharp
public ClassID(byte[] classID, bool isZeroLength)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| classID | Byte[] | Идентификатор класса в виде последовательности байтов. |
| isZeroLength | Boolean | если установлено `true` [is zero length]. Записанная длина строки равна нулю, но фактическая — четыре. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | classID равен null. |

### См. также

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(int) {#constructor_2}

Инициализирует новый экземпляр класса [`ClassID`](../).

```csharp
public ClassID(int classID)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| classID | Int32 | Идентификатор класса. |

### См. также

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(uint) {#constructor_5}

Инициализирует новый экземпляр класса [`ClassID`](../).

```csharp
public ClassID(uint classID)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| classID | UInt32 | Идентификатор класса. |

### См. также

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(string, bool) {#constructor_4}

Инициализирует новый экземпляр класса [`ClassID`](../).

```csharp
public ClassID(string classID, bool isZeroLength)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| classID | String | Идентификатор класса в кодировке ASCII. |
| isZeroLength | Boolean | если установлено `true` [is zero length]. |

## Примеры

Этот пример демонстрирует, что слой, импортированный из изображения, преобразуется в слой смарт‑объекта, и сохранённый файл PSD корректен.

```csharp
[C#]

// Тестирует, что слой, импортированный из изображения, преобразуется в слой смарт‑объекта, и сохранённый файл PSD корректен.

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

### См. также

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(string) {#constructor_3}

Инициализирует новый экземпляр класса [`ClassID`](../).

```csharp
public ClassID(string classID)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| classID | String | Идентификатор класса в кодировке ASCII. |

### См. также

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


