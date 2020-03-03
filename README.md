# Dikdörtgenin alanını bulan program

```
# -*- coding: utf-8 -*-
def dikdortgenAlan(genislik,yukseklik):
    alan = float(genislik)* float(yukseklik)
    print "Alan : ", alan
    return alan
gen=input("Genişlik: ")
yuk=input("Yükseklik: ")
dikdortgenAlan(gen,yuk)
