# SQL 집합 함수

## COUNT

`COUNT`는 데이터 개수를 반환합니다.

```sql
SELECT COUNT(*) FROM users;
```

테이블의 전체 행 개수를 반환합니다.

### NULL 제외

```sql
SELECT COUNT(name) FROM users;
```

`name` 컬럼의 NULL이 아닌 값 개수를 반환합니다.

---

## SUM

`SUM`은 숫자 데이터의 합계를 구합니다.

```sql
SELECT SUM(price) FROM products;
```

모든 `price` 값을 더한 결과를 반환합니다.

---

## AVG

`AVG`는 평균값을 구합니다.

```sql
SELECT AVG(score) FROM students;
```

학생 점수 평균을 반환합니다.

NULL 값은 자동 제외됩니다.

---

## MAX

`MAX`는 가장 큰 값을 반환합니다.

```sql
SELECT MAX(score) FROM students;
```

가장 높은 점수를 반환합니다.

---

## MIN

`MIN`은 가장 작은 값을 반환합니다.

```sql
SELECT MIN(score) FROM students;
```

가장 낮은 점수를 반환합니다.
