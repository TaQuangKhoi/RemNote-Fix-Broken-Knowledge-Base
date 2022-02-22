# RemNote Fix Broken Knowledge Base
I think I can use Python
Error Message:
```json
Long write guarantees:
[
  {
    "isCurrentlyStuck": false,
    "longWriteTriggered": true,
    "_id": 0,
    "debugName": "merge",
    "args": [
      {
        "_id": "MrRk9GajDWrjzXkBt",
        "key": [
          "Edit Later"
        ],
        "owner": "my-remnote-user-id",
        "children": [
          "QsyaDjnyFaHaXXcRH",
          "ovv7PgBkMd6zrDiv9"
        ],
        "subBlocks": [
          "QsyaDjnyFaHaXXcRH"
        ],
        "portalsIn": [],
        "createdAt": 1645320278475,
        "n": 1,
        "u": 1645320278484,
        "parent": null,
        "rcrt": "e",
        "typeChildren": [
          "QsyaDjnyFaHaXXcRH"
        ],
        "tcsp": [
          "QsyaDjnyFaHaXXcRH"
        ],
        "s": 1645320281866
      },
      false,
      null,
      null,
      true
    ]bash
```
Solution: Delete this rem with Back-end API
