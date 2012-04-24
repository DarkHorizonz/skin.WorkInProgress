HORIZONZ - A Skin for XBMC
--------------------------
Created by XB2IRIS
------------------

-------------
0.0  Contents
-------------

1.0  About
1.1  Notes
1.2  Required
1.3  Issues

2.0  Installation

3.0  Setup
3.1  Backdrops
3.2  Fanart
3.3  Home Page
3.4  Features
3.5  Reset

4.0  Credits

5.0  Contact

----------
1.0  About
----------

Horizonz owes it's existence to the genius of Aeon and it's creator DJH_
who single handedly birthed a new skinning concept which so many XBMC 
users have come to love over the last few years.

This skin begun its rise as an Aeon Mod and has always continued to 
follow the principle of DJH_'s concept of elegance, efficiency and 
function. With DJH_'s skinning hiatis and Aeon's developemental progress 
considered unknown, Horizonz continued in its parent skin's wake by adding 
a new look interface, new simplistic views and a new generic concept 
called completeness. With Horizonz maturing by the day, the current feature 
potential has become endless, and with continued user based influence 
it has lept beyond it's label 'Mod' and greeted the XBMC community 
with a progressive skin bound only by the horisons of our minds.

1.1  Notes
----------

Current progress is as illusive as ever. With Volume IV just about 
installed and ready to go, here's what you can expect in this
new and improved version of Horizonz.

- A universal frame system
- Use Wide Icon option for use in TV Shows section
- A universal dialog system with new NP panel and player control
- New look home scrollers and lower home scroller RSS support 
- Watched/Unwatched video overlays and counts
- And lots more (full list in changes.txt)

User feedback is essential to progressive skins such as Horizonz, so 
your input is important and very relevent to future builds. Volume
V is set to be the landmark when Horizonz achieves Beta status, so
please continue pointing out inconsistencies and offering suggestions
as Volume IV becomes your new media based niche.

1.2  Required
-------------

Common:

Required: The very latest build of Xbox Media Center
Required: A widescreen (16:9) TV
Recommended: A High Definition TV capable of 720p display

Windows:

Required: An PC with high-end CPU
Required: Window XP Home/Pro or later
Required: Direct3D compatible video card
Recommended: 1gb+ RAM
Recommended: Nvidia GeForce 7000 series or above

Linux:

Required: An HTPC with high-end CPU
Required: Ubuntu Linux 7.04 or later
Required: Pixel Shader 3.0 / OpenGL compatible video card
Recommended: 1gb+ RAM
Recommended: Nvidia GeForce 7000 series or above

Xbox:

Required: A modded XBOX capable of running unsigned binaries
Recommended: Hard drive with 200mb+ free space

1.3  Issues
-----------

Horizonz was created with all systems in mind, but due to skin
progress, optimization levels have dropped somewhat, allowing
certain flaws such as memory leaks and stuttery animation to 
creep into certain systems such as the XBOX. With this in mind, 
further optimization will be perfomed at a later stage.

Furthermore, due to personal situation, it has become impossible
for me to tweak non-standard media sections such as Clips and 
Comics. Once this situation changes, those sections will be given 
priority and dealt with accordingly.

Anyhow, no skin is without its flaws, and certain inconsistencies 
will develop due to limitations in the XBMC coding structure and the
ongoing battle between personal preference and user orientated 
suggestions. I alone develop this skin and in such, do all the hard 
work, so please bare with me if I cannot find the time or knowledge
to create a perfect skin incapsulating every individual which uses it.

-----------------
2.0  Installation
-----------------

Begin by copying the extracted 'Horizonz' folder into XBMC's /skin folder
alongside skins such as Project Mayhem III. Once in XBMC, navigate to 
the System->Appearence menu and switch skins to Horizonz. A brief 
introductory screen will welcome you with the further option to upgrade
or re-install a fresh copy of Horizonz.   

----------
3.0  Setup
----------

All Horizonz specific customisation options can be found in the 'Horizonz' 
sub-menu, reached simply by visiting the setup menu (push 'up') while on the 
home page. All options are saved in real time and can be changed at any 
point during your media orientated experience. Feel free to experiment 
with skin options to tweak the skin to suit your preferred environment. 

3.1 Backdrops
-------------

