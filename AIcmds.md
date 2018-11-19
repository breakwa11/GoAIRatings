## aya 6.34 ##

aya 6.34  
`--mode gtp --chinese-rule`

## gnugo 3.8 ##

gnugo 3.8 lv1  
`--mode gtp --chinese-rules --level 1`

gnugo 3.8 lvX  
`--mode gtp --chinese-rules --level 10`

## pachi 12.10 ##

pachi 3k  
`-t =3000:9000 threads=1`

pachi 1k  
`-t =1000:3000 threads=1`

pachi nodcnn 1k  
`--nodcnn -t =1000:3000 threads=1`

pachi nodcnn 3k  
`--nodcnn -t =3000:9000 threads=1`

pachi nodcnn 5k  
`--nodcnn -t =5000:15000 threads=1`

## fuego 1.1 ##

fuego 1.1 5M  
`--config config.txt`

    uct_param_player reuse_subtree 1
    uct_param_search number_threads 1
    uct_param_search max_nodes 5000000
    uct_param_search prune_full_tree 0

fuego 1.1 1M  
`--config config.txt`

    uct_param_player reuse_subtree 1
    uct_param_search number_threads 1
    uct_param_search max_nodes 1000000
    uct_param_search prune_full_tree 0

## MoGo Windows ##

