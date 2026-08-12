---
title: "Image.RotateFlip"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод Image. Поворачивает, отражает или одновременно поворачивает и отражает изображение"
type: docs
weight: 230
url: /ru/net/aspose.psd/image/rotateflip/
---
{{< psd/tize >}}
## Image.RotateFlip method

Поворачивает, отражает или одновременно поворачивает и отражает изображение.

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Тип поворота и отражения. |

## Примеры

Этот пример демонстрирует использование операции Rotate для изображения. Пример загружает существующий файл изображения из некоторого расположения на диске и выполняет операцию Rotate над изображением в соответствии со значением перечисления Aspose.PSD.RotateFlipType

```csharp
[C#]

//Создать экземпляр класса image и инициализировать его существующим файлом изображения через путь к файлу
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Повернуть изображение на 180 градусов вокруг оси X
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // Сохраните все изменения.
    image.Save();
}
```

### См. также

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


