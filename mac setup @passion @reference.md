# ultimate mac setup from scratch

TODO: youtube video

principle: speed, UI

## core app:

karabiner
raycast
space launcher
terminal (alacritty item2)
tmux
keyboard maestro
display maid

## great app

great app are those you do not realize their exist

appcleaner
downie
cleanshot x

## visual

consolas nerd + LGXW Wenkai
transparent backgroud + github theme

tmux
---

:key to enter tmux command prompt on top
shift + 

issue: cannot type even paste semicolon

inside terminal vi mode, outside terminal ctrl h,j,k,l

no vim tab no tmux vi navigation, simple fast window move.

TODO karabiner key binding.ctrl j,k  with hold finished
TODO tmux alias

new -d 'ping blah; tmux wait -S ping’;tmux wait ping echo done.

you can keep shortcut, can also use natural language.

raycast as quick link luancher.

set -s command-alias[110] "conftmux=new-window 'conftmux'".

conftmux is a shell alias which open new window in tmux and open lf press q exit lf will quit this window and backup to preview window,the best thing is you can use same shortcut in tmux and.

## raycast

Searching menu item (find command in any app)
quick link (bookmark,search)
utility (uninstall,kill,color pick,reboot)
display today calender

## fish shell

### build in command

1. prevd|nextd,to previous and next directory (equal shortcut:alt-left arrow|alt-right arrow)
2. alt-w (what)after type a command:will show simple description about this command or with command is alias with.

3.alt-s retype the last command with sudo

## nvim

spelling check:

To use that file in vim, you need to open it,

~/.config/nvim/spell/en.utf-8.add
in vim and in Command mode execute

:mkspell! %
[ ! overwrite an existing file; % is the current file, in the vim buffer.]

In any file press zg will add the word under cursor as a 'good' one. 

## mouseless

karabiner element
spacelauncher
raycast
tmux
vimium
moom

### IINA key binding

j backward 5s
k forward 5s
h backward 60s
l forward 60s

u previous media
i next media

## input
chinese input : squirrel


## gloable key binding
karabiner
right shift press alone = f17 ; f17 to switch input ; right-shift press with other key = shift
ctrl-f : in terminal app: = switch to english and esc ; outside terminal app = esc . 
; : in terminal app = tmux command prompt ; outside terminal = semiconlon
spacelauncher: 
