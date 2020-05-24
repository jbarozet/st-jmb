# My st (simple terminal) build

![Screenshot of simple terminal](https://gitlab.com/jbarozet/dotfiles/raw/master/.screenshots/screenshot-st.png) 
st is a simple terminal emulator for X which sucks less (st is created by the good folks at [suckless.org](https://suckless.org)).  This is my personal build of st.  I used a number of patches in this build to make st more "sensible" rather than "suckless."  The patches I added to this build include:
+ alpha (for transparency)
+ font2 (to allow setting more than one font, useful when the default font has missing glyphs)
+ scrollback (scrollback through terminal using Shift+PageUp/PageDown.)
+ scrollback mouse altscreen (allows scrolling using Shift+MouseWheel.)


# Installing st-jmb on other Linux distributions

Download the source code from this repository or use a git clone:

	git clone https://gitlab.com/jbarozet/st-jmb.git
	cd st-jmb
    sudo make clean install
	
NOTE: Installing st-jmb will overwrite your existing st installation so make a backup of your current config if you need it.
