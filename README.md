# Spotifycmd
Tiny scripts for controlling Spotify on the command line on Linux

## Installing

<code>sudo apt-get install xdotool</code><br>
<code>git clone https://github.com/limabeans/Spotifycmd.git</code><br>
<code>cd Spotifycmd</code><br>
<code>mkdir ~/bin</code> (if it doesn't already exist)<br>
<code>cp prev ~/bin</code><br>
<code>cp pause ~/bin</code><br>
<code>cd ~/bin</code><br>
<code>chmod u+x prev pause</code><br>
<code>PATH=$PATH:~/bin</code> (add <code>~/bin</code> to end of your <code>$PATH</code>)

<code>xdotool search --name "Spotify - Linux Preview"</code> within each script might need to be tweaked depending on whether you're a Premium user or not.

## Commands

<code>prev</code> -- Go to previous song. 

<code>pause</code> -- Play/pause the current song.
