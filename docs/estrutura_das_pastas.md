projeto-ia_classificacao_de_imagem/
├── data/
│   ├── raw/                # Dados originais (brutos) baixados.
│   ├── processed/          # Dados limpos e prontos para análise/modelagem.
│   ├── datasets.md         # Informações e links sobre os datasets usados.
├── notebooks/
│   ├── 01-exploracao.ipynb # Notebook de exploração de dados.
│   ├── 02-treinamento.ipynb # Notebook para treinamento do modelo.
│   ├── 03-avaliacao.ipynb  # Notebook para avaliação e análise de resultados.
├── models/
│   ├── checkpoints/        # Checkpoints de treinamento salvos.
│   ├── final_model.pkl     # Modelo final treinado.
│   ├── huggingface_model/  # Diretório para modelos baixados do Hugging Face.
├── src/
│   ├── data_preprocessing.py # Scripts de pré-processamento dos dados.
│   ├── train.py             # Script para treinamento do modelo.
│   ├── evaluate.py          # Script para avaliação do modelo.
│   ├── utils.py             # Funções auxiliares utilizadas no projeto.
├── tests/
│   ├── test_preprocessing.py # Testes para as funções de pré-processamento.
│   ├── test_model.py         # Testes para o modelo treinado.
├── docs/
│   ├── README.md            # Documentação do projeto.
│   ├── estrutura_pastas.md  # Explicação sobre a organização das pastas.
├── results/
│   ├── logs/                # Logs de treinamento e execução.
│   ├── visualizations/      # Gráficos e análises geradas.
│   ├── metrics.json         # Métricas de avaliação do modelo.
├── environment/
│   ├── requirements.txt     # Dependências do projeto.
│   ├── environment.yml      # Arquivo para configuração do ambiente Conda.
├── .gitignore               # Arquivo para ignorar arquivos/pastas no Git.
├── LICENSE                  # Licença do projeto.
└── README.md                # Descrição principal do projeto.
