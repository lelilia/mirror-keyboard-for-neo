# mirror-keyboard-for-neo
mirroring the keys from the left side to the right side 

## motivation

I broke my left arm which makes typing soooo much harder
I read the [xkcd article about key mirroring](https://blog.xkcd.com/2007/08/14/mirrorboard-a-one-handed-keyboard-layout-for-the-lazy/) which gave me the idea in the first place.
I found some one handed layouts online but not for [neo](https://neo-layout.org/) and mostly for the left hand.

After trying out ukulele and not getting any satisfying results I found this [article](https://medium.com/@nikitavoloboev/karabiner-god-mode-7407a5ddc8f6) which send me on the right path.

## get it running

Feel free to try it out but be warned it is very hacky and programmed only withmyself in mind 

### prerequisits

neo layout on a Mac 

### installing
if you have neo running on a Mac you already have Karabiner installed. You also need goku.
```
brew install yqrashawn/goku/goku
```
copy the code to ```~/.config/karabiner.edn``` and create a Karabiner profile called "Default".

```
goku
```
will install the mapping to your Karabiner profile. You have to reinstall the neo "Complex Modifications" again after running goku.

### using it
now you have the space as a modifier that mirrors the left side to the right side.
or if you use a foot pedal mapped to 1 and 2 you can also use that but i found it very uncomfortable.

