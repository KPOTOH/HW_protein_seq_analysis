# HW_protein_seq_analysis
Comparison of classification methods of protein classes

[Colab notebook](https://colab.research.google.com/drive/166LLGFs_-A2iKPHYan8aNRrDNE3Q0tiA?usp=sharing) чтоб удобней смотреть, однако там не видна часть графиков


## Обзор ресурсов

[пеперы про ML в белках](https://github.com/yangkky/Machine-learning-for-proteins#classification-and-annotation)

- [ProtLearn](https://github.com/tadorfer/ProtLearn) - либа базовых фичь и индексов. **Используем ее для генерации признаков для классификации**
- [embedding - есть модель, но непонятно](https://github.com/tbepler/protein-sequence-embedding-iclr2019)
- [tape embedding](https://github.com/songlab-cal/tape) -  - что-то шикарное, берт на белках. Удобная либа - **работает**. Используем эмбеддинги для сравнения
- [bio_embeddings](https://github.com/sacdallago/bio_embeddings)  - тоже что-то хорошее с интерфейсом.  **не устанавливается в колаб**
- [подход с LSTM, точнее они придумали лучшее решение на CNN](https://github.com/ronakvijay/Protein_Sequence_Classification)
- []()
- [shap](https://github.com/slundberg/shap) - оценщик бустинга. **оцениваем им значимость индексов для классов белков**
