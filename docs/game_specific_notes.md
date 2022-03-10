# Game specific notes
For best viewing experience, please use a markdown viewer that supports Github or Gitlab Flavored Markdown syntax.

This document is for detailed game specific notes, if any.

## Overview

|       Name      | Game ID | Latest supported version | Latest supported option | Actively supported | Requires patch |
| ---             | ---     | ---                      | ---                     | ---                | ---            |
|Chunithm         |SDBT     |Paradise Lost             |A032                     |Yes                 |Yes (Paradise)  |
|Maimai DX        |SDEZ     |Universe                  |D051                     |Yes                 |Yes             |
|O.N.G.E.K.I      |SDDT     |Bright                    |A016                     |Yes                 |Yes             |
|Maimai           |SDEY     |Finale                    |?                        |No                  |?               |
|Project DIVA AFT |SBZV     |?                         |?                        |No                  |?               |
|Initial D Zero   |SDDF     |?                         |?                        |No                  |?               |

* Actively supported: if yes, it will likely receive future bug fixes and new version support.
* Requires patch: if yes, game needs to be patched in order to work with Aqua server.
* Latest supported option: this may or may not include all options up to latest.

## Chunithm
Only JP variant is supported.

### Required patches
This section only applies to Paradise and up.
* No TLS
* No encryption

### Additional notes
* Workaround for profile version mismatch is implemented, but not recommended.

## Maimai DX
Only JP variant is supported.

### Required patches
* No TLS
* No certificate pinning
* No URI obfuscation
* No encryption

### Non-working features
* KOP related
* User portrait
* DX Pass
* Tournament mode

### Additional notes
* From version 0.0.25, Aqua reports endpoint as `http://ALLNET_HOST/`. The final endpoint that game connects must be `http://ALLNET_HOST/Maimai2Servlet/`.

## O.N.G.E.K.I

### Required patches
* No TLS
* No certificate pinning
* No URI obfuscation
* No encryption

### Non-working features
* KOP related
* Physical cards