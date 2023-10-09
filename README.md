# Knowledge-Graph

## 진행사항 및 결과

- 도전학기제 프로젝트 : 한국어 지식 그래프 구축 과정 기록

- 네이버 경제 뉴스 크롤링으로 데이터 추출
- Konlpy의 Komoran, Hannanum, Kkma, Okt으로 pos tagging, 관계 추출을 위해 명사구와 동사 추출
- 한국어 사전학습 모델 kcbert-base를 huggingface에서 가져와 Transfer Learning
- pos tagging, position embedding 기반 neural-network model 구축 시도
- modeling에는 실패, python matplotlib와 networkX를 사용해 명사와 명사를 결합하고, 관계 추출로 프로젝트 마무리

## 한계점 
- co-reference(상호 참조 - 대명사 문제)
- extraction entity&relationship(개체와 관계를 동시에 추출하는 방식이 필요)
- 경제 데이터셋 추가 : 국립국어원 "모두의 말뭉치"
- 선행 연구 조사 : 문장 구조, 패턴에 대한 연구 및 positioning 관련 방법론 탐색
