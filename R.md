shp<-st_read("C:/Users/kenin/Downloads/Blocks_Boston_2010_BARI/Blocks_Boston BARI.shp")
str(shp)
map<-merge(data,shp,by='Blk_ID_10',all.x=TRUE)
