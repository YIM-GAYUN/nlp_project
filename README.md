## NLP PROJECT
Team6 </br>
파일 설명: </br></br>
### <평가 반영 파일> </br>
<strong>1. run.ipynb:</strong></br>
main file로 코드 세번째 블럭의 user settings 관련 다음 설정에 유의해야 합니다. </br>
```python
# ⚠️🚨 [이 부분 api key 또는 경로 변경 필요합니다!!] 🚨⚠️
UPSTAGE_API_KEY = "your-api-key"
EWHA_EMB_PATH      = "./ewha_embeddings.npz"        # 첨부한 이화학칙 임베딩 파일
MMLU_WIKI_EMB_PATH = "./mmlu_wiki_embeddings.npz"   # 첨부한 MMLU 위키 임베딩 파일
TESTSET_PATH       = "./testset.csv"                # 주어진 testset.csv
OUTPUT_PATH        = "./6_final.csv"                # 결과 저장 경로
# ⚠️🚨 [이 부분 api key 또는 경로 변경 필요합니다!!] 🚨⚠️
```
</br>
<strong>1-1. UPSTAGE_API_KEY:</strong></br>
본인의 upstage api key를 입력해주시면 됩니다. </br></br>
<strong>1-2. EWHA_EMB_PATH:</strong></br>
ewha_embeddings.npz 파일을 다운받아 저장한 경로를 입력해주시면 됩니다. </br></br>
<strong>1-3. MMLU_WIKI_EMB_PATH:</strong></br>
mmlu_wiki_embeddings.npz 파일을 다운받아 저장한 경로를 입력해주시면 됩니다. </br>
mmlu_wiki_embeddings.npz 파일의 경우 용량 문제로 인하여 다음 구글 드라이브 링크로 대신합니다: </br>
https://drive.google.com/file/d/15MtM9OKmCgp-SLBkXc6gK01Ivw5fpKeS/view?usp=drive_link
</br></br>

<strong>2. ewha_embeddings.npz:</strong></br>
위 코드에 사용되는 이화 학칙 임베딩 파일입니다. </br></br>

---

### <참고 파일>
<strong>ewha_embedding.ipynb:</strong> 이화 학칙 임베딩 코드 (처리) 파일 </br>
<strong>mmlu_embedding.ipynb:</strong> mmlu 데이터 임베딩 코드 (처리) 파일 </br>
<strong>requirements.txt:</strong> 로컬에서 실행할 시 필요한 라이브러리 </br>

