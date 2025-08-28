# 📌 Sistema de Escala Diária PCP

## 📚 Sumário
- [🎯 1. Objetivo do Sistema](#-1-objetivo-do-sistema)
- [🖥️ 2. Interface Principal](#️-2-interface-principal)
- [⚙️ 3. Funcionalidades de Gerenciamento de Tarefas](#️-3-funcionalidades-de-gerenciamento-de-tarefas)
- [📊 4. Organização e Visualização](#-4-organização-e-visualização)
- [📤 5. Opções de Exportação](#-5-opções-de-exportação)
- [✅ Conclusão](#-conclusão)

---

## 🎯 1. Objetivo do Sistema
O **Sistema de Escala Diária PCP** foi desenvolvido para **centralizar e simplificar a gestão da escala diária de serviços**.  
Ele é uma ferramenta rápida e eficiente, permitindo que a equipe de **PCP (Planejamento e Controle da Produção)**:

- Organize tarefas
- Atribua funcionários e veículos
- Gere relatórios de forma automatizada

---

## 🖥️ 2. Interface Principal
A interface é **intuitiva e organizada em seções**:

### 🔹 Header
- Exibe a logo da empresa e o título **"PCP - Escala Diária"**  
- Mantém a identidade visual

### 🔹 Contagem de Serviços
- Um **contador no topo da tela** mostra o total de serviços adicionados  
- Facilita a visualização da carga de trabalho do dia

### 🔹 Formulário de Inserção
Dividido em campos essenciais para cada serviço:

- **Cliente**: Nome do cliente  
- **Número da OS** *(opcional)*: Ordem de Serviço  
- **Prioridade**: Seleção entre `Alta`, `Média` e `Baixa`  
- **Carros**: Checkboxes em letras **maiúsculas** para maior clareza  
- **Funcionários**: Lista de checkboxes exibindo apenas os disponíveis  
  - Tooltip mostra **função e habilitações** (🚗 carro / 🏍️ moto)  
- **Tarefa**: Descrição detalhada do serviço  

---

## ⚙️ 3. Funcionalidades de Gerenciamento de Tarefas

### ➕ Adicionar Serviço
- Valida campos obrigatórios: **Cliente, Carros, Funcionários e Tarefa**  
- Adiciona à lista de serviços após validação  
- Exibe **notificação (toast)** com sucesso ou erro  

### ✏️ Editar Serviço
- Clique em **"Editar ✏️"** na tarefa desejada  
- Formulário é preenchido automaticamente  
- Botão muda para **"Salvar Edição"**  
- Funcionários previamente alocados voltam à lista para ajustes  

### ❌ Remover Serviço
- Exclui uma tarefa da escala com **confirmação** para evitar erros  

### 🧹 Limpar Escala
- Remove todas as tarefas de uma vez  
- Ideal para **final do dia ou da semana**  
- Requer **confirmação**  

---

## 📊 4. Organização e Visualização

### 🔽 Ordenar por
- **Padrão** → ordem de inserção  
- **Prioridade** → da mais alta para a mais baixa  
- **Cliente (A-Z)** → ordem alfabética  

### 📋 Lista de Serviços
Cada tarefa é exibida em uma **caixa individual** contendo:  
Cliente, OS, Prioridade, Carros, Funcionários e Tarefa  

---

## 📤 5. Opções de Exportação
O sistema permite compartilhar a escala com a equipe através de:

- **TXT** → Arquivo de texto simples  
- **PDF** → Documento formatado, pronto para impressão ou envio  
- **WhatsApp** → Copia a escala para a área de transferência, ideal para grupos  

---

## ✅ Conclusão
O **Sistema de Escala Diária PCP** otimiza o fluxo de trabalho do setor, reduzindo tempo com organização e comunicação.  

Com:
- Interface moderna  
- Funções de edição  
- Opções de exportação  

➡️ A gestão da escala diária se torna **rápida, eficiente e à prova de erros**.  

