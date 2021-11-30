# Machine_LearningStudy


## recall/precision 개념
 <img width="479" alt="스크린샷 2021-11-29 오후 11 21 08" src="https://user-images.githubusercontent.com/50222603/143884615-1b369b35-34d9-4fff-9fc4-05ad168ff518.png">
  
  * recall(재현율)
    * 실제 True인 것 중에서 true로 예측한 것의 비율
    * ex) recall of positive
      * of correct prediction positive / of the real positive
      * tp / (tp+fp)

  * precision(정확도)
    * True로 예측 한 것 중에서 True로 예측한 것의 비율
    * ex) precision of positive
      * of correct prediction positive / of predictive positive
      * tp / (tp+fn)

## one - hot encoding
<img width="693" alt="스크린샷 2021-11-30 오후 10 00 50" src="https://user-images.githubusercontent.com/50222603/144052051-df9888af-909f-4f0a-8d93-b10b08ac2c4f.png">


 * 원-핫 인코딩은 간단히 말해 한 개의 요소는 True, 나머지 요소는 False로 만들어 주는 기법이다.
 * scikit-learn에서 제공하는 머신러닝 알고리즘은 문자열 값을 입력 값으로 허락하지 않기 때문에 모든 문자열 값들을 숫자형으로 인코딩하는 전처리 작업(Preprocessing) 후에 머신러닝 모델에 학습을 시켜야 한다.
 * pandas의 get_dummies 사용
 * linear_model에서 get_dummies를 사용하면 Target columns should be dropped in dataframe 을 하나씩 해줘야된다.
