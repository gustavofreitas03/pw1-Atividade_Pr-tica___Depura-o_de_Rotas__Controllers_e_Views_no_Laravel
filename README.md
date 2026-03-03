Atividade - Rotas, Views e Controllers no Laravel
Disciplina: Programação Web I
Curso: Análise e Desenvolvimento de Sistemas (ADS)
Instituição: IFCE – Campus Boa Viagem
Aluno: Gustavo de Freitas Angelim
Objetivo da Atividade
Aplicar na prática os conceitos fundamentais do Laravel utilizando:
- Rotas
- Controllers
- Views (Blade)
- Parâmetros via URL
- Estrutura MVC
Estrutura do Projeto
O sistema foi desenvolvido seguindo o padrão MVC (Model-View-Controller).
Fluxo de funcionamento:
Browser → Route → Controller → View → Resposta
Model → Estrutura de dados
View → Interface exibida ao usuário
Controller → Lógica da aplicação
Funcionalidades Implementadas
Rotas Simples:
/ola
/curso/ads
/curso/web
Rotas Retornando Views:
/sobre
/contato
/institucional/missao
Rotas com Controller (Retornando Texto):
/empresa
Rotas com Controller (Retornando View):
/servicos
/portfolio
/blog
/equipe
Parâmetro Obrigatório na URL:
/usuario/{nome}
Exemplo: /usuario/Gustavo
Parâmetro com Controller:
/produto/{id}
Exemplo: /produto/10
O valor informado na URL é recebido automaticamente como parâmetro no método do controller.
Estrutura Principal do Projeto:
app/
resources/views/
routes/web.php
As pastas vendor, node_modules e o arquivo .env não são enviados para o GitHub, conforme boas
práticas do Laravel.
Como Executar o Projeto:
1. Clonar o repositório
2. Instalar dependências: composer install
3. Criar o arquivo .env (copiar do .env.example)
4. Gerar chave da aplicação: php artisan key:generate
5. Executar o servidor: php artisan serve
6. Acessar no navegador: http://127.0.0.1:8000
Conclusão
A atividade demonstrou o funcionamento das rotas no Laravel e sua integração com Controllers e
Views, aplicando corretamente o padrão MVC e a passagem de parâmetros via URL.
O sistema encontra-se funcional e organizado conforme os princípios da disciplina de
Programação Web 
