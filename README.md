# .config

# GLava
I've been playing around with the GLava config files a bit, making it look like a central sun with blockylooking flames :) \
\
![simplescreenrecorder-2023-04-14_23 18 43_(00:00:16 568)](https://user-images.githubusercontent.com/19855231/232230826-1f47c1a8-47ae-4c75-a485-3472f0555452.jpg)
# install glava 
from source follow steps on \
https://github.com/jarcode-foss/glava \
\
on arch ```sudo pacman -S glava``` \
\
to copy default config files into home ```glava --copy-config ``` \
clone my config ```git clone https://github.com/snaaajl/.config.git -S glava``` \
if you didn't clone directly intto home ```cp .config/glava ~/.config/```

# run 
\
for the bars
```glava -m bars -d &``` \
for the flaming hot sun \
```glava -m radial -d &```
 \
 too exit all glava run
 ```killall glava```
 

