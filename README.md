# Rofi Galactic Horizon Theme

![Ekran Görüntüsü - 2024-12-01 21-06-25](https://github.com/user-attachments/assets/f0eda7db-70a0-4080-adf4-75aeef64f4b4)

## .config/rofi/config.rasi
```
configuration {
	modi:				"drun";
	font:				"Rubik 10";
	display-drun: 			"";
	drun-display-format:            "{name}";
	sidebar-mode: 			false;
}

@theme "/dev/null"

* {
	bg:				#061115;
	fg:				#d9d7d6;
	button:				#0b151a;

	background-color:		@bg;
	text-color:			@fg;
}

window {
	transparency:                   "real";
	width:			    	70%;
}

prompt { enabled: false; }

entry {
    placeholder: "🚀  🌕";
    placeholder-color: @fg;
    expand: true;
    background-color: rgba(0,0,0,0.2);
    padding: 1.5%;
    border-radius: 8px;
}

inputbar {
	children: 			[ prompt, entry ];
	background-image:               url("img/uzay-mekigi.png");
	expand:                         false;
	border-radius:                  0px 0 8px 8px;
	padding:                        235px 0px 50px 1000px;
}

listview {
	columns:                        1;
	lines:	                        4;
	cycle:                          false;
	dynamic:                        true;
	layout:                         vertical;
	padding:			30px 300px 30px 30px;
}

mainbox { children: [ inputbar, listview ]; }

element {
	orientation:                    vertical;
	padding:                        1.5% 0% 1.5% 0%;
	border-radius:			8px;
}

element-text {
	expand:                         true;
	vertical-align:                 0.5;
	margin:                         0.5% 3% 0% 3%;
	background-color: 		inherit;
	text-color:       		inherit;
}

element selected {
	background-color:               @button;
	border-radius:                  8px;
}
```

## .config/rofi/img/uzay-mekigi.png

![uzay-mekigi](https://github.com/user-attachments/assets/429a2400-9cb3-4080-9746-910e9c5c37bd)

## Desktop Wallpaper

![output](https://github.com/user-attachments/assets/70343e7a-d582-4c5e-a139-740f9158a91f)

