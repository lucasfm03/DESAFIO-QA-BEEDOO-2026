# Casos de Teste

Este documento apresenta os cenários de teste executados no sistema de gerenciamento de cursos.

| ID | Cenário de Teste | Tipo | Resultado |
|----|------------------|------|-----------|
CT01 | Verificar se é possível cadastrar um novo curso no sistema | Funcional | Passou |
CT02 | Verificar se o sistema lista corretamente os cursos cadastrados | Funcional | Passou |
CT03 | Verificar se os dados cadastrados são exibidos corretamente na listagem | Funcional | Passou |
CT04 | Verificar se o sistema permite acessar a tela de cadastro de cursos | Funcional | Passou |
CT05 | Verificar se o sistema permite visualizar os cursos cadastrados na tela inicial | Funcional | Passou |
CT06 | Verificar se o sistema impede cadastro de curso com campos obrigatórios vazios | Validação | Falhou |
CT07 | Verificar se o sistema valida corretamente a data de início e fim do curso | Validação | Falhou |
CT08 | Verificar se o sistema valida links inseridos no cadastro do curso | Validação | Falhou |
CT09 | Verificar se o sistema impede cadastro de cursos duplicados | Validação | Falhou |
CT10 | Verificar se o sistema limita a quantidade de caracteres nos campos do cadastro | Validação | Falhou |
CT11 | Verificar se os cursos cadastrados são exibidos corretamente na interface | UI | Passou |
CT12 | Verificar se o sistema apresenta feedback ao usuário após cadastrar um curso | UX | Passou |
CT13 | Verificar se os cards de cursos permanecem alinhados quando cursos com nomes de diferentes tamanhos são cadastrados | UI | Falhou |
CT14 | Verificar se um curso é realmente removido da listagem após clicar na opção de exclusão | Funcional | Falhou |
CT15 | Verificar se o sistema solicita confirmação antes de excluir um curso | UX | Falhou |
CT16 | Verificar a navegação entre a tela inicial e a tela de cadastro de cursos | UX | Passou |
CT17 | Verificar se o usuário consegue cancelar o cadastro e retornar à tela inicial | UX | Falhou |
CT18 | Verificar comportamento do sistema ao clicar múltiplas vezes no botão de cadastrar curso | Robustez | Falhou |
CT19 | Verificar validação do campo nome ao inserir caracteres especiais | Validação | Falhou |
CT20 | Verificar comportamento da interface quando não existem cursos cadastrados no sistema | UX | Falhou |

