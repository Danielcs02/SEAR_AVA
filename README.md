# Comparação de Versões YOLO11 — Detecção de Objetos

Trabalho da disciplina **Sistemas Evolutivos e Aplicados à Robótica** — Universidade Veiga de Almeida (UVA).

## Sobre

Análise comparativa entre cinco variantes do modelo YOLO11 (nano, small, medium, large e extra-large) aplicadas à detecção de objetos em uma imagem urbana, utilizando o COCO Dataset como base de reconhecimento.

## Resultados

| Versão | Tempo (ms) | Total | Carro | Pessoa | Semáforo | Caminhão |
|--------|-----------|-------|-------|--------|----------|----------|
| YOLO11n | 87,1 | 20 | 10 | 8 | 1 | 1 |
| YOLO11s | 63,8 | 21 | 9 | 10 | 1 | 1 |
| YOLO11m | 50,7 | 17 | 8 | 8 | — | 1 |
| YOLO11l | 32,9 | 17 | 8 | 8 | — | 1 |
| YOLO11x | 56,0 | 22 | 12 | 9 | — | 1 |

## Como executar

### Pré-requisitos

- Conta no [Google Colab](https://colab.research.google.com/)
- GPU ativada (Runtime → Change runtime type → T4 GPU)

### Passos

1. Abra o arquivo `notebook.ipynb` no Google Colab
2. Execute as células na ordem (Shift+Enter)
3. Os resultados e imagens anotadas serão gerados automaticamente

### Bibliotecas utilizadas

- [Ultralytics YOLO](https://docs.ultralytics.com/) — framework de detecção de objetos
- [Matplotlib](https://matplotlib.org/) — visualização dos resultados
- [Pillow](https://pillow.readthedocs.io/) — manipulação de imagens

## Estrutura do projeto

```
├── notebook.ipynb    # Notebook principal com os testes
├── README.md         # Este arquivo
```

## Imagem utilizada

Rua urbana em Roma, Itália — obtida na plataforma [Pexels](https://www.pexels.com/photo/a-busy-street-with-cars-and-people-6420697/) (Md Mortoza Ashraf).

## Referências

- [COCO Dataset](https://cocodataset.org/#home)
- [Ultralytics YOLO11 Docs](https://docs.ultralytics.com/models/yolo11/)
- [DataCamp — YOLO Object Detection Explained](https://www.datacamp.com/pt/blog/yolo-object-detection-explained)
