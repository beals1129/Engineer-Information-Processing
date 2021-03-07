
# .MD 사용해보기






---
## 데이터 정의어 (DDL) 



### CREATE

1. 스키마 정의 / 설정
- 형식 : `CREATE` `SCHEMA` 스키마명 `AUTHORIZATION` 사용자 ID;

2. 도메인 정의 
- 형식 : `CREATE` `DOMAIN` 도메인명 데이터타입
    [ `DEFAULT` 기본값 ] //기본값을 표시하라고 명시되었을 때 사용
    [ `CONSTRAINT` 제약조건명(도메인 이름에 대한 제약조건의 이름) `CHECK` (범위값) ];

3. 테이블 정의
- CREATE TABLE 기본테이블 명  
    (
    | 속성 |
    |---|
    | PRIMARY KEY (기본키 속성) |
    | UNIQUE (대체키 속성) |
    | FOREIGN KEY(외래키 속성) |
    | REFERENCES 참조하는 테이블명 (기본키 속성) |  

    )


    # 그냥 손필기로 공부합니다..
