API de Chamados de Suporte

Estudante: Jefferson da Rocha Teodoro

Objetivo
Criar a estrutura inicial de uma API de chamados de suporte utilizando Python e Flask, com o ambiente virtual e as dependências gerenciados pelo uv.

Instalação das Dependências
Com o uv instalado no ambiente, execute o comando abaixo na raiz do projeto para sincronizar as dependências:

uv sync --locked

Como Executar
Para iniciar o servidor Flask (localmente ou no GitHub Codespaces), execute:

uv run flask --app app run --host=0.0.0.0 --port=5000

Acesso à Rota Inicial e Resposta Esperada
Com a aplicação em execução, acesse http://localhost:5000/ pelo navegador ou realize uma requisição GET pelo terminal:

curl -i http://localhost:5000/

Resposta esperada:
- Código HTTP: 200 OK
- Cabeçalho: Content-Type: application/json
- Corpo (JSON):
{
  "mensagem": "API de chamados em funcionamento"
}