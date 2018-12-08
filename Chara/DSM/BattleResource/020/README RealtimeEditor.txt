First, copy the uasset files that will be in memory when you play into the "Originals"-folder. If you've not modded the game that would be the newest original ones.
If you have modded the game put the modded ones in there too. They will be used to recognize where the game is storing data in memory.

Open the game and the RealtimeEditor.
You must run RealtimeEditor as admin for it to have access to the game's memory.
Get into a match or training room.
Press scan.
Wait.

After a while you should see that it found BCM's and BAC's in memory.
Select the one you want to edit from the dropdown box.
Click "Select Json" and select the Json you will be working with.
The RealtimeEditor will now convert the json to uasset and load it into the game.
You can now open the json file in an editor and edit it.
Whenever the file is modified (you save in the editor) it will re-load it into the game.
No need to restart the game or even the match.
You can have multiple BAC's and BCM's open at the same time.
When you are done, click "Restore Game" and, hopefully, everything will be back to normal.

PS. This is not tested much at all and the tool is probably buggy in a lot of ways. Expect crashes.