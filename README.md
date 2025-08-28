<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apresentação: Sistema de Escala Diária PCP</title>
</head>
<body>

    <h1>Apresentação: Sistema de Escala Diária PCP</h1>

    <hr>

    <h2>1. Objetivo do Sistema</h2>
    <p>O objetivo deste sistema é centralizar e simplificar a gestão da escala diária de serviços. Ele foi desenvolvido para ser uma ferramenta rápida e eficiente, permitindo que a equipe de PCP (Planejamento e Controle da Produção) organize as tarefas, atribua funcionários e veículos, e gere relatórios de forma automatizada.</p>

    <h2>2. Interface Principal</h2>
    <p>A interface do sistema é intuitiva e organizada em seções:</p>
    <ul>
        <li><strong>Header</strong>: Apresenta a logo da empresa e o título "PCP - Escala Diária", garantindo a identidade visual.</li>
        <li><strong>Contagem de Serviços</strong>: Um contador no topo da tela informa o total de serviços adicionados, ajudando a visualizar a carga de trabalho do dia.</li>
        <li><strong>Formulário de Inserção</strong>: É aqui que a mágica acontece. O formulário é dividido em campos essenciais para registrar cada serviço:
            <ul>
                <li><strong>Cliente</strong>: Campo de texto para o nome do cliente.</li>
                <li><strong>Número da OS</strong>: Campo opcional para o número da Ordem de Serviço.</li>
                <li><strong>Prioridade</strong>: Um menu suspenso para definir a prioridade do serviço (Alta, Média, Baixa).</li>
                <li><strong>Carros</strong>: Checkboxes para selecionar um ou mais veículos disponíveis, agora em letras maiúsculas para maior clareza.</li>
                <li><strong>Funcionários</strong>: Uma lista de checkboxes com os nomes dos funcionários. Um recurso inteligente só mostra os funcionários que estão disponíveis, ou seja, que ainda não foram alocados em outro serviço. Ao passar o mouse sobre o nome, um tooltip exibe a função e as habilitações (🚗 ou 🏍️).</li>
                <li><strong>Tarefa</strong>: Campo de texto para a descrição detalhada da tarefa a ser executada.</li>
            </ul>
        </li>
    </ul>

    <hr>

    <h2>3. Funcionalidades de Gerenciamento de Tarefas</h2>
    <p>As funções de gerenciamento são o coração do sistema:</p>
    <ul>
        <li><strong>Adicionar Serviço</strong>:
            <ul>
                <li>Ao clicar no botão "Adicionar Serviço", o sistema valida se todos os campos obrigatórios (<strong>Cliente</strong>, <strong>Carros</strong>, <strong>Funcionários</strong>, <strong>Tarefa</strong>) foram preenchidos.</li>
                <li>Após a validação, ele adiciona a tarefa à lista de serviços abaixo.</li>
                <li>Em caso de sucesso ou erro, uma mensagem de notificação (<strong>toast</strong>) aparece na tela, informando o resultado da operação.</li>
            </ul>
        </li>
        <li><strong>Editar Serviço</strong>:
            <ul>
                <li>Para corrigir uma tarefa já adicionada, basta clicar no botão "<strong>Editar ✏️</strong>" na caixa do serviço correspondente.</li>
                <li>O formulário é preenchido automaticamente com os dados da tarefa selecionada.</li>
                <li>O botão "Adicionar Serviço" muda para "<strong>Salvar Edição</strong>", indicando que você está no modo de edição. Os funcionários previamente alocados na tarefa voltam a aparecer na lista de checkboxes para que você possa editá-los.</li>
            </ul>
        </li>
        <li><strong>Remover Serviço</strong>:
            <ul>
                <li>O botão "<strong>Remover ❌</strong>" permite excluir uma tarefa da escala, após uma confirmação para evitar exclusões acidentais.</li>
            </ul>
        </li>
        <li><strong>Limpar Escala</strong>:
            <ul>
                <li>O botão "<strong>Limpar Escala</strong>" remove todas as tarefas de uma vez, ideal para o final do dia ou da semana. Ele também requer uma confirmação.</li>
            </ul>
        </li>
    </ul>

    <hr>

    <h2>4. Organização e Visualização</h2>
    <p>O sistema conta com um painel de visualização e uma ferramenta de organização:</p>
    <ul>
        <li><strong>Ordenar por</strong>: Um menu suspenso acima da lista de serviços que permite ordenar as tarefas por:
            <ul>
                <li><strong>Padrão</strong>: Mantém a ordem em que foram adicionadas.</li>
                <li><strong>Prioridade</strong>: Organiza as tarefas da mais prioritária (Alta) para a menos prioritária (Baixa).</li>
                <li><strong>Cliente (A-Z)</strong>: Organiza em ordem alfabética pelo nome do cliente.</li>
            </ul>
        </li>
        <li><strong>Lista de Serviços</strong>: A área de visualização exibe as tarefas adicionadas em caixas individuais, cada uma com todos os detalhes: Cliente, OS, Prioridade, Carros, Funcionários e Tarefa.</li>
    </ul>

    <hr>

    <h2>5. Opções de Exportação</h2>
    <p>Para compartilhar a escala com a equipe, o sistema oferece várias opções:</p>
    <ul>
        <li><strong>Exportar como</strong>: Ao clicar neste botão, um menu suspenso aparece com as seguintes opções:
            <ul>
                <li><strong>TXT</strong>: Gera e baixa um arquivo de texto simples com todos os detalhes da escala.</li>
                <li><strong>PDF</strong>: Cria um documento PDF formatado, pronto para impressão ou envio.</li>
                <li><strong>WhatsApp</strong>: Copia a escala inteira para a área de transferência no formato de texto, ideal para colar diretamente em grupos de WhatsApp.</li>
            </ul>
        </li>
    </ul>

    <hr>

    <h2>Conclusão</h2>
    <p>Este sistema foi projetado para otimizar o fluxo de trabalho do PCP, reduzindo o tempo gasto com organização e comunicação. Com uma interface moderna, funções de edição e múltiplas opções de exportação, a gestão da escala diária se torna mais rápida, eficiente e à prova de erros.</p>

</body>
</html>
