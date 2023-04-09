---
layout: single
title: Projects
permalink: /projects/
author_profile: true
toc: true
---

I love free software and I do a fair share of work on free software projects.
Most of my projects are in the realms of Clojure, Ruby and Emacs and aim to
help software engineers be more productive.

My projects are spread over several GitHub accounts:

* [Personal Projects](https://github.com/bbatsov)
* [RuboCop HQ](https://github.com/rubocop)
* [Clojure Emacs](https://github.com/clojure-emacs)
* [nREPL](https://github.com/nrepl)



## Tables

| Github         | PSGallery |        Description                                                      |
| --------         | ------ | ------------------------------------------------------------ |
| [PSAlphaFS](https://github.com/v2kiran/PSAlphaFS){: .btn .btn--primary}    | [PSgallery](https://www.powershellgallery.com/packages/PSAlphaFS/2.0.0.1){: .btn .btn--info}     | PSAlphaFS is a wrapper for the ALphaFS .NET library, providing a small subset of functions that overcome the MAX_PATH limitation of 260 characters of the windows filesystem. <p>This module is intended to work on windows alone because Linux and Unix systems do not have the 260 character length limitation.</p> **Note:** PowerShell Version 7 supports long paths natively so if you have PS v7 installed you do not need this module. [Primary Button](#){: .btn .btn--primary}           |
| [Jane Doe](#)    | $100K  | For all the blogging she does.                               |
| [Fred Bloggs](#) | $100M  | Pictures are worth a thousand words, right? So Jane × 1,000. |
| [Jane Bloggs](#) | $100B  | With hair like that?! Enough said.                           |


<h2>Open Source</h2>
<dl class="row">
    <dt class="col-sm-3">PSAlphaFS</dt>
    <dd class="col-sm-9">
        <p>PSAlphaFS is a wrapper for the <a id="anchorid" href="https://alphafs.alphaleonis.com/">ALphaFS .NET library</a>, providing a small subset of functions
            that overcome the <a id="anchorid" href="https://docs.microsoft.com/en-us/windows/win32/fileio/maximum-file-path-limitation?tabs=cmd">MAX_PATH limitation of 260 characters</a> of the windows filesystem.
        </p>
        <p>
            This module is intended to work on windows alone because Linux and Unix systems do not have the 260
            character length limitation.
        </p>
        <p>
            <strong>Note: </strong>PowerShell Version 7 supports long paths natively so if you have PS v7
            installed you do not need this module.
        </p>
        <p>
            <a type="button" class="btn btn-secondary" style="background-color:#485fc7" href="https://github.com/v2kiran/PSAlphaFS">
                <span>
                    <i class="fab fa-github" style="color:#fff"></i>
                </span>
                <span style="color:white;">GitHub</span>
            </a>
            <a className="button is-primary" href="https://www.powershellgallery.com/packages/PSAlphaFS/2.0.0.1">
            <span>
              <i class="fas fa-terminal"></i>
            </span>
            <span>PSGallery</span>
          </a>
        </p>
    </dd>
    <dt class="col-sm-3">PSLiteDB</dt>
    <dd class="col-sm-9">
        <p>   PSLiteDB is a PowerShell wrapper for LiteDB which is a
              <a id="anchorid" href="https://en.wikipedia.org/wiki/NoSQL">noSQL</a> singlefile datastore just like <a id="anchorid" href="https://www.sqlite.org/index.html">SQLite</a>.
              PSLiteDB has been compiled against the <a id="anchorid" href="https://docs.microsoft.com/en-us/dotnet/standard/net-standard">.NET Standard 2</a> which means
              you can use this module on windows with both Windows PowerShell 5 and above
              and PowerShell 7 or above on linux.
        <p>
              The advantage of using a nosql database is that you do not need to
              create tables with any particular schema. Columns in tables can be
              added or removed on the fly.
        <p>
            <a type="button" class="btn btn-secondary" style="background-color:#485fc7" href="https://github.com/v2kiran/PSLiteDB">
                <span>
                    <i class="fab fa-github" style="color:#fff"></i>
                </span>
                <span style="color:white;">GitHub</span>
            </a>
            <a className="button is-primary" href="https://www.powershellgallery.com/packages/PSLiteDB/2.1.0">
            <span>
              <i class="fas fa-terminal"></i>
            </span>
            <span>PSGallery</span>
          </a>
        </p>
    </dd>
    <dt class="col-sm-3">PSSecret</dt>
    <dd class="col-sm-9">
        <p> PSSecret acts as your personal secure vault where you can
            <strong>
              encrypt, store & retrive data securely from the registry.
            </strong>
            You can store the following types of information :
            Strings,Credentials,Hashtables,Objects.
        <p>
              PSSecret uses the <a id="anchorid" href="https://en.wikipedia.org/wiki/Cryptographic_Message_Syntax">Crytographic Message Syntax</a>
              introduced in PowerShell V5 which use the
              <a id="anchorid" href="https://en.wikipedia.org/wiki/Public_key_infrastructure">public key infrastructure PKI</a>
              to encrypt data. The encrypted data cannot be decrypted by any other
              user on any other computer than the one where it was encrypted.
        <p>
            <a type="button" class="btn btn-secondary" style="background-color:#485fc7" href="https://github.com/v2kiran/PSSecret">
                <span>
                    <i class="fab fa-github" style="color:#fff"></i>
                </span>
                <span style="color:white;">GitHub</span>
            </a>
            <a class="btn--info" href="https://www.powershellgallery.com/packages/PSSecret/1.0.0">
            <span>
              <i class="fas fa-terminal"></i>
            </span>
            <span>PSGallery</span>
          </a>
        </p>
    </dd>
</dl>