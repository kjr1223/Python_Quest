# Code Peer Review Templete

- 코더 : 김재림
- 리뷰어 : 차정은

---

# PRT(PeerReviewTemplate)

각 항목을 스스로 확인하고 체크하고 확인하여 작성한 코드에 적용하세요.

- [ ] 코드가 정상적으로 동작하고 주어진 문제를 해결했나요?
- [ ] 주석을 보고 작성자의 코드가 이해되었나요?
- [x] 코드가 에러를 유발할 가능성이 있나요?
- [x] 코드 작성자가 코드를 제대로 이해하고 작성했나요? (직접 인터뷰해보기)
- [x] 코드가 간결한가요?

---

# 예시

1. 코드의 작동 방식을 주석으로 기록합니다.

2. 코드의 작동 방식에 대한 개선 방법을 주석으로 기록합니다.

3. 참고한 링크 및 ChatGPT 프롬프트 명령어가 있다면 주석으로 남겨주세요.
   
```python
from google.colab import drive
drive.mount('/content/drive')

## 구글 코랩에서 파일 입력 받는 방법에서 헤매셨던 것 같습니다. 
## 드라이브 마운트까지는 성공해서 드라이브에 txt 파일 업로드하고 파일 입력 하는 방법까지 같이 리뷰 진행했습니다. 
## 그 뒤에 단계 진행하셔보면 좋을 것 같네요!

```


---

# 참고 링크 및 코드 개선 여부

```python
with open('파일경로', 'r') as file:         # 파일 입력 받는 방법
    for line in file:
        print(line)

```
