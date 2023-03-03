---
title: FileCreateSource.FileCreateSource
second_title: .NET API 참조용 Aspose.PSD
description: FileCreateSource 건설자. 의 새 인스턴스를 초기화합니다.FileCreateSource 클래스.
type: docs
weight: 10
url: /ko/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
## FileCreateSource(string) {#constructor}

의 새 인스턴스를 초기화합니다.[`FileCreateSource`](../) 클래스.

```csharp
public FileCreateSource(string filePath)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 생성할 파일 경로입니다. |

### 예

이 예제는 BmpOptions 인스턴스의 Source 속성에 지정된 일부 디스크 위치에 새 이미지 파일을 만듭니다. 두 번째 매개 변수가 FileCreateSource의 생성자에 전달되지 않으면 기본적으로 생성될 파일의 IsTemporal 속성이 True로 설정됩니다. IsTemporal을 True로 설정하면 실행 종료 시 디스크에 파일이 저장되지 않습니다.

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
//PsdOptions의 인스턴스를 만들고 다양한 속성을 설정합니다.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

// FileCreateSource의 인스턴스를 생성하고 PsdOptions 인스턴스의 소스로 할당합니다.
//두 번째 매개변수가 전달되지 않으면 기본적으로 파일의 IsTemporal이 True로 설정됩니다.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

//이미지 인스턴스 생성 
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // 일부 이미지 처리 수행
}
```

### 또한보십시오

* class [FileCreateSource](../)
* 네임스페이스 [Aspose.PSD.Sources](../../filecreatesource/)
* 집회 [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

의 새 인스턴스를 초기화합니다.[`FileCreateSource`](../) 클래스.

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 생성할 파일 경로입니다. |
| isTemporal | Boolean | 로 설정한 경우`진실` 생성된 파일은 일시적입니다. |

### 예

이 예에서는 PsdOptions 인스턴스의 Source 속성에 지정된 일부 디스크 위치에 새 이미지 파일을 만듭니다. 실제 이미지를 생성하기 전에 PsdOptions 인스턴스에 대한 여러 속성이 설정됩니다. 특히 이 경우 실제 디스크 위치를 나타내는 Source 속성입니다.

```csharp
[C#]

//PsdOptions의 인스턴스를 만들고 다양한 속성을 설정합니다.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

// FileCreateSource의 인스턴스를 생성하고 PsdOptions 인스턴스의 소스로 할당합니다.
//두 번째 부울 매개변수는 생성할 파일이 IsTemporal인지 여부를 결정합니다.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Create 메서드를 호출하여 Image 인스턴스를 만들고 PsdOptions 인스턴스로 초기화합니다.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // 일부 이미지 처리 수행

    // 모든 변경 사항 저장
    image.Save();
}
```

### 또한보십시오

* class [FileCreateSource](../)
* 네임스페이스 [Aspose.PSD.Sources](../../filecreatesource/)
* 집회 [Aspose.PSD](../../../)


