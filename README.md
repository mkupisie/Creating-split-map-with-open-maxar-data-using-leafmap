## Creating-split-map-with-open-maxar-data-using-leafmap

**Visualizing the Maxar Open Data for the 2023 North India Floods (pre and post event images) on the split map using leafmap.**

**The Maxar Open Data Program** provides pre- and post-event high-resolution satellite imagery. The available collections in the Maxar Open Data STAC catalog can be checked using _leafmap.maxar_collections()_ function. Each collection represents single event. 

**The purpose of the code is to retrieve collection for North India Floods 2023**, that is related to the event on 4th October in Sikkim (a state in northeastern India), where the heavy rains caused the glacial South Lhonak lake to breach its banks, causing a glacial lake outburst flood. The footprints _(geojson, tsv)_ of the event were taken from the Maxar Open Data GitHub repo (https://github.com/opengeos/maxar-open-data). Start_date and end_date parameters were used to get images before and after the event. Based on the footprint map, area of interest were set to the region where pre and post event images are available. Split map was created to compare the pre-event and post-event images.