MoGo release3 1k  
`--19 --chinese-rules --nbTotalSimulations 1000`  
download: [http://www.godrago.net/Engines.htm](http://www.godrago.net/Engines.htm)

## zen6 (gtp4zen) ##

zen6 8k?  
`-z6 -r3 -t1 -s100 -n0 -o0.1 -p0.1`

zen6 7K?  
`-z6 -r3 -t1 -s200 -n0 -o0.1 -p0.3`

zen6 7K  
`-z6 -r3 -t1 -s300 -n0 -o0.1 -p0.5`

zen6 6K  
`-z6 -r5 -t1 -s400 -n0 -o0.1 -p0.6`

zen6 5K  
`-z6 -r5 -t1 -s500 -n0 -o0.2 -p0.65`

zen6 4K  
`-z6 -r5 -t1 -s600 -n0 -o0.3 -p0.7`

zen6 3K  
`-z6 -t1 -s700 -n0 -o0.4 -p0.75`

zen6 2K  
`-z6 -t1 -s800 -n0 -o0.5 -p0.8`

zen6 1K  
`-z6 -t1 -s1000 -n0 -o0.6 -p0.85`

zen6 1K+  
`-z6 -t1 -s1000 -n0 -o0.7 -p0.85`

zen6 1D-  
`-z6 -t1 -s1500 -n0 -o0.7 -p0.9`

zen6 1D  
`-z6 -t1 -s1500 -n0 -o0.8 -p0.9`

zen6 1D+  
`-z6 -t1 -s1500 -n0 -o0.9 -p0.9`

zen6 2D  
`-z6 -t1 -s2000 -n0 -o1 -p1`

zen6 3D  
`-z6 -t1 -s2500 -n1 -o0.1 -p1`

zen6 3D+  
`-z6 -t1 -s2500 -n1 -o0.2 -p1`

zen6 4D  
`-z6 -t1 -s3000 -n1 -o0.3 -p1`

zen6 5D  
`-z6 -t1 -s3000 -n1 -o0.5 -p1`

zen6 6D  
`-z6 -r15 -t1 -s3000 -n1 -o1 -p1`

zen6 7D  
`-z6 -r15 -t1 -s12000 -n1 -o1 -p1`

## zen7 (gtp4zen) ##

zen7 13k  
`-t1 -r3 -s200 -n0 -o4.0 -p0.2`

zen7 12k  
`-t1 -r3 -s200 -n0 -o3.0 -p0.25`

zen7 11k  
`-t1 -r3 -s300 -n0 -o2.4 -p0.3`

zen7 10k  
`-t1 -r3 -s300 -n0 -o2.2 -p0.3`

zen7 9K  
`-t1 -r3 -s300 -n0 -o2.0 -p0.3`

zen7 8K  
`-t1 -r5 -s400 -n0 -o1.6 -p0.3`

zen7 7K  
`-t1 -r5 -s500 -n0 -o1.2 -p0.3`

zen7 6K  
`-t1 -r5 -s600 -n0 -o1.0 -p0.3`

zen7 5K  
`-t1 -r5 -s800 -n1 -o2.4 -p0.3`

zen7 4K  
`-t1 -r5 -s800 -n1 -o2.2 -p0.3`

zen7 3K  
`-t1 -s1000 -n1 -o2.0 -p0.3`

zen7 2K  
`-t1 -s1400 -n1 -o1.8 -p0.3`

zen7 1K  
`-t1 -s1600 -n1 -o1.6 -p0.3`

zen7 1D  
`-t1 -s1800 -n1 -o1.3 -p0.35`

zen7 2D  
`-t1 -s2000 -n1 -o1.0 -p0.4`

zen7 3D  
`-t1 -s2200 -n2 -o2.0 -p0.45`

zen7 4D  
`-t1 -s2400 -n2 -o1.5 -p0.5`

zen7 5D  
`-t1 -s2700 -n2 -o1.0 -p0.55`

zen7 6D-  
`-t1 -r15 -s2700 -n3 -o5.2 -p0.55`

zen7 6D  
`-t1 -r15 -s3000 -n3 -o4.4 -p0.6`

zen7 6D+  
`-t1 -r15 -s3000 -n3 -o3.6 -p0.6`

zen7 7D  
`-t1 -r15 -s3500 -n3 -o2.8 -p0.65`

zen7 8D  
`-t1 -r20 -s4000 -n3 -o1.4 -p0.7`

zen7 9D  
`-t1 -r20 -s6000 -n3 -o1.0 -p0.75`

zen7 9D+  
`-t1 -r20 -T180 -s25000 -n3 -o1.0 -p0.75`

## Leela 0.11 ##
Leela 0.11 0.1k  
`-p100 -g -t1 --noponder`

Leela 0.11 0.5k  
`-p500 -g -t1 --noponder`

Leela 0.11 1.0k  
`-p1000 -g -t1 --noponder`

Leela 0.11 1.6k  
`-p1600 -g -t1 --noponder`

Leela 0.11 6.4k  
`-p6400 -g -t1 --noponder`

## Leela Zero 0.16 ##

LZ xxx  
`-p1600 -g -t1 -w xxxx.gz --noponder`

LZ xxx (040 < xxx <= 057)  
`-p1600 -r5 -g -t1 -w xxxx.gz --noponder`

LZ xxx (xxx <= 040)  
`-p1600 -r3 -g -t1 -w xxxx.gz --noponder`

LZ xxx 3.2k  
`-p3200 -g -t1 -w xxxx.gz --noponder`

LZ xxx 1.2k  
`-p1200 -g -t1 -w xxxx.gz --noponder`

LZ xxx 0.8k  
`-p800 -g -t1 -w xxxx.gz --noponder`

LZ xxx 0.4k  
`-p400 -g -t1 -w xxxx.gz --noponder`

LZ xxx 0.2k  
`-p200 -g -t1 -w xxxx.gz --noponder`

LZ xxx 0.1k  
`-p100 -g -t1 -w xxxx.gz --noponder`

LZ xxx 0.1k (xxx < 024)  
`-p100 -r1 -g -t1 -w xxxx.gz --noponder`

LZ xxx 0.06k (xxx < 024)  
`-p60 -r1 -g -t1 -w xxxx.gz --noponder`

LZ xxx 0.04k (xxx < 024)  
`-p40 -r1 -g -t1 -w xxxx.gz --noponder`

LZ xxx 0.01k (xxx < 024)  
`-p10 -r1 -g -t1 -w xxxx.gz --noponder`

#### LeelaZero with Leela Master network ####

LZ LM 10BE08 (10blocks,E08)  
`-p1600 -g -t1 -w LeelaMaster_E08.txt --noponder`

LZ LM 15BGX78 (15blocks,GX78)  
`-p1600 -g -t1 -w LeelaMaster_GX78.txt --noponder`

Leela Master networks from [https://github.com/pangafu/LeelaMasterWeight](https://github.com/pangafu/LeelaMasterWeight)

#### LeelaZero with ELF OpenGo network ####

LZ ELF v0  
`-p1600 -g -t1 -w elf_converted_weights_62b5417b.txt --noponder`

LZ ELF v1  
`-p1600 -g -t1 -w elf_converted_weights_d13c4099.txt --noponder`

## Leela Zero 0.15 ##

#### LeelaZero (mod) with PhoenixGo network ####

LZ PhoenixGo v1  
`-p1600 -g -t1 -w PhoenixGo_v1.txt --noponder`  
repo: [https://github.com/yenw/LeelaZero_PhoenixGo](https://github.com/yenw/LeelaZero_PhoenixGo) version: v2_lizzie
