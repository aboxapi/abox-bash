# abox-bash
abox-bash is a small bash utility for using http://acapela-box.com/ right from your command-line.


This tool was tested on bash (Linux), MSYS2 (Windows) and bash (Windows)

## Usage
```
./abox [options] <text>
./abox [options] <-f filename|--file filename>
./abox <-l|--list> <ISO country code>
./abox -h
```

## Options
  `-r`,  `--cookie`		Regenerates the cookie, use this if no response is given.
  
  `-v`,  `--voice`		Specify voice (default:antoinefromafar22k)
  
  `-o`,  `--output`		Specify output file for download action
  
  `-a`,  `--action`		Specify an action in
  
			  - url, show_url: shows the url (default)

			  - play, mpv: plays the sound using mpv

			  - stdout, curl: prints the sound to stdout using curl

			  - wget, download, dl: downloads to file, can specify a name with -o

  `-S`,  `--shaping`	Specify a voice shaping (default:180)

  `-s`,  `--speed`		Specify a voice speed (default:100)