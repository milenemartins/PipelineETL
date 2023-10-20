# Pipeline ETL
Explorando IA Generativa em um Pipeline de ETL com Python 🐍 e Pandas 🐼

## Listagem de filmes com base no ano de lançamento.

O objetivo do projeto: Mostrar como extrair, transformar e analisar dados com Python no Colab.

As informações citadas na listagem de filmes, são veridicas e tiradas por mim mesma da plataforma Google.

### 1 - Estract (extração)
Importação da bibilioteca pandas, e importação da planilha("dados_filmes.csv") para realizarmos a exploração.

### 2 - Transform (transformação)
Criando uma coluna para receber os valores baseada na lógica feita para o retorno da listagem, mostrando se é um filme atual (>=2023) ou um filme antigo (<2023)
Ordenando a lista para que ela retorne do mais novo para o mais velho, de acordo com o ano de Estreia conforme os dados da coluna.

### 3 - Load (carregamento)
Imprimir a mensagem com a lista de filmes, genêros e estreia e com o status de 'lançamento' ou 'antigo'


