Cli for https://github.com/b5i/apple-playlist-downloader

#Install

`npm i -g apple-music-downloader-cli`

#Run
```
HELP 

(Required)   / -u / --url "URL" : Download playlist with provided URL

(Optional) -p / --path /path/to/song/folder : Download songs to provided path, default : current directory.

(Optional) -d / --dcd : Won't use/create ApdSongs folder in the path.

(Optional) -h / --help : Shows current message

Example :
apd "url"
```
#Example 

`apd "https://music.apple.com/en/playlist/dancexl/pl.6bf4415b83ce4f3789614ac4c3675740?l=en" `

Will download the playlist in the current working direcotry and save the songs in a created folder named ApdSongs, to avoid the folder and just download in the cwd just add -d or -dcd parameter.

