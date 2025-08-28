# Apresentação: Sistema de Escala Diária PCP

1. Objetivo do Sistema
O objetivo deste sistema é centralizar e simplificar a gestão da escala diária de serviços. Ele foi desenvolvido para ser uma ferramenta rápida e eficiente, permitindo que a equipe de PCP (Planejamento e Controle da Produção) organize as tarefas, atribua funcionários e veículos, e gere relatórios de forma automatizada.

2. Interface Principal
A interface do sistema é intuitiva e organizada em seções:
<br>

Header: Apresenta a logo da empresa e o título "PCP - Escala Diária", garantindo a identidade visual.

<br>

Contagem de Serviços: Um contador no topo da tela informa o total de serviços adicionados, ajudando a visualizar a carga de trabalho do dia.
<br>

Formulário de Inserção: É aqui que a mágica acontece. O formulário é dividido em campos essenciais para registrar cada serviço:

Cliente: Campo de texto para o nome do cliente.

Número da OS: Campo opcional para o número da Ordem de Serviço.

Prioridade: Um menu suspenso para definir a prioridade do serviço (Alta, Média, Baixa).

Carros: Checkboxes para selecionar um ou mais veículos disponíveis, agora em letras maiúsculas para maior clareza.

Funcionários: Uma lista de checkboxes com os nomes dos funcionários. Um recurso inteligente só mostra os funcionários que estão disponíveis, ou seja, que ainda não foram alocados em outro serviço. Ao passar o mouse sobre o nome, um tooltip exibe a função e as habilitações (🚗 ou 🏍️).

Tarefa: Campo de texto para a descrição detalhada da tarefa a ser executada.

3. Funcionalidades de Gerenciamento de Tarefas
As funções de gerenciamento são o coração do sistema:
<br>

Adicionar Serviço:

Ao clicar no botão "Adicionar Serviço", o sistema valida se todos os campos obrigatórios (Cliente, Carros, Funcionários, Tarefa) foram preenchidos.

Após a validação, ele adiciona a tarefa à lista de serviços abaixo.

Em caso de sucesso ou erro, uma mensagem de notificação (toast) aparece na tela, informando o resultado da operação.

<br>

Editar Serviço:

Para corrigir uma tarefa já adicionada, basta clicar no botão "Editar ✏️" na caixa do serviço correspondente.

O formulário é preenchido automaticamente com os dados da tarefa selecionada.

O botão "Adicionar Serviço" muda para "Salvar Edição", indicando que você está no modo de edição. Os funcionários previamente alocados na tarefa voltam a aparecer na lista de checkboxes para que você possa editá-los.
<br>

Remover Serviço:

O botão "Remover ❌" permite excluir uma tarefa da escala, após uma confirmação para evitar exclusões acidentais.
<br>

Limpar Escala:

O botão "Limpar Escala" remove todas as tarefas de uma vez, ideal para o final do dia ou da semana. Ele também requer uma confirmação.

4. Organização e Visualização
O sistema conta com um painel de visualização e uma ferramenta de organização:
<br>

Ordenar por: Um menu suspenso acima da lista de serviços que permite ordenar as tarefas por:

Padrão: Mantém a ordem em que foram adicionadas.

Prioridade: Organiza as tarefas da mais prioritária (Alta) para a menos prioritária (Baixa).

Cliente (A-Z): Organiza em ordem alfabética pelo nome do cliente.

<br>

Lista de Serviços: A área de visualização exibe as tarefas adicionadas em caixas individuais, cada uma com todos os detalhes: Cliente, OS, Prioridade, Carros, Funcionários e Tarefa.

5. Opções de Exportação
Para compartilhar a escala com a equipe, o sistema oferece várias opções:
<br>

Exportar como: Ao clicar neste botão, um menu suspenso aparece com as seguintes opções:

TXT: Gera e baixa um arquivo de texto simples com todos os detalhes da escala.

PDF: Cria um documento PDF formatado, pronto para impressão ou envio.

WhatsApp: Copia a escala inteira para a área de transferência no formato de texto, ideal para colar diretamente em grupos de WhatsApp.

Conclusão
Este sistema foi projetado para otimizar o fluxo de trabalho do PCP, reduzindo o tempo gasto com organização e comunicação. Com uma interface moderna, funções de edição e múltiplas opções de exportação, a gestão da escala diária se torna mais rápida, eficiente e à prova de erros.
