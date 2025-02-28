---
title: downloads.FilenameConflictAction
slug: Mozilla/Add-ons/WebExtensions/API/downloads/FilenameConflictAction
translation_of: Mozilla/Add-ons/WebExtensions/API/downloads/FilenameConflictAction
---

{{AddonSidebar()}}

Le type `FilenameConflictAction` de l'API {{WebExtAPIRef("downloads")}} spécifie que faire si le nom d'un fichier téléchargé est en conflit avec un fichier existant.

Ce type définit les valeurs pouvant être utilisées pour la propriété `conflictAction` du paramètre d'`options` {{WebExtAPIRef("downloads.download")}}.

## Type

Les valeurs de ce type sont des chaînes. Les valeurs possibles sont :

- `"uniquify"`
  - : Le navigateur modifiera le nom de fichier pour le rendre unique.
- `"overwrite"`
  - : Le navigateur écrase l'ancien fichier avec le fichier nouvellement téléchargé.
- `"prompt"`
  - : Le navigateur invitera l'utilisateur, lui demandant de choisir s'il souhaite l'uniquifier ou l'écraser.

## Compatibilité des navigateurs

{{Compat}}

{{WebExtExamples}}

> **Note :**
>
> Cette API est basée sur l'API Chromium [`chrome.downloads`](https://developer.chrome.com/extensions/downloads).
>
> Les données de compatibilité relatives à Microsoft Edge sont fournies par Microsoft Corporation et incluses ici sous la licence Creative Commons Attribution 3.0 pour les États-Unis.

<!--
// Copyright 2015 The Chromium Authors. All rights reserved.
//
// Redistribution and use in source and binary forms, with or without
// modification, are permitted provided that the following conditions are
// met:
//
//    * Redistributions of source code must retain the above copyright
// notice, this list of conditions and the following disclaimer.
//    * Redistributions in binary form must reproduce the above
// copyright notice, this list of conditions and the following disclaimer
// in the documentation and/or other materials provided with the
// distribution.
//    * Neither the name of Google Inc. nor the names of its
// contributors may be used to endorse or promote products derived from
// this software without specific prior written permission.
//
// THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
// "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
// LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
// A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT
// OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
// SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT
// LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
// DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
// THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
// (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
// OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
-->
