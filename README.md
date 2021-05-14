# 동국대학교 강종렬 석사논문
SentenceTokenizer 클래스 의 text2sentences() 함수에서 kkma 를 이용해서 텍스트를 문장으로 분리
get_nouns() 함수에서 twitter(0kt) 를 이용하여 문장에서 명사 추출, 불용어 제거

GraphMaxrix 클래스 에서 매트릭스 추출
CountVectorize , TF-IDF 계산

위를 바탕으로
Rank 클래스에서 단어별 TextRank 계산 

TextRank 클래스를 통해 텍스트 하나당 10개의 키워드로 추출

동국대학교 공지사항
파일들의 이름(본문 내용, 첨부 내용)을 같게한 후 각각의 첨부파일 형식에서 텍스트 추출 (예: pdf, jpg)
텍스트 추출한 후 해당 단어들을 본문의 단어들과 결합

뉴스 데이터
Google Cloud Vision을 이용하여 뉴스데이터에서는 이미지에서 label을 추출 (Google API 소스 이용)
한국 Wikipedia 기반으로 학습시킨 Word2Vec 모델을 이용하여 label과 키워드 단어들간의 유사도를 구함
이를 본문의 Matrix에 결합


위를 토대로 각각의 키워드 추출 및 저장
