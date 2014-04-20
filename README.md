Jekyll plugin for Windows 8.1 IE live tiles
===============

##Setup

1. Copy 'jekyll-live-tiles.rb' to your _plugins folder
2. Add "<meta name='msapplication-config' content='/ietemplates/ieconfig.xml' />" to your header file
3. In _config.yml specify
	1. ie_frequency:  - (optional) the frequency of site polling. Options are {30,60,360,720,1440}. Default is 1440 (1 day) 
	2. ie_tile_color: - (optional) the color of the windows 8 pinned background tile
	3. ie_tile_small: - location of small tile image (For more information of tile sizes visit http://msdn.microsoft.com/en-us/library/dn455106(v=vs.85).aspx)
	4. ie_tile_medium - location of medium tile image
	5. ie_tile_wide   - location of wide tile image
	6. ie_tile_large  - location of large tile image
4. Build
