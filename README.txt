This is an edit of a HTML-5 overlay by @D3Vlicious (https://twitter.com/D3Vlicious) utilizing StreamControl by farpenoodle at https://github.com/farpenoodle/StreamControl made for the P4AUPC community.
This edit is primarily used for streaming P4AU tournaments and events using OBS, and houses a twitch chat bot executable that can be configured in the .env file of the main folder
Of the edits made, jstween animations were ported over to anime.js for more concise code, and the html layouts that were provided were reworked. Currently, StreamControl.exe is still included for scoreboard control but this will be incorporated into the "P4PC Match Screen Control.exe" file in a later iteration.
If you would like to fork this repository and make your own edits, feel free to do so.
In the future I plan on making a more general overlay akin to the original overlay for use in other games, so stay tuned.

---

StreamControl setup instructions (Borrowed from https://github.com/farpenoodle/StreamControl):
1. Place StreamControl.exe in it's own directory (shouldn't actually matter where)
2. Run it. It should autodetect your XSplit installation if you installed XSplit to the default location. If not, please click configure and set it there.
3. Load XSplit and set up the scene. Add the SWF overlays you require.
4. Done.

Report bugs at http://github.com/farpenoodle/StreamControl/issues

GNU/Linux build instructions:

Install QtCreator and Qt5-script.
In the same directory as StreamControl.pro run "qmake && make".

---

FuukaBot setup instructions:
1. Set values in the .env file located in the root directory using notepad.
2. Launch FuukaBot

