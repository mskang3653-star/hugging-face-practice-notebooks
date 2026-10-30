# Hugging Face in Practice — Notebooks

Hugging Face Transformers 실습 과제(08-1 ~ 08-4)입니다.

## 구성

- `08-1 Pipelines and the Hub.ipynb`: pipeline, Hugging Face Hub, 감정 분석과 여러 NLP task
- `08-2 Tokenizers and Models.ipynb`: tokenizer, model 입력, hidden states, language-model loss
- `08-3 Generation and Chat Templates.ipynb`: greedy/sampling generation, chat template, response-only loss
- `08-4 Datasets and the Trainer.ipynb`: Datasets, tokenization, Trainer를 이용한 분류 학습과 평가

## 실행 환경

```bash
python -m pip install -r requirements.txt
```

노트북 첫 번째 셀에서도 필요한 패키지를 설치합니다. Apple Silicon Mac에서는 PyTorch의 `mps` 장치를 사용할 수 있습니다.

## 주의

모델과 데이터셋은 노트북 실행 중 Hugging Face Hub에서 다운로드됩니다. `my-smollm2/`는 08-2에서 저장한 약 1.4GB의 로컬 모델 사본이므로, 이 과제 저장소에는 포함하지 않았습니다.
