---
title: "Image.Create"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод Image. Создаёт новое изображение, используя указанные параметры создания"
type: docs
weight: 10
url: /ru/net/aspose.psd/image/create/
---
{{< psd/tize >}}
## Image.Create method

Создаёт новое изображение, используя указанные параметры создания.

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | Параметры изображения. |
| width | Int32 | Ширина. |
| height | Int32 | Высота. |

### Возвращаемое значение

Новое созданное изображение.

## Примеры

В этом примере создаётся новый файл Image в указанном месте диска, определённом свойством Source экземпляра PsdOptions. Перед созданием фактического изображения задаются несколько свойств экземпляра PsdOptions, особенно свойство Source, которое в данном случае указывает реальное расположение на диске.

```csharp
[C#]

//Создайте экземпляр PsdOptions и задайте его различные свойства
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Создайте экземпляр FileCreateSource и назначьте его в качестве Source для экземпляра PsdOptions
//Второй логический параметр определяет, является ли создаваемый файл временным
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Создайте экземпляр Image и инициализируйте его экземпляром PsdOptions, вызвав метод Create
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //выполнить некоторую обработку изображения

    // сохранить все изменения
    image.Save();
}
```

### См. также

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


