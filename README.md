# 동국대학교 강종렬 석사논문
설정된 불용어들을 제거 후 텍스트를 문장 분리, 형태소 분석 후 명사 추출
CountVectorizer 후 TextRank 계산  

동국대학교 공지사항
파일들의 이름을 같게한 후 각각의 형식에서 텍스트 추출 (예: pdf, jpg)
텍스트 추출한 후 해당 단어들을 본문의 단어들과 결합

뉴스 데이터
Google Cloud Vision을 이용하여 뉴스데이터에서는 이미지에서 label을 추출 (Google Cloud 소스 이용)
한국 Wikipedia 기반으로 학습시킨 Word2Vec 모델을 이용하여 label과 키워드 단어들간의 유사도를 구함
이를 본문의 Matrix에 결합


위를 토대로 각각의 키워드 
