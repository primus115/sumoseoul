netconvert --osm-files gangnam.osm -o gangnam.net.xml
polyconvert --osm-files gangnam.osm --net-file gangnam.net.xml --type-file osmPolyconvert.typ.xml -o gangnam.poly.xml
python D:\github\sumoseoul\randomTrips.py -n gangnam.net.xml -r gangnam.rou.xml -e 50 -l

https://www.youtube.com/watch?v=48N_BCeDFkI