South Korea Population Data
===========================

This repo hosts South Korean population data from the 2010 Census in CSV format.

## Description

### Population data 
The census data was gathered in 2010.
South Korean administrative divisions are consisted of three levels:

- [Provincial level (시도)](http://en.wikipedia.org/wiki/Administrative_divisions_of_South_Korea#Provincial_level_divisions): Special City(특별시), Metropolitan City(광역시), Province(도), Special Self-governing Province(특별자치도), Special Self-governing City(특별자치시)
- [Municipal level (시군구)](http://en.wikipedia.org/wiki/Administrative_divisions_of_South_Korea#Municipal_level_divisions): Si (시, city), Gun (군, county), Gu (구, district)
- [Submunicipal level (읍면동)](http://en.wikipedia.org/wiki/Administrative_divisions_of_South_Korea#Submunicipal_level_divisions): Eup (읍, town), Myeon (면, township), Dong (동, neighborhood), Ri (리, village)

### Codebook
This codebook was written in April, 2010.

1. `codenames-20100401.csv`: Raw data
1. `codenames-20100401-06-translation.csv` : Regional names' English, Chinese translation

## Development notes
Raw data are in `2010/*.csv`.
Data converted to UTF-8 are in `2010/*_utf8.csv`.

## Copyright and License

### Author
[Team POPONG](http://en.popong.com).

### Data Source
- Population data are provided by [KOSIS](http://kosis.kr/abroad/abroad_01List.jsp).
- Codebooks are provided by [KOSTAT](http://kostat.go.kr/kssc/board_notice/BoardAction.do?method=view&board_id=3&seq=8&num=8&parent_num=0&page=2&sdate=&edate=&search_mode=&keyword=&position=&catgrp=kssc&catid1=kssc06&catid2=&catid3=&catid4=#startHeader) (in Korean)

### License
<a rel="license" href="http://creativecommons.org/licenses/by/3.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by/3.0/88x31.png" /></a>
