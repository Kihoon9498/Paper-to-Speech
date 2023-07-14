# Project Name : Paper-to-Speech
</br>

## Contents Table
- [문제 상황](#문제-상황)
- [기대 효과](#기대효과)
- [Project 설명](#PROJECT-설명)  
- [모델 설명](#about-model)
- [Dataset](#Dataset)
- [Reference](#Reference) 

---
## 문제 상황

![Alt text](image.png)

- 인공지능 학습 특징
    - 인공지능 분야는 매 년, 매 분기 다양한 구조의 모델이 새롭게 발표된다.
    - 인공지능 학습을 위해 전문화된 특정 교재나 미디어가 존재하지 않는다.
    - 이로 인하여 학습을 위해서는 좋은 결과를 발표한 연구들의 논문으로 학습하는 것이 효율적이며 전문적인 학습이 가능하다!

- 인공지능 학습할 시 어려운 점 
    - 발행되는 논문의 수는 그래프에서 참고할 수 있듯이, 급격하게 늘어나는 추세이다.
    - 논문의 제목만을 바탕으로는 전체적인 내용을 파악하기 어렵다.
    - 언어적 한계로 인해 영어로 작성된 논문을 빠르고 쉽게 이해할 수 없다.

## 기대효과 

- 대중교통( 지하철, 버스 등 )을 이용하여 출퇴근 할 때의 시간이나 남는 시간을 활용하여 논문 내용을 학습할 수 있다.
- 인공지능 분야가 아닌 다른 논문을 학습할 때에도 효율적으로 학습할 수 있다.
- TTS 모델을 학습시킨다면, 원하는 목소리로 내용을 들을 수 있다.

## PROJECT 설명 

![image](https://github.com/Kihoon9498/Paper-to-Speech-/assets/121469546/4a829a6b-df55-490e-8675-55e735fc9550)

논문의 정보를 쉽게 파악할 수 있도록 영어/한국어로 된 논문 내용을 한국어 음성 파일로 변환시켜 학습할 수 있게 해주는 프로젝트

## ABOUT MODEL

### Summarization(Eng)
- Hugging Face / [Facebook(Bart-large-cnn)](https://huggingface.co/facebook/bart-large-cnn)

BART model
: 

### Summarization(Kor)
- GitHub / [SKT-AI(KoBART)](https://github.com/SKT-AI/KoBART)

KoBART model
:

### Translation(Eng to Kor)
- Hugging Face / [facebook(nllb-200-distilled-600M)](https://huggingface.co/facebook/nllb-200-distilled-600M)



### TTS (Text To Speech)
- Hugging Face / [tensorspeech(tts-tacotron2-ljspeech-en)](https://huggingface.co/tensorspeech/tts-tacotron2-ljspeech-en)

Tacotron2 model
: 


## Dataset
AIHub - [논문자료 요약](https://aihub.or.kr/aihubdata/data/view.do?currMenu=&topMenu=&aihubDataSe=realm&dataSetSn=90)

- 3만개의 원문 / Summary 데이터 이용


## Enviroment

| Env |CPU | GPU | RAM | OS 
|:--:|:--:|:--:|:--:|:--:|
| Local | i5- 10400F | RTX-3080(12G) | 32G| Window10 |
| AWS |  AMD-EPYC-7R32 | RTX-3090| 12G| Ubuntu |
| Colab + | intel Xeon | A100 | 80G | Ubuntu |
