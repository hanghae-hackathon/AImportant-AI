# AImportant-AI

# 프로젝트 개요
AImportant는 AI를 활용하여 수능 영어 문제와 고등학교 모의고사 영어 문제를 자동으로 풀고, 상세한 분석과 개인 맞춤형 추천을 제공함으로써 학생들의 영어 실력을 향상시키는 것을 목표로 합니다.

# 주요 기능
- AI 수능/모의고사 데이터 학습
- pdf 올리면 자동으로 문제별 텍스트 추출하는 기능
- pdf 중 그래프 문제 이미지 인식

# 사용 기술
- gpt 파인튜닝 - gpt 3.5 활용해서 수능/모의고사를 학습해서 설명 말투를 친절하고 선생님처럼 하였습니다.
- pix2pix : 그래프 이미지를 인식해서 수치 추출
- gpt api 활용해서 답변 받아서 json 저장
