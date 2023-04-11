---
layout: single
title: Projects
permalink: /projects/
author_profile: true
classes: wide
toc: false
---

I love free software and contribute to them when i can.
Most of my projects are involve powershell, and or csharp. You will find some of them below.



## Open Source PowerShell projects

| Links         |         Description                                                      |
| --------         | ------------------------------------------------------------ |
| [Github](https://github.com/v2kiran/PSAlphaFS){: .btn .btn--inverse} [PSgallery](https://www.powershellgallery.com/packages/PSAlphaFS/2.0.0.1){: .btn .btn--primary}    | **PSAlphaFS** is a wrapper for the [ALphaFS](https://alphafs.alphaleonis.com/) .NET library, providing a small subset of functions that overcome the [MAX_PATH](https://learn.microsoft.com/en-us/windows/win32/fileio/maximum-file-path-limitation?tabs=registry) limitation of 260 characters of the windows filesystem.  This module is intended to work on windows alone because Linux and Unix systems do not have the 260 character length limitation.    **Note:** > PowerShell Version 7 supports long paths natively so if you have PS v7 installed you do not need this module.            |
| [Github](https://github.com/v2kiran/PSLiteDB){: .btn .btn--inverse} [PSgallery](https://www.powershellgallery.com/packages/PSLiteDB/2.1.0){: .btn .btn--primary}     |  **PSLiteDB** is a PowerShell wrapper for LiteDB which is a [nosql](https://en.wikipedia.org/wiki/NoSQL) singlefile datastore just like [SQLite](https://www.sqlite.org/index.html) SQLite PSLiteDB has been compiled against the [.NET Standard 2](https://learn.microsoft.com/en-us/dotnet/standard/net-standard?tabs=net-standard-1-0) Standard which means you can use this module on windows with both Windows PowerShell 5 and above and PowerShell 7 or above on linux. The advantage of using a nosql database is that you do not need to create tables with any particular schema. Columns in tables can be added or removed on the fly.                               |
| [Github](https://github.com/v2kiran/PSSecret){: .btn .btn--inverse} [PSgallery](https://www.powershellgallery.com/packages/PSSecret/1.0.0){: .btn .btn--primary}  |  **PSSecret** acts as your personal secure vault where you can encrypt, store & retrive data securely from the registry. You can store the following types of information : Strings,Credentials,Hashtables,Objects. PSSecret uses the [Crytographic Message Syntax](https://en.wikipedia.org/wiki/Cryptographic_Message_Syntax) introduced in PowerShell V5 which use the [public key infrastructure](https://en.wikipedia.org/wiki/Public_key_infrastructure) PKI to encrypt data. The encrypted data cannot be decrypted by any other user on any other computer than the one where it
