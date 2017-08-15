# LegalNoticeMaker
OSS 고지문 작성
forked from [ppiazi/LegalNoticeMaker](https://github.com/ppiazi/LegalNoticeMaker)

## 필요사항
### python3
macOS
```
brew install python3
```
### jinja2
```
pip3 install jinja2
```

## 사용법
0. 내려받기
```
git clone --recursive https://github.com/rajephon/LegalNoticeMaker
```
1. swinfo.csv 작성
2. data.csv 작성
3. LegalNoticeMaker.py 동작
```
python3 ./LegalNoticeMaker.py -s swinfo.csv -d data.csv
```
