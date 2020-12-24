# Sentiment-Analysis

빅데이터자연어처리기술
기말고사 감정분석기 과제

## 1.   데이터셋

 Naver sentiment movie corpus v1.0

  (https://github.com/e9t/nsmc)
 

## 2.   실험모델

*   LSTM
*   bi-LSTM
*   KoBERT
*   KoELECTRA

## 3.   추가데이터
*   KNU 감성사전

    (https://github.com/park1200656/KnuSentiLex)


## 4. 각 모델별 전처리 방식

실험 모델|전처리|모델|
|------|---|---|
|LSTM|KoNLPy PyKomoran|LSTM|
|bi-LSTM|KoNLPy PyKomoran|bi-LSTM|
|KoBERT|BERT_Tokenizer(get_tokenizer) |KoBERT의 get_pytorch_kobert_model|
|KoELECTRA|koelectra-base-v3-discriminator|koelectra-base-v3-discriminator|

## 5. 참고자료

