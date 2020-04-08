# howls_nlp

### doc2vec기반 vector 유사도를 이용한 유사한 질문 추천기

### 에타 조교(학사 행정 관련한 QnA 게시판, everytime) 내용 크롤링(질문과 답변). 크롤링 데이터로 코퍼스 구축 후 전처리

### gensim의 doc2vec 모델로 코퍼스를 학습하여 모든 document(질문들)를 vectorize

### 질문을 입력받아 학습한 모델로 vectorize, 생성된 vector를 질문들의 vector와 유사도 비교하여 상위 10개 추출

### 크롤링한 데이터셋의 답변과 연동하여 상위 10개의 질문-답 쌍 출력 
