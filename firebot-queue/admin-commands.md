# Admin commands

Following commands only accessible to streamer and/or moderators by default, these are also hidden from the !commands list



STREAMER ONLY:&#x20;

!queue key "room-pass-code" - changes the passcode used that gets sent to the invited players via whisper. Use without quotes. NOTE: DO NOT SEND THIS MESSAGE IN YOUR CHAT, WHISPER THIS TO THE BOT. Otherwise everyone will see your code, duh.

Example: _!queue key peepee-poopoo_



**!queue pick \[number]** - selects the designated amount of people from the top of the list, sends them the room code via Twitch whisper and deletes them from the line. Also sends a chat message saying how many people are selected and dinkdonks.

**Example: **_**!queue pick 69**_ (sends the code for 69 people in your list)



STREAMER AND MODERATORS:

**!queue open** - Makes the !queue command active, opens the queue for viewers and sends a chat message with simple instructions for viewers.



**!queue close** - Closes the queue, sends a chat message, empties the queue completely and disables the !queue command until it's opened again.




