# LegalNoticeMaker
OSS 고지문 작성
forked from [ppiazi/LegalNoticeMaker](https://github.com/ppiazi/LegalNoticeMaker)
ppiazi님 버전에서 본인의 필요에 의하여 단지 가벼운 수정과 HTML 템플릿 형태로 바꾼 것 뿐입니다.

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

## LICENSE
Apache-2.0
