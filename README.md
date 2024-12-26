# Трансформер для генерации русскоязычного диалога

## Здесь представлен трансформер, построенный на основе статьи "Attention is all you need" с кастомным токенизатором (созданным вручную, не из репозиториев) и обученный на русском датасете пар вопрос-ответ

### Использован следующий стек технологий:

Hugging face, transformers, tensorflow (tensorflow, text, tfds), pathlib, matplotlib, numpy, pandas

За основу взят датасет из HF Den4ikAI/russian_dialogues, который был обработан, токенизирован с помощью кастомного токенизатора (на основе BertTokenizer). Затем собрана модель и обучена. Референс оценивается хорошим
