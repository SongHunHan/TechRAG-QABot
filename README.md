# TechRAG-QABot

TechRAG-QABot은 Langchain, Transformers, RAG(Retrieval-Augmented Generation) 기술을 활용하여 사용자가 입력한 데이터를 기반으로 질문을 생성하고, 생성된 질문에 대한 사용자의 답변을 평가하는 프로젝트입니다.

## 주요 기능

1. **질문 생성**: 사용자가 CSV 파일, URL, 또는 정리된 내용 등을 입력하면 해당 데이터를 분석하여 관련 질문을 자동으로 생성합니다.

2. **답변 평가 및 참조**: 사용자가 생성된 질문에 대한 답변을 입력하면, 시스템은 답변의 정확성을 평가하고 결과를 알려줍니다. 또한, 질문과 관련된 추가 참조 자료를 제공하여 사용자의 학습을 돕습니다. 사용자는 자신이 공부한 내용 중 어느 부분에서 해당 질문이 파생되었는지 확인할 수 있습니다.

## 기술 스택

- Langchain: 자연어 처리 및 질문 생성을 위한 라이브러리
- Transformers: 사전 학습된 언어 모델을 활용하기 위한 라이브러리
- RAG(Retrieval-Augmented Generation): 질문 생성 및 답변 평가를 위한 기술

## 설치 및 사용 방법

1. 레포지토리를 클론합니다.
```
git clone https://github.com/yourusername/TechRAG-QABot.git
```

2. 필요 라이브러리 설치
```
pip install -r requirements.txt
```

3. 프로젝트 실행
```
python main.py
```

4. 프롬프트에 따라 CSV 파일, URL, 또는 정리된 내용을 입력하고 생성된 질문에 답변합니다.

## Contribution Guide

1. Issue를 생성하여 버그를 report하거나 새로운 feature를 제안합니다.
2. Repository를 fork하고 변경 사항을 적용한 후 pull request를 생성합니다.

## License

이 프로젝트는 [MIT License](LICENSE)를 따릅니다.