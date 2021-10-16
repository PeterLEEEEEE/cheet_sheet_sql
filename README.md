# cheet_sheet_sql

### SQL RANK 함수
3가지의 RANK 함수 존재
1. RANK() OVER
- 중복이 있으면 반영하여 순위 매김, 공동 1등이 존재하면 그 다음은 3등, (1 - 1 - 3)
2. DENSE_RANK() OVER
- 중복에 관계없이 순서대로 순위 매김, 공동 1등이 있어도 다음은 2등, (1 - 1 - 2)
3. ROW_NUMBER() OVER
- 중복이 있어도 순위는 순서대로 매김, (1 - 2 - 3)
