+++
title = "Pass"
+++

GPG
---

``gpg2 --key-gen``
  Generate key.
``gpg2 -k``
  List generated key and id. We need pub key id for pass.

Usage
-----

``pass insert section/sub/profile``
  Insert pass-only record.
``pass insert -m section/sub/profile``
  Insert multi-line record. <C-D> to exit.
``pass generate -n -c section/sub/profile 12``
  Generate 12 char alpha-numeric pass and copy in clipboard.
``pass find .com``
  Search pass records by name.
``pass grep word``
  Grep pass texts.
``pass edit section/sub/profile``
  Edit with default editor.

Git
---

``pass git init``
  Initialize pass dir as git repo.
``pass git remote add origin github.com``
  Add remote repo.
``pass git push -u --all``
  Push changes.
