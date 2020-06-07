# 판다스 스터디 데이터 자료입니다.

"데이터분석을 위한 판다스입문" 이라는 책을 공부하며 Google Colab 에서 사용하기 위한 약간의 수정을 거쳤습니다.
아래 코드를 맨 상단에 추가하여 사용하세요. 깃허브에서 데이터를 읽어와서 colab 에 넣는 코드입니다. 

abcde

```
try:
    if upload == True:
        print('Data Uploaded')
    else :
        print('Data uploaded Error')
except :
    upload = False
    !git clone https://github.com/MLBasic/pandasBasicStudyData.git
    %cd /content/pandasBasicStudyData/notebook/
    upload = True
```
		
		