# GST Tacotron2 KOREAN

## DATA
### 1. Dataset 
  * [Korean Speech Emotion Dataset](http://aicompanion.or.kr/kor/main/)
  * Single Female Voice Actor recorded six diffrent emotions(neutral, happy, sad, angry, disgust, fearful), each with 3,000 sentences. Total 30 hours

### 2. Text
 * Using [korean_cleaner](https://github.com/Yeongtae/tacotron2/tree/master/text)
 * Using jamo
  ```
    안녕하세요.
     ==>
     ㅇㅏㄴㄴㅕㅇㅎㅏㅅㅔㅇㅛ 
   ```

### 3. Audio
    * sampling rate: 16000
    * filter length: 1024
    * hop length: 256
    * win length: 1024
    * n_mel: 80
    * mel_fmin: 0
    * mel_fmax: 8000

### 4. file list
 * path | text
 ```
dataset/hap/wav/acriil_hap_00003104.wav|경암은 푸른 수풀 속에 거뭇거뭇 보이는 높은 기와집들을 손가락질로 가리키며 자랑스런 얼굴로 무어라고 중얼거렸다.
dataset/neu/wav/acriil_neu_00000097.wav|모든 것을 공개할 수 없으나 앞으로 국민화합과 화해조치들을 강구해 나갈 것이다.
dataset/fea/wav/acriil_fea_00002629.wav|우리집 개와 고양이는 사이가 좋다.
 ```

## Training
