---
description: passcode.txt is referenced in three different places
---

# passcode.txt

**!queue key**

Passcode.txt will be referenced here the first time, to adjust:

* Go to Edit Command -> Effects
* Write To File -> Edit Effect
* Press Choose File, browse to your new folder location and locate your passcode.txt

**!queue**&#x20;

This command references the passcode.txt on sending the room code via Whisper to your chat members

* Go to Edit Command -> Subcommands -> "pick \[number]"
* Go to Effects -> Loop Effect -> Edit Effect -> Effects -> Chat
* Change the path in the highlighted part
* Remember to save!

<figure><img src="../../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

**!queue close**

This command empties the passcode.txt

* Go to Edit Command -> Subcommands -> "Close"
* Go to Effects -> Write to File (double check you're editing the correct Effect!)
* Press Choose File, browse to your new folder location and locate your passcode.txt

