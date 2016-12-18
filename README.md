# pyCleanTor
Clean and reorganize torrents

Finds, categories, renames and moves torrents from a downloads folder.

Example:
	
	Starting files
	\downloads\American.Dad.S13E06.HDTV.x264-FUM[ettv]\American.Dad.S13E06.HDTV.x264-FUM[ettv].mp4
	\downloads\American.Dad.S13E06.HDTV.x264-FUM[ettv]\Torrent-Downloaded-from-ExtraTorrent.cc.txt

	Ending files
	\media\tv_shows\American.Dad.S13E06.mp4


The use of tags to find info in name.
	FUM, [ettv], HDTV,

The files to not copy
	small txt files (Torrent-Downloaded-from-ExtraTorrent.cc.txt)  Thanks



Basic Flow
	Loop thru each file/folder in the "Downloads" folder
	If file
		What kind of file (Audio, Video, App, Game, Other)
		Each file will be scored(using machine learning)
		A new name will be created.
		A file will be moved or deleted.
	If folder recurse 



	

