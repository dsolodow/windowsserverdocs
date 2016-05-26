---
title: Bitsadmin geterrorcount
ms.custom: na
ms.prod: windows-server-2012
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 8840ae78-52b0-4c7e-b592-0547359a237e
author: britw
---
# Bitsadmin geterrorcount
Retrieves a count of the number of times the specified job generated a transient error.  
  
## Syntax  
  
```  
bitsadmin /GetErrorCount <Job>  
```  
  
## Parameters  
  
|Parameter|Description|  
|-------------|---------------|  
|Job|The job's display name or GUID|  
  
## <a name="BKMK_examples"></a>Examples  
The following example retrieves error count information for the job named *myDownloadJob*.  
  
```  
C:\>bitsadmin /GetErrorCount myDownloadJob  
```  
  
## Additional references  
[Command-Line Syntax Key](Command-Line-Syntax-Key.md)  
  