As Aeon before it, Horizonz supports 720p (1280x720) backdrop cycling while 
you navigate its hierachy of media defined sections, personalising your 
experience even further. 

Backdrops should be stored on XBMC's native system (XBOX, HTPC), preferably 
in folders representing their media format (Movies, Music, TV) to make adding
them into Horizonz a less tricky process. Once in Horizonz, navigate to
the Horizonz->Backgrounds menu and associate the home menu sections with your
pre-defined media orientated folders you created. The preview window will
show whether you've associated the correct media type with the correct 
folder. Furthermore, it is possible to define a single backdrop for each media
section if that's what you prefer. However, if a folder has already been
defined for a specific media section it will take preference unless you
clear the folder you have previously specified for that section.    

Backdrops should preferably be saved in BMP format. JPG and PNG are 
also supported by XBMC, though XBOX users can expect noticable loading times 
with those formats. It is also recommended that XBOX users resize their 
backdrops to 1024x576 or even 960x540 to further optimize the performance
of Horizonz. Perfomance on certain views may be a little sluggish based on 
which XBOX kernel you are running and various other memory related issues, 
so it is strongly recommended that you enable the "Disable Backdrop Cycling"
option in the Horizonz->Features section.

3.2  Fanart
-----------

Horizonz featurez full support for user-generated TV fanart and contextual
Movie fanart. Enabled by default, fanart will display automatically on
selection in certain fanart driven views (showcase and info), as long as 
the following conditions are met    

TV	- You are in Library, not File mode.
	- Your TV Show folder has been set up to receive database info from
	  thetvdb.com only.
	- The Fanart setting is enabled (default).
	- Fanart for your current TV show is hosted on thetvdb.com.


At present, art must be locally stored in order to appear in XBMC. So you
can't grab it from the net like you would TV show fanart. Instead, the image
must be stored alongside the movie itself, with a .jpg or .png extension and
a "-fanart" suffix. So for the above example, you'd need this:

Movies	- You are either Library or File mode.
        - The Fanart setting is enabled (default).
        - Fanart is stored locally alongside the movie itself with a jpg or
          png file extension (bmp can be renamed to either) and a -fanart 
          suffix attached to the movies title, for example:
              
          Beowulf.avi (movie)
          Beowulf-fanart.jpg (fanart)

Similar to backdrop optimization, resizing fanart to lower resolutions can
lead to an indefinite performance boost in the Showcase and Info views.  

3.3  Home Page
--------------

Horizonz features a large selection of Home Page shortcuts from 
the essentials such as Movies, TV Shows and Music to the lesser used Arcade 
and Clips. These Home screen sections however remain low on the current
priority list and have thus, not been optimized for use with Horizonz. 
As in Aeon, these menu options are nothing but shortcuts to
bookmarked sources defined in the sources.xml (located in XBMC's /Userdata
folder) with the following format: 

    <movies>
        <default>Movies</default>
        <source>
            <name>Movie Archive</name>
            <path>/archive/movies</path>
        </source>
    </movies>

Each media source in XBMC is defined using a separate <source></source>
tag, the <name> tag being what Horizonz looks for. To use its additional
Home shortcut options, you need to define sources with the following names:

OPTION				SOURCE NAME (default)

Movies				Movies
TV Shows			TV Shows
Clips				Clips
Arcade				Arcade
Adult				asource
Comics				Comics
Game Trailers			Gametrailers
Movie Trailers			Movietrailers

In addition to these default names, you can specify your own source names
in the Horizonz->Home Shortcuts menu. This is also where you can turn 
individual Home shortcuts on and off according to your preference.

Furthermore, the Horizonz->Home Page menu contains a number of Home Page only 
features, which may be used to improve user experience, depending on what suits
you. Here is a list of Home page features:

Time And Date Panel		The default time panel which displayes the 
				time and date
Time, Date And Weather Panel	Alternate time panel which displays the
				time, date and the current temperature
Fullscreen Media Backdrop	Displays the current music visualisation
				or video being played instead of backdrops
Now Playing Media Panel		Displays a panel with currently played
				media information including the 
 				cover art and title
Vignette Visual Effect		Displays a dark overlay over certain 
				portions of the backdrop currently being
				displayed
Lower Home Scroller Position	Shifts the home scroller to a lower 
				screen location to reveal more of the 
				currently displayed backdrop
