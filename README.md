# ----Hw2

```python
def main():
    scores = [] 

    for i in range(7):
        score = float(input(f"과목 {i+1}의 점수를 입력하세요: "))
        scores.append(score)

  
    total_score = sum(scores)
    average_score = total_score / len(scores)

    print(f"과목 점수 합계: {total_score}")
    print(f"과목 점수 평균: {average_score:.2f}")

if __name__ == "__main__":
    main()
```
