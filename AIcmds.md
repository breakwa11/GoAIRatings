## AmiGo 1.8 ##

AmiGo1.8  
` `

[http://amigogtp.sourceforge.net](http://amigogtp.sourceforge.net)

## aya 6.34 ##

aya 6.34  
`--mode gtp --chinese-rule`

## Dariush 3.1.5.7 ##

DariushGTP3.1.5.7 lv1  
`--level 1 --rules chinese`

DariushGTP3.1.5.7 lv7  
`--level 7 --rules chinese`

[http://ricoh51.free.fr/indexeng.htm](http://ricoh51.free.fr/indexeng.htm)

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

## Go169 1.0 ##

Go169  
` `

[http://www.cis.hut.fi/praiko/go169/](http://www.cis.hut.fi/praiko/go169/)

## gnugo 3.8 ##

gnugo 3.8 lv1  
`--mode gtp --chinese-rules --level 1`

gnugo 3.8 lvX  
`--mode gtp --chinese-rules --level 10`

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

## Leela Zero 0.15 ##

#### LeelaZero (mod) with PhoenixGo network ####

LZ PhoenixGo v1 (256x19blocks)  
`-p1600 -g -t1 -w PhoenixGo_v1.txt --noponder`  
bin: phoenix-orig-mt.exe  
release: [https://github.com/alreadydone/lz/releases/tag/phoenix-v0.33](https://github.com/alreadydone/lz/releases/tag/phoenix-v0.33)

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

LZ xxx 0.06k  
`-p60 -r1 -g -t1 -w xxxx.gz --noponder`

LZ xxx 0.04k  
`-p40 -r1 -g -t1 -w xxxx.gz --noponder`

LZ xxx 0.02k  
`-p40 -r1 -g -t1 -w xxxx.gz --noponder`

LZ xxx 0.01k  
`-p10 -r1 -g -t1 -w xxxx.gz --noponder`

#### LeelaZero with bjiyxo network ####

LZ bjiyxo 15b-195-184k quantized (192x15blocks)  
`-p1600 -g -t1 -w 92297ff22dfa781bd02def6cadafdf7d69e9546300a913faf19e6164b895ed39.gz --noponder`  
download: [here](https://zero.sjeng.org/networks/92297ff22dfa781bd02def6cadafdf7d69e9546300a913faf19e6164b895ed39.gz)

LZ bjiyxo 15b-199-96k quantized (192x15blocks)  
`-p1600 -g -t1 -w f438268ef88e083aaf7a08fba885552818abc08cd0aefce9671954a8df3cf707.gz --noponder`  
download: [here](https://zero.sjeng.org/networks/f438268ef88e083aaf7a08fba885552818abc08cd0aefce9671954a8df3cf707.gz)

LZ bjiyxo 15b-199-240k quantized (192x15blocks)  
`-p1600 -g -t1 -w 83f1bb325920fc1c4866672f5ddd4a4364f3e0f1557fdd6115a6e2d8142d2563.gz --noponder`  
download: [here](https://zero.sjeng.org/networks/83f1bb325920fc1c4866672f5ddd4a4364f3e0f1557fdd6115a6e2d8142d2563.gz)

#### LeelaZero with ELF OpenGo network ####

LZ ELF v0 (224x20blocks)  
`-p1600 -g -t1 -w elf_converted_weights_62b5417b.txt --noponder`

LZ ELF v1 (224x20blocks)  
`-p1600 -g -t1 -w elf_converted_weights_d13c4099.txt --noponder`

LZ ELF v2 (256x20blocks)  
`-p1600 -g -t1 -w elf_converted_weights_05dbca15.txt --noponder`

LZ ELF v0 3.2k (224x20blocks)  
`-p3200 -g -t1 -w elf_converted_weights_62b5417b.txt --noponder`

LZ ELF v1 3.2k (224x20blocks)  
`-p3200 -g -t1 -w elf_converted_weights_d13c4099.txt --noponder`

ELF v0: [download](https://zero.sjeng.org/networks/62b5417b64c46976795d10a6741801f15f857e5029681a42d02c9852097df4b9.gz)

ELF v1: [download](https://zero.sjeng.org/networks/d13c40993740cb77d85c838b82c08cc9c3f0fbc7d8c3761366e5d59e8f371cbd.gz)

ELF v2: [download](https://zero.sjeng.org/networks/05dbca157002b9fd618145d22803beae0f7e4015af48ac50f246b9316e315544.gz)

#### LeelaZero with Leela Master network ####

LZ LM 10BE08 (128x10blocks,E08)  
`-p1600 -g -t1 -w LeelaMaster_E08.txt --noponder`

LZ LM 15BGX78 (192x15blocks,GX78)  
`-p1600 -g -t1 -w LeelaMaster_GX78.txt --noponder`

LZ LM 15BGX78 3.2k (192x15blocks,GX78)  
`-p3200 -g -t1 -w LeelaMaster_GX78.txt --noponder`

LZ LM 15BGX88 (192x15blocks,GX88)  
`-p1600 -g -t1 -w LeelaMaster_GX88.txt --noponder`

LZ LM 15BGX89 (192x15blocks,GX89)  
`-p1600 -g -t1 -w LeelaMaster_GX89.txt --noponder`

LZ LM 15BGX97 (192x15blocks,GX97)  
`-p1600 -g -t1 -w LeelaMaster_GX97.txt --noponder`

Leela Master networks from [https://github.com/pangafu/LeelaMasterWeight](https://github.com/pangafu/LeelaMasterWeight)

#### LeelaZero with minigo network ####

LZ minigo v15 000939 (256x19blocks)  
`-p1600 -g -t1 -w v15_000939.gz --noponder`

LZ minigo v15 000990 (256x19blocks)  
`-p1600 -g -t1 -w v15_000990.gz --noponder`

#### LeelaZero with ZQ network ####

LZ ZQ elf-5 (224x20blocks)  
`-p1600 -g -t1 -w ZQelf-5.gz --noponder`

LZ ZQ elf-2 (224x20blocks)  
`-p1600 -g -t1 -w ZQelf.2.gz --noponder`

LZ ZQ X4 (192x15blocks)  
`-p1600 -g -t1 -w ZQ15BX4.gz --noponder`

LZ ZQ X2 (192x15blocks)  
`-p1600 -g -t1 -w ZQ15B-X2.gz --noponder`

LZ ZQ G5 (192x15blocks)  
`-p1600 -g -t1 -w ZQ-G5.gz --noponder`

LZ ZQ i8 (128x10blocks)  
`-p1600 -g -t1 -w ZQ-i8.gz --noponder`

LZ ZQ F1 (64x5blocks)  
`-p1600 -g -t1 -w ZQ1-F1.gz --noponder`

Reference: QQ group 278743263  
Android APP: [Ah Q Go](https://play.google.com/store/apps/details?id=cn.ezandroid.aq)

#### LeelaZero with other network ####

LZ ManKit Pong 10BF (128x10blocks)  
`-p1600 -g -t1 -w fast_lr_drop_1600k_final.txt --noponder`  
Author: [@godmoves](https://github.com/godmoves)  
SHA256: ED1010C789182D1F401A5198369E0D3A147068C6D5EEDBD3172708A507DECC14

LZ 6b2h (128x6blocks)  
`-p1600 -g -t1 -w 6b2h.txt --noponder`  
Author: unknown  
SHA256: B861162DC9C40B8BCB0554357B9863F2A10704CEF2B9A7BDFEE4743CA30C2E68

LZ S05B064F-C77779D0  
`-p1600 -g -t1 -w S05B064F-C77779D0.txt --noponder`  
Author: unknown  
SHA256: C77779D07C86A10EB4A210ED590F162BD9C9E904B18C500ADD78CA0811F2DDF4  
Original filename: weights 最强-64x5.txt

## MoGo Windows ##

MoGo release3 1k  
`--19 --chinese-rules --nbTotalSimulations 1000`  
download: [http://www.godrago.net/Engines.htm](https://www.godrago.net/Engines.htm)

## pachi ##

#### pachi 12.10 ####

pachi 3k  
`-t =3000:9000 threads=1`

pachi 1k  
`-t =1000:3000 threads=1`

pachi nodcnn 5k  
`--nodcnn -t =5000:15000 threads=1`

pachi nodcnn 3k  
`--nodcnn -t =3000:9000 threads=1`

pachi nodcnn 1k  
`--nodcnn -t =1000:3000 threads=1`

#### pachi 12.20 ####

pachi 12.20 3k  
`-t =3000:9000 threads=1`

pachi 12.20 1k  
`-t =1000:3000 threads=1`

pachi 12.20 nodcnn 5k  
`--nodcnn -t =5000:15000 threads=1`

pachi 12.20 nodcnn 3k  
`--nodcnn -t =3000:9000 threads=1`

pachi 12.20 nodcnn 1k  
`--nodcnn -t =1000:3000 threads=1`

## RN 4.32 ##

RN4.32 0.8k  
`--playout 800 --reuse-subtree --thread 1 --no-debug`

RN4.32 0.4k  
`--playout 400 --reuse-subtree --thread 1 --no-debug`

RN4.32 0.3k  
`--playout 300 --reuse-subtree --thread 1 --no-debug`

RN4.32 0.2k  
`--playout 200 --reuse-subtree --thread 1 --no-debug`

RN4.32 0.1k  
`--playout 100 --reuse-subtree --thread 1 --no-debug`

Github: [https://github.com/zakki/Ray](https://github.com/zakki/Ray)

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
