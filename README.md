# Kehai Companions

Kehai Companions puts a character on your desktop who talks with you, remembers you between
chats, and (if you let them) can see what is on your screen. It runs on your own PC: with the
models it downloads for you, your chats, memories and screenshots never leave it.

**[Download the latest version](https://github.com/WrenLoft/kehai-releases/releases/latest)**

Need help, want to share your OCs or animation configs? Join the
**[WrenLoft Discord](https://discord.gg/z4fPdmsbuQ)**.

Kehai is for adults (18 or older). It can run language models that are not filtered, and can
work with games and character cards made for adults.

## What you need

- Windows 10 (version 2004 or later) or Windows 11.
- A graphics card helps a lot. The smallest language model needs about 5.5 GB of video memory
  and even runs without a graphics card (slowly); bigger, smarter ones need 7.5 to 22 GB. The app
  suggests one that fits your PC.
- Optional: Koikatsu or Koikatsu Sunshine (with BepInEx, which any modded install has) if you
  want Koikatsu characters as bodies.

## Install

1. Download `KehaiCompanions_<version>_x64-setup.exe` from the
   [releases page](https://github.com/WrenLoft/kehai-releases/releases/latest) and run it.
   No administrator rights are needed.
2. Read and accept the license agreement.
3. It installs into a "Kehai Companions" folder in your user folder (you can pick another).
4. Tick "Run" on the last page, or start it from the Start menu or the desktop shortcut.

Windows may say "Windows protected your PC" because the installer isn't signed with a paid
certificate yet. Click **More info**, then **Run anyway**.

Kehai keeps everything you make (characters, chats, memories, settings) in a `data` folder next
to the program. Settings > Help & about > Your data opens it.

## Your first launch

Aero, the built-in character, appears on your desktop and walks you through getting started in
a small window beside them. You can go back a step at any time, and if you close the app halfway,
it picks up where you left off.

1. **Your name.** What Aero should call you (and your pronouns).
2. **A body.** VRM (3D models like Aero; nothing else to install) or Koikatsu (point the app at
   the folder with `CharaStudio.exe`). You can change this later.
3. **Character cards.** If you have Tavern or SillyTavern character cards, choose their folder.
   Keep them where they are, or copy them into Kehai. Or skip this.
4. **A language model.** This is the character's brain. Pick one on the Models page (the
   recommended one fits your graphics card), download it and press **Use**. You can carry on
   while it downloads. Without a model the character can't think, so don't skip this for long.
5. **Extras.** Dictation (talk instead of typing; about 0.5 GB, runs on your processor) and
   voice (the character speaks aloud; needs an NVIDIA card with about 12 GB of video memory and
   about 25 GB of disk). Both install with one button, or later from Settings > Voice.

A short tutorial follows, showing how to talk, the Nav Menu and Control Panel, and the Mind
window. You can replay it from Settings > Help & about.

Everything optional starts off: screen vision, voice, dictation and push to talk are only on once
you turn them on.

## Everyday use

| To do this | Do this |
| --- | --- |
| Talk | Left-click the character to open the chat box. Enter sends, Shift+Enter starts a new line, Esc closes. |
| Move them | Drag the character anywhere on your desktop. |
| Resize them | Scroll over the character. |
| Turn them | Drag with the middle mouse button. |
| Pat their head | Hold Alt over the head for the hand, then press and rub. |
| Open the Nav Menu | Right-click the character: the Control Panel's tabs (Talk, Mind, Body, Wardrobe, Scene, Permissions), Characters, Rooms, Models, Settings, Show metrics, Hide to tray, Quit. |
| Find them again | Use the tray icon: show or hide, Control Panel, reset size and position, Characters, Rooms, Settings, Quit. |
| Push to talk | Turn on dictation, then push to talk in Settings > Voice. Hold the backtick key (`) in any app and speak. |

## Going further

- **More characters.** Characters > New character: from your cards, from a card file (PNG or
  JSON), starting from Aero, or written from scratch.
- **Rooms.** Put up to 4 characters on your desktop together, and talk to everyone or just one.
- **The Mind window** (Nav Menu > Mind > Mental Model). What the character remembers and
  believes about you. New memories wait in Review for you to approve, edit or deny. When the mind
  fills up, use **Curate** and then **Synthesize** to tidy it, or turn on Auto-manage to let the
  character do it. A bigger language model does this better.
- **Screen vision.** Off until you turn it on in the Control Panel's Permissions tab ("Let the
  character see my screen"). Screenshots stay on your PC and are never saved to disk.
- **Animation configs** (Koikatsu bodies). Settings > Animations > **Export...** lets you pick
  exactly what to share (activities, gestures, idles, talking, picked up, expressions) and name
  the `.kehaianim` file. **Import...** adds someone else's. Share yours on the Discord.

## Updates

Kehai checks for updates in the background and downloads them quietly. When one is ready, a
small chip saying "Update <version> ready" appears; click it, then **Update now**. Kehai closes,
installs the update and opens again. Your characters, chats and memories are kept.

## Something went wrong?

Settings > Help & about > Troubleshooting has **Open logs folder** and **Copy report info**.
When you report a problem on the Discord, paste the report info and mention the build number at
the bottom of Help & about (for example "Kehai Companions 1.0.0 (Public)"). Logs leave out what
you said in chats unless you turn on Detailed logs there.

## Uninstalling

Use "Add or remove programs" in Windows. Your characters, chats and memories are kept unless you
tick "Also delete my characters, chats and memories". If you used a Koikatsu body, the Kehai
plugin is taken out of Koikatsu too, unless you untick "Also remove the Kehai plugin from
Koikatsu". You can also remove it at any time from Settings > Avatar > Koikatsu.

## License

Kehai Companions is free to use, by WrenLoft, under its end user license agreement (shown by the
installer, and in Settings > Help & about > License). It is not open source. The libraries it
is built with, and the extras it can download, each come under their own licenses, listed in
Help & about.

Koikatsu and Koikatsu Sunshine are games by ILLUSION. Kehai is an independent project, not
affiliated with or endorsed by ILLUSION.
