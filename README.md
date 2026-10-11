# FarmTech Vision | FIAP - Fase 6

## Sobre o projeto
Projeto acadêmico desenvolvido na FIAP, com foco em Inteligência Artificial e Visão Computacional para identificação e localização de objetos em imagens, utilizando YOLO.

## Objetivo
Desenvolver e avaliar um modelo capaz de detectar duas classes de produtos: Coca-Cola e cereal Nescau.

## Tecnologias utilizadas
- Python
- Google Colab
- Ultralytics YOLO
- Redes Neurais Convolucionais (CNN)
- OpenCV e bibliotecas de visualização e análise
- Make Sense AI para anotação das imagens
- GitHub para documentação e versionamento

## Dataset
Foram utilizadas 80 imagens, distribuídas em:
- 64 imagens para treinamento
- 8 imagens para validação
- 8 imagens para teste

As duas classes utilizadas foram `Coca_Cola` e `Cereal`.

## Metodologia
1. Coleta e organização das imagens.
2. Anotação dos objetos com caixas delimitadoras.
3. Preparação do dataset no formato YOLO.
4. Treinamento e comparação de modelos com 30 e 60 épocas.
5. Avaliação quantitativa e análise visual das detecções.

## Resultados - YOLO com 60 épocas

| Métrica | Resultado |
|---|---:|
| Precision | 0,957 |
| Recall | 0,927 |
| mAP50 | 0,938 |
| mAP50-95 | 0,786 |

O experimento apresentou resultados promissores nas condições avaliadas. Entretanto, o tamanho reduzido do dataset limita a generalização das conclusões.

## Entregas
- **Entrega 1:** preparação dos dados, treinamento e avaliação do modelo YOLO.
- **Entrega 2:** análises comparativas, avaliação dos resultados e experimentos adicionais documentados no notebook.

## Notebook
Consulte o arquivo `FarmTech_Vision_Fase6_pbl_fase6.ipynb` neste repositório para visualizar o código, os experimentos e as análises.

## Considerações finais
O projeto permitiu aplicar conceitos de visão computacional, detecção de objetos, treinamento e avaliação de modelos de Inteligência Artificial. Como trabalhos futuros, recomenda-se ampliar e diversificar o conjunto de imagens e realizar novos testes com dados independentes.

## Instituição
FIAP - Tecnólogo em Inteligência Artificial | Fase 6
