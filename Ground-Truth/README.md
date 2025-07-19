
## Ground Truth

RAG 정량적 평가를 위해 Agent로 생성한 GT입니다.

GT 하나당 초기 수집해놓은 채용공고 데이터셋에서 채용 공고를 랜덤으로 선택한 후 유사도가 높은 4개의 채용 공고를 추가하여 총 5개의 채용공고를 선별합니다.
Agent는 5개의 채용 공고를 확인한 후 해당 채용 공고에 지원했을 법한 학생 프로필 데이터를 생성합니다.
이때 한양대학교 수강편람 데이터를 검색할수 있는 api를 tool로 이용합니다.

학생 프로필 데이터는 총 105개입니다.

<img width="1684" height="784" alt="image" src="https://github.com/user-attachments/assets/a42e8fc3-4b47-4a4e-a0f7-f9955cb81340" />
