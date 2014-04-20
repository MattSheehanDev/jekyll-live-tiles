Jekyll plugin for Windows 8.1 IE live tiles
===============

##Setup

1. Copy 'jekyll-live-tiles.rb' to your _plugins folder
2. Add 
'''
<b><meta name='msapplication-config' content='/ietemplates/ieconfig.xml' /></b>
''' 
to your header file
3. In _config.yml specify
	- ie_frequency:  - (optional) the frequency of site polling. Options are {30,60,360,720,1440}. Default is 1440 (1 day) 
	- ie_tile_color: - (optional) the color of the windows 8 pinned background tile
	- ie_tile_small: - location of small tile image (For more information of tile sizes visit http://msdn.microsoft.com/en-us/library/dn455106(v=vs.85).aspx)
	- ie_tile_medium - location of medium tile image
	- ie_tile_wide   - location of wide tile image
	- ie_tile_large  - location of large tile image
4. Build
5. All necessary files will be generated in a directory called <b>ietemplates</b>
