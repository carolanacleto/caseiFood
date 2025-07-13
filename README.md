### 📌 Instruções
Todo o processo de carregamento, tratamento das bases, análise exploratória e modelagem estatística foi realizado na plataforma Databricks Community Edition.

Notebooks desenvolvidos (disponíveis neste repositório):
- [iFood] Data Analysis _ Prepare Data.ipynb – Etapas de limpeza, transformação e preparação das variáveis. Link Databricks: https://dbc-821fdc49-4774.cloud.databricks.com/editor/notebooks/3372752459351212?o=1434825530295015#command/7160234885973343
- [iFood] Data Analysis _ Analyse Data.ipynb – Análise exploratória, segmentações e modelo estatístico aplicado. Link Databricks: https://dbc-821fdc49-4774.cloud.databricks.com/editor/notebooks/710778929764000?o=1434825530295015

- Devido ao tamanho e peso da base de pedidos (order), foi necessário fazer o download dos arquivos separados, realizar a leitura individual de cada parte e, em seguida, unificá-los dentro do Databricks para formar a base final utilizada na análise.

### Como reproduzir os notebooks no seu ambiente Databricks: 
Como os notebooks foram desenvolvidos dentro do meu ambiente pessoal no Databricks Community Edition, eles não podem ser executados diretamente por outros usuários. Para reproduzi-los no seu próprio ambiente Databricks, siga os passos abaixo:
1) Faça o download dos arquivos de dados, através dos links forncecidos no case.
2) No Databricks, acesse a aba lateral "Data" e clique em "Add Data" > "Upload File".
3) Faça o upload dos arquivos necessários para dentro da plataforma.
4) Após o upload, os arquivos serão armazenados em um caminho como: /dbfs/FileStore/tables/nome_do_arquivo.csv
5) No código, substitua os caminhos locais por este caminho do Databricks. Exemplo: df = pd.read_csv("file:/dbfs/FileStore/tables/nome_do_arquivo.csv")


### Relatórios disponíveis neste repositório:

[iFood] Relatório Final - Case Técnico de Data Analysis.pdf:
documento completo e detalhado, com todo o raciocínio técnico desenvolvido ao longo do projeto. Ideal para discussões entre áreas de dados e negócios, com foco analítico.

[iFood] Relatório Executivo - Case Técnico de Data Analysis.pdf:
versão mais concisa e objetiva, voltada para apresentações executivas. Recomendado para lideranças e áreas tomadoras de decisão, com foco em insights e recomendações práticas.


### Observação:
Gostaria de ser totalmente transparente com vocês:
Os testes estatísticos e a modelagem realizados nesta análise foram inicialmente desenvolvidos em R, linguagem com a qual tenho maior domínio, por já utilizá-la com frequência tanto no trabalho quanto durante minha graduação e pós-graduação.

Posteriormente, com o apoio de ferramentas de IA, transcrevi os códigos para Python para garantir a compatibilidade com o ambiente e o case proposto.
Tenho plena consciência da importância de dominar Python para projetos de modelagem, e estou comprometida em continuar meu aprendizado ativo na linguagem.

