South Korea Population Data
===========================

This repo hosts South Korea population data from the 2010 Census in CSV format.

## Description

### Population data 
South Korean administrative divisions are consisted of three levels:

- [Provincial level (시도)](http://en.wikipedia.org/wiki/Administrative_divisions_of_South_Korea#Provincial_level_divisions): Special City(특별시), Metropolitan City(광역시), Province(도), Special Self-governing Province(특별자치도), Special Self-governing City(특별자치시)
- [Municipal level (시군구)](http://en.wikipedia.org/wiki/Administrative_divisions_of_South_Korea#Municipal_level_divisions): Si (시, city), Gun (군, county), Gu (구, district)
- [Submunicipal level (읍면동)](http://en.wikipedia.org/wiki/Administrative_divisions_of_South_Korea#Submunicipal_level_divisions): Eup (읍, town), Myeon (면, township), Dong (동, neighborhood), Ri (리, village)

### Codebook

## Development notes

1. Get csv files: Downloaded from [KOSIS](http://kosis.kr/abroad/abroad_01List.jsp).
2. Convert encoding: `iconv -f EUC-KR -t UTF-8 [datafile]`
3. The data
    - Provincial (시도): `101_DT_1IN0001_ENG_F_2010_utf8.csv`
    - Municipal (시군구): `01_DT_1IN0001_05_F_2010_utf8.csv`
    - Submunicipal (읍면동): `101_DT_1IN0001_F_2010_utf8.csv`

## Copyright and License

### Author
[Team POPONG](http://en.popong.com).

### Data Source
- Population data are provided by [KOSIS](http://kosis.kr/abroad/abroad_01List.jsp).
- The Codebook is provided by [KOSTAT](http://kostat.go.kr/kssc/board_notice/BoardAction.do?method=view&board_id=3&seq=8&num=8&parent_num=0&page=2&sdate=&edate=&search_mode=&keyword=&position=&catgrp=kssc&catid1=kssc06&catid2=&catid3=&catid4=#startHeader) (in Korean)

### License
<a rel="license" href="http://creativecommons.org/licenses/by/3.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by/3.0/88x31.png" /></a>
