# Spotifycmd
Tiny scripts for controlling Spotify on the command line

#Installing

<code>sudo apt-get install xdotool</code>
<code>git clone https://github.com/limabeans/Spotifycmd.git</code>
<code>cd Spotifycmd</code>
<code>mkdir ~/bin</code> (if it doesn't already exist)
<code>cp prev ~/bin</code>
<code>cp pause ~/bin</code>
<code>cd ~/bin</code>
<code>chmod u+x prev pause</code>
<code>PATH=$PATH:~/bin</code> (add <code>~/bin</code> to end of <code>$PATH</code>

I search for the Spotify process by name by doing <code>xdotool search --name "Spotify - Linux Preview"</code>. You might need to change this depending on whether you're a Premium user or not.


<code>prev</code> -- Go to previous song. I usually do this if I want to "repeat" a song without wilst skipping the commercial.

<code>pause</code> -- Play/pause the current song.
