# Spotifycmd
Tiny scripts for controlling Spotify on the command line

#Installing

<code>sudo apt-get install xdotool</code><br>
<code>git clone https://github.com/limabeans/Spotifycmd.git</code><br>
<code>cd Spotifycmd</code><br>
<code>mkdir ~/bin</code> (if it doesn't already exist)<br>
<code>cp prev ~/bin</code><br>
<code>cp pause ~/bin</code><br>
<code>cd ~/bin</code><br>
<code>chmod u+x prev pause</code><br>
<code>PATH=$PATH:~/bin</code> (add <code>~/bin</code> to end of <code>$PATH</code><br>

I search for the Spotify process by name by doing <code>xdotool search --name "Spotify - Linux Preview"</code>. You might need to change this depending on whether you're a Premium user or not.


<code>prev</code> -- Go to previous song. I usually do this if I want to "repeat" a song without wilst skipping the commercial.

<code>pause</code> -- Play/pause the current song.
