# Transformer Model
## 카카오아레나 쇼핑몰 카테고리 분류
### 한국어 자연언어처리

- train_chunk 1개로 상품명 데이터만 이용
- okt 한국어 형태소 분석기 이용
- 4개의 multi head 이용
- transformer 모델에 encoder부분 이용
- attention value 값으로 scaled dot product 연산 적용
- 정확도 약 0.905

#### 버전
- tensorflow 2.0.0
- keras 2.3.1

#### 데이터
https://drive.google.com/file/d/1tI1IM3Pr8oqkBidL5CQ3Wk76MPxZ6X3t/view?usp=sharing
