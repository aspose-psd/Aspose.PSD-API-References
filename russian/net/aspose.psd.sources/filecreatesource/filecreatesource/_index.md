---
title: "FileCreateSource.FileCreateSource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Конструктор FileCreateSource. Инициализирует новый экземпляр класса FileCreateSource"
type: docs
weight: 10
url: /ru/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource(string) {#constructor}

Инициализирует новый экземпляр класса [`FileCreateSource`](../).

```csharp
public FileCreateSource(string filePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу для создания. |

## Примеры

Этот пример создает новый файл Image в некотором месте диска, указанном свойством Source экземпляра BmpOptions. Если второй параметр не передан конструктору FileCreateSource, то по умолчанию у создаваемого файла свойство IsTemporal будет установлено в True. При установленном IsTemporal в True файл не будет сохранён на диске по завершении выполнения.

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
//Создаёт экземпляр PsdOptions и задаёт его различные свойства.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Создайте экземпляр FileCreateSource и назначьте его в качестве Source для экземпляра PsdOptions
//Если второй параметр не передан, то по умолчанию у файла свойство IsTemporal будет установлено в True.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

//Создаёт экземпляр Image
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //выполнить некоторую обработку изображения
}
```

### См. также

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

Инициализирует новый экземпляр класса [`FileCreateSource`](../).

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу для создания. |
| isTemporal | Boolean | Если установлено в `true`, созданный файл будет временным. |

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

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)


