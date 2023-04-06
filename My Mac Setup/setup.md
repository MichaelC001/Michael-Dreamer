# Mac setup from scratch

## welcome
Hello, YouTube!

- I am a new YouTuber, I will share my mac setup as my first video.
- I am not a programmer, I do financial job in Shanghai, China.
- I am not a native English speaker. I hope you guys could understand me.

Les's get started!

## Mac setup for command line usage and note-taking.
- I use Thinkpad windows laptop for working , meanwhile iMac M1 as my daily computer.
- I spend a most of time in terminal and browser. The pholopy of this setup, is keeping simple and mouseless.

## App Launchers

**Raycast as universical launcher**
*Spacelauncher 1.6 as quick app switcher.*

1. spacebar + a: switch to terminal app Wrap.
2. spacebar + s: switch to web browser Arc.
3. spacebar + i: switch to video player IINA.
...

## Window mangement

Moom

- I could set diffent diffrent layout for daily using and video recoding.
- space-tab restore window layout.

Sometimes I turn on Moc OS stage manger.

## Terminal

Warp or iTerm2

- Warp looks good, when recoding video, I set Windows Opacity to 50%, while playing a backgroud video behind terminal window.
- iTerm2 supoort tmux mode and image, sometimes I will switch to iTerm2.

## Key binding

Karabiner element

1. Outside terminal app: Ctrl-h,j,k,l = left,down,up,right ; Inside terminal app,ctrl-h,j,k,l move to left,down,up,right tmux pane.
2. right shift : press alone = F17 (which is set to switch input method in system preference), press with other key = shift.
3. ctrl - f = escape , escape = escape and switch input method to english.

## Auto app quitting

I use the app called quitter to quick all the app just need temporary.
app will be closed automaticly after a specifed time.

example:

photos 5min
drafts 5min
activity monitor 5min
appstore 5min
coteditor 10min

## config


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
