Adesk Menu
=========



 ADesk Menu
   - v0.4 : set default menu position to bottom left, just above the panel
   			prevent window display on taskbar
   			added behaivor to hide window menu on second execution
   
   - v0.3 :    This script was edited from the original by sliphot and MoD from silver irc.
   I thhought it might come in handy with tint2s's new launcher feature.
   We re-worked it so it will open the menu in a designated area of the screen when the script is executed. 
   by default it opens in the top left corner of the screen. To adjust go to line 369 and adjust x= and y=
   Make this script executable and move it to /usr/bin after that make a .desktop file pointing to it.
   Point tint2 to the .desktop file and presto! tint2 desktop menu. It can be a little slow to load.
   It helps to run it once in a terminal with the -s option. it saves a config file of all your .desktop files.
   If you install a new app after you have ran the -s option you will have to run it again to update the config. 
 
   - v0.2 : add signal , get cursor position and show menu whith it
			
   - v0.1 : check if 'Terminal=true' in .desktop file, always above other windows

   Original by ADcomp <david.madbox@gmail.com>
      http://www.ad-comp.be/
      
   Current modifications by Agustín Cruz <atin81@gmail.com>

   This program is distributed under the terms of the GNU General Public License
   For more info see http://www.gnu.org/licenses/gpl.txt