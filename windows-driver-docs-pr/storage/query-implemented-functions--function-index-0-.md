---
title: Query Implemented Functions (Function Index 0)
description: This function returns the functions supported by this interface version.
ms.assetid: AFF735D7-BB3F-4532-8BF4-F616C081921C
---

# Query Implemented Functions (Function Index 0)


This function returns the functions supported by this interface version. Function 0 of every \_DSM is a query function that returns the set of supported function indexes, and is always required. For the definition of Function 0, see section 9.14.1, "\_DSM (Device Specific Method)" in the [ACPI 6.0 specification](http://www.acpi.info).

## <span id="Arguments__ARG_3_"></span><span id="arguments__arg_3_"></span><span id="ARGUMENTS__ARG_3_"></span>Arguments (ARG 3)


None.

## <span id="Returns"></span><span id="returns"></span><span id="RETURNS"></span>Returns


This function returns an ACPI Buffer containing the following byte values in order: 0xFF, 0xFF, 0xFF, & 0xFF.

## <span id="related_topics"></span>Related topics


[\_DSM Interface for Byte Addressable Energy Backed Function Class (Function Interface 1)](-dsm-interface-for-byte-addressable-energy-backed-function-class--function-interface-1-.md)

 

 





