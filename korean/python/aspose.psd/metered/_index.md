---
title: "Metered 클래스"
type: docs
weight: 3030
url: /ko/python-net/aspose.psd/metered/
---

**Summary:** Provides methods to set metered key.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Metered

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [Metered()](#Metered__1) | Metered 클래스의 새 인스턴스를 초기화합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | 소비 크레딧을 가져옵니다 |
| [get_consumption_quantity()](#get_consumption_quantity__2) | 소비 파일 크기를 가져옵니다 |
| [get_product_name()](#get_product_name__3) | 제품 이름을 가져옵니다. |
| [is_metered_licensed()](#is_metered_licensed__4) | Metered가 라이선스가 있는지 확인합니다 |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_5) | Metered 공개 및 개인 키를 설정합니다.<br/>            메터드 라이선스를 구매한 경우, 애플리케이션을 시작할 때 이 API를 호출해야 하며, 일반적으로 이것만으로 충분합니다. <br/>            그러나 소비 데이터를 업로드하는 데 계속 실패하고 24시간을 초과하면 라이선스가 평가 상태로 설정됩니다, <br/>            이러한 경우를 방지하려면 라이선스 상태를 정기적으로 확인하고, 평가 상태인 경우 다시 이 API를 호출하십시오. |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

Metered 클래스의 새 인스턴스를 초기화합니다.

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

소비 크레딧을 가져옵니다

**Returns**

| 유형 | 설명 |
| :- | :- |
| decimal | 소비량 |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

소비 파일 크기를 가져옵니다

**Returns**

| 유형 | 설명 |
| :- | :- |
| decimal | 소비량 |


### Method: get_product_name() {#get_product_name__3}


```
 get_product_name() 
```

제품 이름을 가져옵니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| 문자열 | 라이선스가 적용된 제품 이름 |


### Method: is_metered_licensed()  [static] {#is_metered_licensed__4}


```
 is_metered_licensed() 
```

Metered가 라이선스가 있는지 확인합니다

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 참 또는 거짓 |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_5}


```
 set_metered_key(public_key, private_key) 
```

Metered 공개 및 개인 키를 설정합니다.<br/>            메터드 라이선스를 구매한 경우, 애플리케이션을 시작할 때 이 API를 호출해야 하며, 일반적으로 이것만으로 충분합니다. <br/>            그러나 소비 데이터를 업로드하는 데 계속 실패하고 24시간을 초과하면 라이선스가 평가 상태로 설정됩니다, <br/>            이러한 경우를 방지하려면 라이선스 상태를 정기적으로 확인하고, 평가 상태인 경우 다시 이 API를 호출하십시오.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| public_key | 문자열 | 공개 키 |
| private_key | 문자열 | 개인 키 |

