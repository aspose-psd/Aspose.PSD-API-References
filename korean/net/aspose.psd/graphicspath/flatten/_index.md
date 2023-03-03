---
title: GraphicsPath.Flatten
second_title: .NET API 참조용 Aspose.PSD
description: GraphicsPath 방법. 이 경로의 각 곡선을 일련의 연결된 선 세그먼트로 변환합니다.
type: docs
weight: 90
url: /ko/net/aspose.psd/graphicspath/flatten/
---
## Flatten() {#flatten}

이 경로의 각 곡선을 일련의 연결된 선 세그먼트로 변환합니다.

```csharp
public void Flatten()
```

### 또한보십시오

* class [GraphicsPath](../)
* 네임스페이스 [Aspose.PSD](../../graphicspath/)
* 집회 [Aspose.PSD](../../../)

---

## Flatten(Matrix) {#flatten_1}

지정된 변환을 적용한 다음 이 안에 있는 각 곡선을 변환합니다.[`GraphicsPath`](../) 연결된 라인 세그먼트의 시퀀스로.

```csharp
public void Flatten(Matrix matrix)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| matrix | Matrix | ㅏ[`Matrix`](../../matrix/) 이것을 변형시키는 것으로[`GraphicsPath`](../) 평평하기 전에. |

### 또한보십시오

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* 네임스페이스 [Aspose.PSD](../../graphicspath/)
* 집회 [Aspose.PSD](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

이 안에 있는 각 곡선을 변환합니다.[`GraphicsPath`](../) 연결된 라인 세그먼트의 시퀀스로.

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| matrix | Matrix | ㅏ[`Matrix`](../../matrix/) 이것을 변형시키는 것으로[`GraphicsPath`](../) 평평하기 전에. |
| flatness | Single | 곡선과 평평한 근사치 사이의 최대 허용 오차를 지정합니다. 0.25 값이 기본값입니다. 편평도 값을 줄이면 근사치의 선 세그먼트 수가 증가합니다. |

### 또한보십시오

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* 네임스페이스 [Aspose.PSD](../../graphicspath/)
* 집회 [Aspose.PSD](../../../)


