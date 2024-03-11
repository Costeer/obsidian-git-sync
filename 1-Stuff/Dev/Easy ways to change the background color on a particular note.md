If you want to change the background color of a particular note, as OneNote does, use this simple snippet:
```
.yourColorName{ 
background-color: #HexadecimalColorCode;
}
```

and add the cssclass "yourColorName" to the front matter of your Note.

For example, I defined 4 colors named blue, red, green, and yellow with hexadecimal code:

```
.blue {
  background-color: #DAEDFC;
}

.red {
	background-color: #FFE2DF;
}

.green {
	background-color: #E0FFF4;
}

.yellow {
	background-color: #FFFEDE;
}
```

To change the background color of your note once you add this snippet to Obsidian, simply write in the front matter of your note:

```
---
cssclass: blue
---
```

If you want to go fancy, you can add some effects, like a gradient. Here is an example with color encoded in RGB:

```
.blue2 {
	background-image: linear-gradient(rgba(218, 237, 252, 1), rgba(114, 194, 234, 0.80));
}
```

Or if you want to add a background image from the internet, you can use this snippet as a template.

```
.image1 {
	background-image: url("https://images.unsplash.com/photo-1558591710-4b4a1ae0f04d?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=774&q=80");
	background-position: center;
	background-attachment: fixed;
	background-repeat: no-repeat;
}
```

(For using a background image from the internet, you must have only the image on the screen to get his URL address. The best way to get the URL is to open the image in a new tab and copy-paste the URL)

→ If you want to add a local image as a background , you can do it by adding **app://local/** before the path to the image:

```
.image2 {
	background-image: url("app://local/c:/path/to/my/file/image.png");
	background-position: center;
	background-attachment: fixed;
	background-repeat: no-repeat;
}
```

*Auch Interessant | Tags*
[[Colours]] [[README]]
#dev 