Alternate Home Scroller Shade	Replaces the default light home
				scroller with a darker version as well
				as replacing the dark time and rss panels
				with a lighter version  
Use Original Time Panel		Swaps the time panel to the original
 				location and shade which is seen across 
				the entire skin except the home screen

With a personalised combination of these features, your media experience may
improve dramatically. The Alternate Home Scroller Shade with Vignette
Overlay, for instance, has been quite a hit since Horizonz' release, so 
I suggest you give it a go if you feel something needs a change.

3.4  Features
-------------

Horizonz has added a number of excellent features to Aeon's already amazing
list of unique features. Some features are preference driven, others 
perfomance orientated and can be reached by visiting the Horizonz->Features
menu. The array of across the skin features are listed as follows:

Contextual fanart for Movies	This enables item specific Movie and TV Show fanart
				in the Showcase and Info views
Contextual fanart for TV	This activates static Season and Episode fanart
				in the Showcase and Info views
Disable Plot Info Scrolling	This customises scrolling of information across
				all views in the Movie and TV Show sections 
Disable Backdrop Rotation	Improve performance and increase show focus by 
                                removing backdrop cycling from behind fanart in
				Showcase and Info views
Media Information Panel		Choose whether or not to show item information
				in the Wall view
Dynamic Media Info Panel	Add a new dimension to the List and Poster views
				by adding a dynamically animated info panel
Use Poster Icons		This enables the use of Normal Poster Icons in 
				the List, Poster, Info, Showcase and Wall views 
  				in the TV Shows section
Use Wide Icons			This activates the use of Wide Banner Icons in 
				the List, Poster, Info and Showcase views in the 
				TV Shows section (Deactivates the Wall view in
				TV Show and Season sections)
Disable (Un)Watched Overlays	Hides watched/unwatched overlay icons in Movie
				and TV Show sections

Besides Horizonz vast array of across the skin features, there are also a few
other tweakable functions to improve overall performance and usability. These 
can be found in the Horizonz->System menu. They are as follows:

Force XBOX Mode			Forces certain textures to be replaced by
				optimized versions which use less memory and thus
				increase performance on systems with limited 
				system RAM
Vignette Visual Effect		This adds a dark overlay to certain sections
				of the screen to improve graphical quality
				but use more memory and may cause diminished
				performance on memory busting views
Light Crest Effects		Enables light crest animated effects across
				the skin and may cause stuttery animation
				due to memory leaks
Enable Startup Playlist		Allows for an M3U Playlist to play upon
				Horizonz startup but does require more
				memory at startup
Specify Startup Playlist	Specify which M3U Playlist to play at
				startup	

These feature rich menus are of the utmost importance to improving user
experience, eliminating memory related issues and as a whole defining
your unique version of Horizonz. Remember to disable features you don't 
use or need, as they will do nothing but get in the way.   

3.5  Reset
----------

In the Horizonz->System menu, the two reset options will restore Horizonz to its
default state. You can either restore all skin settings to their default or
choose to reset the skin whilst leaving your user-defined settings intact. The
'Reset All' option is recommended for those updating Horizonz to a new volume, 
and experiencing problems with backdrops or other features.

------------
4.0  Credits
------------

Skin Code and Design:	Gary Petersen aka Gareth Denne

Xbox Media Center:	Team XBMC (for the best Media Centre around)

Thanks:			DJH_ (for AEON and the inspiration to create)
			Rand Al Thor (for his AEON Mod and advice)
			Six_Storm (for skinning tips and great advice)
			Tension113 (for helping out with non-standard sections)
			Takagen (for Trainer Settings code)
			DigitalHigh (for skinning ideas and advice)
			Livin (for ideas for universal frame system)
			Xbmc01 (for optimization tips)
			DjOktave (for use of his sound pack)
			Chipy (for skinning ideas and coding ideas)
			Rectifier, XBDD (for some coding tips and xbox testing)
			Pike (for giving Horizonz its own sub-forum)
			JMarshall, Skunkmonkee, Spiff and Jezz-X (for tech help)
			XBMC forum users (for ongoing support)

Donation Shouts:	

Shouts:			Team Razorfish (for creating MediaStream, PM3s replacement)
			BlackRose (for being the most in touch person on the forum)

------------
6.0  Contact
------------

throughtheiris25@hotmail.com