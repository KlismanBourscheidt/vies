# Vies — Protótipo de gestão ocupacional

Site estático de navegação funcional para GitHub Pages. Basta abrir `index.html` no navegador ou publicar o arquivo na raiz de um repositório GitHub Pages.

## Recursos
- Dashboard com vidas ativas, empresas, documentos e riscos.
- Cadastro, edição, pesquisa e exclusão de vidas.
- Inventário de riscos com empresa, setor/GHE, atividade, grupo, agente, nível preliminar e medidas de controle.
- Documentos e planejamento.
- Relatórios com exportação CSV de vidas ativas.

## Dados e segurança
Todos os dados iniciais são **fictícios**. As alterações são armazenadas somente no `localStorage` do navegador. Não utilize dados pessoais reais ou informações sensíveis: este projeto não possui autenticação, servidor, controle de acesso nem medidas adequadas para dados de saúde. As classificações de risco são ilustrativas e não substituem avaliações profissionais.

## Publicação
1. Crie um repositório no GitHub.
2. Envie `index.html` e `README.md` para a raiz da branch `main`.
3. Em **Settings > Pages**, escolha **Deploy from a branch**, `main`, `/ (root)`.

## Organização
O protótipo é intencionalmente autocontido em `index.html`: HTML, CSS no `<style>` e JavaScript no `<script>`. Isso evita erros de caminhos na hospedagem estática.
