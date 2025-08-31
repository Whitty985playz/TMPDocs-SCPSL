# What is text Mesh Pro?
Text Mesh Pro(or TMP) is the Unity UI Text type SCP: Secret Laboratory uses to display information like:

- Server Names
- Server Information
- Broadcasts
- Hints
- TextToys
- etc

There are **some** elements taht do not use TMP, however I will not talk about them since this documentation is for your Server Info.

| TMP Syntax | Usage | Example |
| ------------- | ------------- | ------------- |
| \<b> \</b> | Creating **Bold** Text. | Hello \<b>World!\</b> |
| \<i> \</i> | *Italics* | \<i>Hello\</i> World! | 
| \<u> \</u> | <ins>Underline</ins> Text | \<u>Hello\</u> World! | 
| \<i> \</i> | ~~Strike Through~~ Text | \<s>Hello\</s> World! | 
| \<color=\[HEX\]> \</color> | Coloring Text | \<color=red>Hello\</color> World! | 
| \<alpha=#XX> \</alpha> | Changing the Alpha Channel of Text | \<alpha=#55>Hello\</i> World! | 
| \<size=###> \</size> | Resizing Text | \<size=40>Hello\</size> World! | 
| \<line-indent=XXX%> \</line-indent> | Self explanitory | \<line-indent=15%>Hello\</line-indent> World! | 
| \<align="\[LEFT/CENTER/RIGHT\]"> \</align> | Realign Text | \<align="right">Hello\</align> World! | 
| \<link="\[LINK\]"> \</link> | Add a hyperlink | \<link="https://en.scpslgame.com">Hello\</link> World! | 


This should be all you need to know when it comes to using TMP's Markdown.
If you want to add emojis to your server info, please follow [this link](https://boltondev.github.io/SL-Emojis) to see all of the available emojis you can pick from.


Here is a basic template you can use when creating your server info.
```
<align="center"><size=50><b>[SERVER NAME]</b></size>
<size=40><color=blue><link"[LINK]">Discord(Clickable)</link></color></size>
</align>
<size=15>[RULES]
```

Here is what you could expect to see in the game(using my server as an example).
<img width="765" height="755" alt="Server Info Example" src="https://github.com/user-attachments/assets/53ecc929-ac21-4725-9af7-2eb89db8230b" />

If you want to gradient text, please follow [this link](https://cedmod.nl/tools/gradient) to go to the **CedMod Gradient Creator**. This is a tool I personally use a lot.
