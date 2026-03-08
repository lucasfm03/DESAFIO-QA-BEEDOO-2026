# DESAFIO QA – BEEDOO 2026

Este repositório contém a análise, cenários de teste, execução dos testes e relatório de bugs identificados durante a avaliação do módulo de cadastro e listagem de cursos da aplicação disponibilizada no desafio.

Aplicação analisada:
https://creative-sherbet-a51eac.netlify.app/

## Objetivo da aplicação

A aplicação tem como objetivo permitir o cadastro e a visualização de cursos através de uma interface simples.

O sistema apresenta duas funcionalidades principais:

- Cadastro de novos cursos através de um formulário
- Listagem dos cursos cadastrados

O fluxo principal consiste em inserir informações sobre um curso e verificar se ele é exibido corretamente na listagem.

## Exploração da aplicação

Durante a análise inicial da aplicação foram identificadas as seguintes telas e funcionalidades:

- Tela inicial com listagem de cursos
- Tela de cadastro de cursos
- Funcionalidade de exclusão de cursos

## Principais fluxos identificados

1. Cadastro de curso
   - Usuário acessa o formulário
   - Preenche os campos necessários
   - Envia o cadastro

2. Listagem de cursos
   - Sistema apresenta os cursos cadastrados

3. Exclusão de curso
   - Usuário pode remover um curso da listagem

## Pontos críticos para teste

Durante a análise da aplicação foram identificados alguns pontos que exigem maior atenção nos testes:

- Validação de campos obrigatórios
- Integridade dos dados cadastrados
- Funcionamento da exclusão de cursos
- Comportamento da interface ao lidar com dados inesperados
- Validação de datas e limites de entrada

Esses pontos foram priorizados nos cenários de teste pois falhas nessas áreas podem comprometer a consistência dos dados ou a experiência do usuário.

## Estratégia de testes

Os testes foram elaborados considerando diferentes tipos de cenários:

Cenários positivos  
Validação do funcionamento correto do sistema em condições normais de uso.

Cenários negativos  
Testes com dados inválidos ou incompletos para verificar como o sistema reage a erros de entrada.

Testes de validação  
Verificação de limites de campos, formato de dados e consistência das informações.

Comportamentos inesperados  
Testes simulando entradas incomuns que usuários podem realizar.

## Cenários e casos de teste

Os cenários e casos de teste foram documentados em uma planilha no Google Sheets.

Link da planilha:

https://docs.google.com/spreadsheets/d/1WytL6Up5jGTWb721bymHgAWuPBSZqEY6aTQOndevXoQ/edit?usp=sharing

## Evidências da execução dos testes

As evidências da execução dos testes, incluindo capturas de tela, estão disponíveis na pasta /evidencias deste repositório ou no link abaixo:

[LINK DO GOOGLE DRIVE]

## Bugs encontrados

Durante a execução dos testes foram identificados alguns comportamentos inesperados e falhas no sistema.

O relatório completo de bugs pode ser encontrado no arquivo:

/bugs/relatorio-bugs.md

## Considerações finais

A execução dos testes permitiu identificar falhas relacionadas principalmente à validação de dados e ao funcionamento de algumas funcionalidades da aplicação.

Também foram observados pontos de melhoria relacionados à experiência do usuário e à robustez do sistema no tratamento de entradas inesperadas.

A documentação dos testes e dos problemas encontrados contribui para melhorar a qualidade e confiabilidade da aplicação.
