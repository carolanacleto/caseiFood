### 📌 Instruções
Todo o processo de carregamento, tratamento das bases, análise exploratória e modelagem estatística foi realizado na plataforma Databricks Community Edition.

Notebooks desenvolvidos (disponíveis neste repositório):
- notebook_preparacao_dados.ipynb – Etapas de limpeza, transformação e preparação das variáveis
- notebook_modelagem_estatistica.ipynb – Análise exploratória, segmentações e modelo estatístico aplicado


### Como reproduzir os notebooks no seu ambiente Databricks: 
Como os notebooks foram desenvolvidos dentro do meu ambiente pessoal no Databricks Community Edition, eles não podem ser executados diretamente por outros usuários. Para reproduzi-los no seu próprio ambiente Databricks, siga os passos abaixo:
1) Faça o download dos arquivos de dados disponíveis neste repositório (pasta dados/).
2) No Databricks, acesse a aba lateral "Data" e clique em "Add Data" > "Upload File".
3) Faça o upload dos arquivos necessários para dentro da plataforma.
4) Após o upload, os arquivos serão armazenados em um caminho como: /dbfs/FileStore/tables/nome_do_arquivo.csv
5) No código, substitua os caminhos locais por este caminho do Databricks. Exemplo: df = pd.read_csv("file:/dbfs/FileStore/tables/nome_do_arquivo.csv")


### Relatório/apresentação final
O relatório com os principais resultados obtidos está disponível neste repositório como: relatorio_final_case.pdf.
Nota pessoal: o relatório está mais descritivo e detalhado do que seria ideal para uma reunião executiva. Optei por explicar cuidadosamente todas as decisões e resultados para garantir que até pessoas sem conhecimento técnico consigam entender o raciocínio por trás de cada etapa do projeto. Para uma reunião executiva, seria ideal resumir o conteúdo e apresentar os principais pontos de forma mais objetiva.

### Observação:
Gostaria de ser totalmente transparente com vocês:
A modelagem estatística foi inicialmente desenvolvida em R, linguagem com a qual tenho maior domínio, por já utilizá-la com frequência tanto no trabalho quanto durante minha pós-graduação.

Posteriormente, com o apoio de ferramentas de IA, transcrevi os códigos para Python para garantir a compatibilidade com o ambiente e o case proposto.
Tenho plena consciência da importância de dominar Python para projetos de modelagem, e estou comprometida em continuar meu aprendizado ativo na linguagem.

