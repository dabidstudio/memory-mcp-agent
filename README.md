


# 장기기억 AI Agent

## 메모리 작동방식
<img src="https://github.com/user-attachments/assets/8f32577d-2207-44e1-8cc3-93b820dd8654" width="600">

## 설치 방법

1. 필수 패키지 설치  
   ```bash
   uv add openai-agents openai streamlit python-dotenv 
   ```

2. 환경 변수 파일(.env)을 생성한 후, [mem0](https://mem0.ai/old-home)와 OpenAI API 키를 입력하기
   ```env
   OPENAI_API_KEY=여기에_발급받은_키_입력
   MEM0_API_KEY=여기에_발급받은_키_입력
   ```

## 실행

   ```bash
   uv run streamlit run agent.py
   ```


