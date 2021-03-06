---
title: About the Speech SDK | Microsoft Docs
description: An overview of the SDKs available for the Speech service.
titleSuffix: "Microsoft Cognitive Services"
services: cognitive-services
author: v-jerkin
manager: noellelacharite

ms.service: cognitive-services
ms.component: speech-service
ms.topic: article
ms.date: 05/07/2018
ms.author: v-jerkin
---

# About the Speech SDK

The Speech Software Development Kit (SDK) provides your applications native access to the functions of the Speech service, making it easier to develop software. Currently, the SDK provides access to **Speech to Text** and **Speech Translation**. **Text to Speech** is currently not supported by the SDK.

The table lists the currently supported programming languages and operating systems.

|Supported operating system|Programming language|
|-|-|
|Windows|C/C++, C#|
|Linux|C/C++|
|Devices|Java\*|

\* *The Java SDK is part of the [Speech Devices SDK](speech-devices-sdk.md).*

## Get the Windows SDK

The Windows version of the Speech SDK includes 32-bit and 64-bit C/C++ client libraries as well as managed (.NET) libraries for use with C#. The SDK can be installed in Visual Studio using NuGet; simply search for "Cognitive Services Speech SDK."

## Get the Linux SDK

Make sure you have the required compiler and libraries by running the following shell commands:

```sh
sudo apt-get update
sudo apt-get install build-essential libssl1.0.0 libcurl3 libasound2
```

> [!NOTE]
> These instructions assume you're running Ubuntu 16.04 on a PC (x86 or x64). On a different Ubuntu version, or a different Linux distribution, adapt these steps to your environment.

Then, [download the SDK](https://aka.ms/csspeech/linuxbinary) and unpack the files in into a directory of your choice. This table shows the SDK folder structure.

|Path|Description|
|-|-|
|`license.md`|License|
|`third-party-notices.md`|Third-party notices|
|`include`|Header files for C and C++|
|`lib/x64`|Native x64 library for linking with your application|
|`lib/x86`|Native x86 library for linking with your application|

To create an application, copy or move the required binaries (and libraries) into your development environment, and include them as required into your build process.

## Get the Java SDK

The Java SDK is part of the [Speech Devices SDK](speech-devices-sdk.md).

## Next steps

* [Get your Speech trial subscription](https://azure.microsoft.com/try/cognitive-services/)
* [See how to recognize speech in C#](quickstart-csharp-windows.md)
