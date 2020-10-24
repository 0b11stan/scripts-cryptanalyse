# 0b11stan cryptanalysis scripts

Those are scripts for solving ctfs and other crypto challenges.

## decipher_caesar.py

```
usage: ./decipher_caesar.py KEY CIPHERTEXT
```

* `KEY`: un chiffre compris entre 1 et 26
* `CIPHERTEXT`: un **ciphertext** (ASCII + espaces only)

Exemple d'utilisation classique :
```bash
$ for x in {1..26}; do echo -n "$x "; ./decipher_caesar.py $x lnbja nbc dw lqrooanvnwc canb ojrkun; done
 1 KMAIZ MAB CV KPQNNZMUMVB BZMA NIQJTM 
 2 JLZHY LZA BU JOPMMYLTLUA AYLZ MHPISL 
 3 IKYGX KYZ AT INOLLXKSKTZ ZXKY LGOHRK 
 4 HJXFW JXY ZS HMNKKWJRJSY YWJX KFNGQJ 
 5 GIWEV IWX YR GLMJJVIQIRX XVIW JEMFPI 
 6 FHVDU HVW XQ FKLIIUHPHQW WUHV IDLEOH 
 7 EGUCT GUV WP EJKHHTGOGPV VTGU HCKDNG 
 8 DFTBS FTU VO DIJGGSFNFOU USFT GBJCMF 
 9 CESAR EST UN CHIFFREMENT TRES FAIBLE # KEY and PLAINTEXT
10 BDRZQ DRS TM BGHEEQDLDMS SQDR EZHAKD 
11 ACQYP CQR SL AFGDDPCKCLR RPCQ DYGZJC 
12 ZBPXO BPQ RK ZEFCCOBJBKQ QOBP CXFYIB 
13 YAOWN AOP QJ YDEBBNAIAJP PNAO BWEXHA 
14 XZNVM ZNO PI XCDAAMZHZIO OMZN AVDWGZ 
15 WYMUL YMN OH WBCZZLYGYHN NLYM ZUCVFY 
16 VXLTK XLM NG VABYYKXFXGM MKXL YTBUEX 
17 UWKSJ WKL MF UZAXXJWEWFL LJWK XSATDW 
18 TVJRI VJK LE TYZWWIVDVEK KIVJ WRZSCV 
19 SUIQH UIJ KD SXYVVHUCUDJ JHUI VQYRBU 
20 RTHPG THI JC RWXUUGTBTCI IGTH UPXQAT 
21 QSGOF SGH IB QVWTTFSASBH HFSG TOWPZS 
22 PRFNE RFG HA PUVSSERZRAG GERF SNVOYR 
23 OQEMD QEF GZ OTURRDQYQZF FDQE RMUNXQ 
24 NPDLC PDE FY NSTQQCPXPYE ECPD QLTMWP 
25 MOCKB OCD EX MRSPPBOWOXD DBOC PKSLVO 
26 LNBJA NBC DW LQROOANVNWC CANB OJRKUN
```

