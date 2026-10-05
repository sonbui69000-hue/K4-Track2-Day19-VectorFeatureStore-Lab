# Reflection — Lab 19

**Tên:** Bui Le Thai Son
**MSSV:** 02880
**Cohort:** _<A20-K4>_
**Path đã chạy:** lite

---

## Câu hỏi (≤ 200 chữ)

> Trên golden set 50 queries, mode nào thắng ở loại query nào (`exact` /
> `paraphrase` / `mixed`), và tại sao? Khi nào bạn **không** dùng hybrid
> (i.e. khi nào pure BM25 hoặc pure vector là lựa chọn đúng)?

BM25 is strongest for exact queries because it matches the same words.
Vector search is strongest for paraphrase queries because it matches meaning.
Hybrid search is strongest for mixed queries because it combines both signals.
Would not use hybrid when queries are only exact identifiers, error codes,
or short keywords. Pure BM25 is simpler and faster there. Would use pure
vector search for natural language questions where wording changes often.

---

## Điều ngạc nhiên nhất khi làm lab này

The best search mode depends on the query type. One mode is not always best.

---

## Bonus challenge

- [ ] Đã làm bonus (xem `bonus/`)
- [ ] Pair work với: _<tên đồng đội nếu có>_
