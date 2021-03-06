---
title: 初始化函数 （非托管 API 参考）
description: Initialize 函数执行 WMI 的初始化。
ms.date: 11/06/2017
api_name:
- Initialize
api_location:
- WMINet_Utils.dll
api_type:
- DLLExport
f1_keywords:
- Initialize
helpviewer_keywords:
- Initialize function [.NET WMI and performance counters]
topic_type:
- Reference
author: rpetrusha
ms.author: ronpet
ms.openlocfilehash: 7c71b2b6d6f102d19d30d480ee9bafcac3c204be
ms.sourcegitcommit: 9b552addadfb57fab0b9e7852ed4f1f1b8a42f8e
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62049292"
---
# <a name="initialize-function"></a>初始化函数

执行 WMI 初始化。

[!INCLUDE[internalonly-unmanaged](../../../../includes/internalonly-unmanaged.md)]

## <a name="syntax"></a>语法

```cpp
HRESULT Initialize(
   [in] boolean bAllowIManagementObjectQI
);
```

## <a name="parameters"></a>参数

`bAllowIManagementObjectQI`

[in]`true`以指示允许对 WMI 对象的 QueryInterface 调用;`false`否则为。

## <a name="return-value"></a>返回值

该函数始终返回`S_OK`(0)。

## <a name="requirements"></a>要求

**平台：** 请参阅[系统需求](../../../../docs/framework/get-started/system-requirements.md)。

**标头：** WMINet_Utils.def

**.NET Framework 版本：**[!INCLUDE[net_current_v472plus](../../../../includes/net-current-v472plus.md)]

## <a name="see-also"></a>请参阅

- [WMI 和性能计数器 （非托管 API 参考）](index.md)
