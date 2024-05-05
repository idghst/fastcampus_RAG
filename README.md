# fastcampus_RAG

## 실습 내용

### Part 2 RAG with LlamaIndex

---

#### 구현 실습

##### LlamaIndex with ChatGPT

[Part2_RAG_with_LlamaIndex_01_basic_ChatGPT.ipynb](./notebooks/Part2_RAG_with_LlamaIndex_01_basic_ChatGPT.ipynb) <br/>
[Part2_RAG_with_LlamaIndex_02_basic_LlamaIndex.ipynb](./notebooks/Part2_RAG_with_LlamaIndex_02_basic_LlamaIndex.ipynb) <br/>
[Part2_RAG_with_LlamaIndex_03_RAG_ChatGPT.ipynb](./notebooks/Part2_RAG_with_LlamaIndex_03_RAG_ChatGPT.ipynb) <br/>
[Part2_RAG_with_LlamaIndex_04_RAG_LlamaIndex.ipynb](./notebooks/Part2_RAG_with_LlamaIndex_04_RAG_LlamaIndex.ipynb) <br/>

##### LlamaIndex with Local LLM

[](./)

---

#### 모델 서빙

##### API 만들기
[Part2_rag_api.py](./codes/Part2_rag_api.py)

##### 데모 페이지 만들기
[Part2_rag_st.py](./codes/Part2_rag_st.py)

---

### Part 3 RAG with LangChain

---

#### 구현 실습

##### LangChain with ChatGPT
[](./)

##### LangChain with Local LLM
[](./)

##### LangChain with Ollama
[](./)

##### LangGraph
[](./)

---

#### 모델 서빙

##### API + 데모 페이지 만들기
[](./)

---

## 가상환경 설정

```bash
# 가상환경 설치

python -m venv [가상환경폴더명]
# ex) python -m venv venv
```

```bash
# 가상환경 활성화

source venv/bin/activate
```

```bash
# dependency 설치

pip install [설치항목] # 개별 설치
pip install -r requirements.txt # 일괄 설치
```

```bash
# dependency 백업

pip freeze > requirements.txt
```

```bash
# 가상환경 비활성화

deactivate
```
