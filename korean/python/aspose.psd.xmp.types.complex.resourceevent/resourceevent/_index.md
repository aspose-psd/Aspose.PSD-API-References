---
title: "ResourceEvent 클래스"
type: docs
weight: 10
url: /ko/python-net/aspose.psd.xmp.types.complex.resourceevent/resourceevent/
---

**Summary:** Containing dimensions for a drawn object.

**Module:** [aspose.psd.xmp.types.complex.resourceevent](/psd/python-net/aspose.psd.xmp.types.complex.resourceevent/)

**Full Name:** aspose.psd.xmp.types.complex.resourceevent.ResourceEvent

**Inheritance:** IXmpType, ComplexTypeBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [ResourceEvent()](#ResourceEvent__1) | ResourceEvent 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| 동작 | 문자열 | r/w | 동작을 가져오거나 설정합니다. |
| action_date | datetime | r/w | 동작 날짜를 가져오거나 설정합니다. |
| changed | 문자열 | r/w | 이전 이벤트 기록 이후 변경된 리소스 부분들의 세미콜론 구분 목록을 가져오거나 설정합니다. |
| instance_id | Guid | r/w | xmpMM:InstanceId의 값을 가져오거나 설정합니다. |
| namespace_uri | 문자열 | r | 기본 네임스페이스 URI를 가져옵니다. |
| 매개변수 | 문자열 | r/w | 동작에 대한 추가 설명을 가져오거나 설정합니다. |
| 접두사 | 문자열 | r | 접두사를 가져옵니다. |
| sofware_agent_name | 문자열 | r/w | 소프트웨어 에이전트 이름을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_xmp_representation()](#get_xmp_representation__1) | XMP 형식의 문자열 포함 값을 가져옵니다. |


### Constructor: ResourceEvent() {#ResourceEvent__1}


```
 ResourceEvent() 
```

ResourceEvent 클래스의 새 인스턴스를 초기화합니다.

### Method: get_xmp_representation() {#get_xmp_representation__1}


```
 get_xmp_representation() 
```

XMP 형식의 문자열 포함 값을 가져옵니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| 문자열 | XMP 형식의 문자열 포함 값을 반환합니다. |


