---
title: "FileCreateSource.FileCreateSource"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "FileCreateSource 생성자. FileCreateSource 클래스의 새 인스턴스를 초기화합니다."
type: docs
weight: 10
url: /ko/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource(string) {#constructor}

새 인스턴스를 초기화합니다 [`FileCreateSource`](../) 클래스.

```csharp
public FileCreateSource(string filePath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | String | 생성할 파일 경로. |

## 예제

이 예제는 BmpOptions 인스턴스의 Source 속성으로 지정된 디스크 위치에 새 Image 파일을 생성합니다. FileCreateSource 생성자에 두 번째 매개변수가 전달되지 않으면, 기본적으로 생성될 파일의 IsTemporal 속성이 True로 설정됩니다. IsTemporal이 True로 설정되면 실행이 끝날 때 디스크에 파일이 저장되지 않습니다.

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
//PsdOptions의 인스턴스를 생성하고 다양한 속성을 설정합니다.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//FileCreateSource의 인스턴스를 생성하고 이를 PsdOptions 인스턴스의 Source로 할당합니다.
//두 번째 매개변수가 전달되지 않으면 기본적으로 파일의 IsTemporal이 True로 설정됩니다.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

//Image 인스턴스를 생성합니다.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //이미지 처리를 수행합니다.
}
```

### 또 보기

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

새 인스턴스를 초기화합니다 [`FileCreateSource`](../) 클래스.

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | String | 생성할 파일 경로. |
| isTemporal | Boolean | `true` 로 설정하면 생성된 파일이 일시적입니다. |

## 예제

이 예제는 PsdOptions 인스턴스의 Source 속성으로 지정된 디스크 위치에 새 Image 파일을 생성합니다. 실제 이미지를 만들기 전에 PsdOptions 인스턴스의 여러 속성이 설정됩니다. 특히 이 경우 실제 디스크 위치를 가리키는 Source 속성이 설정됩니다.

```csharp
[C#]

//PsdOptions의 인스턴스를 생성하고 다양한 속성을 설정합니다.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//FileCreateSource의 인스턴스를 생성하고 이를 PsdOptions 인스턴스의 Source로 할당합니다.
//두 번째 Boolean 매개변수는 생성될 파일이 임시 파일인지 여부를 결정합니다.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Image 인스턴스를 생성하고 Create 메서드를 호출하여 PsdOptions 인스턴스로 초기화합니다.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //이미지 처리를 수행합니다.

    // 모든 변경 사항을 저장합니다.
    image.Save();
}
```

### 또 보기

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)


