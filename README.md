========================================================================
                PROJETO DE ENGENHARIA DE SOFTWARE
                  SISTEMA LIVRARIA RESOLVE - GRUPO F
========================================================================

INSTITUIÇÃO:
Universidade Federal do Rio de Janeiro - UFRJ

DISCIPLINA:
Engenharia de Software (EEL873)

INTEGRANTES DO GRUPO:
- Enzo de Carvalho Sampaio
- Paulo César Vaz de Barros
- Raphael Henrique da Silva Pereira

------------------------------------------------------------------------
SOBRE O PROJETO
------------------------------------------------------------------------
Este repositório contém a documentação completa de requisitos e análise 
funcional para o desenvolvimento do sistema "Livraria Resolve". O projeto 
visa informatizar os processos de uma livraria especializada em livros 
raros, cobrindo desde o cadastro de clientes e gestão de pedidos até a 
integração com sistemas financeiros e relatórios gerenciais.

------------------------------------------------------------------------
ESTRUTURA DOS ARQUIVOS E COMPONENTES
------------------------------------------------------------------------

O repositório está organizado com os seguintes artefatos de documentação:

1. ARQUIVO: Casos de Uso - EEL873 - Engenharia de Software.pdf
   -------------------------
   Conteúdo: Modelagem comportamental do sistema.
   - Diagrama de Casos de Uso (UML).
   - Identificação completa dos Atores e seus Objetivos.
   - Narrativas Expandidas (Cenários) dos principais casos de uso:
     * Registrar Pedido (Vendedor)
     * Gerar Proposta Comercial (Vendedor/Gerente)
     * Gerar Requisição de Compra (Diretor)
   - Fluxos principais, alternativos, pré-condições e pós-condições.

2. ARQUIVO: Pontos de Função - EEL873 - Engenharia de Software.pdf
   -------------------------------------
   Conteúdo: Mensuração do tamanho funcional do projeto.
   - Metodologia: Contagem Estimativa (Padrão NESMA/IFPUG).
   - Definição de Fronteiras e Escopo.
   - Contagem detalhada de Funções de Dados (ALI/AIE) com complexidade Baixa.
   - Contagem detalhada de Funções Transacionais (EE/SE/CE) com complexidade Média.
   - Resultado final do cálculo em Pontos de Função (PF).

3. ARQUIVO: Planejamento_e_Requisitos.xlsx (Planilha)
   --------------------------------------------------
   Conteúdo: Levantamento inicial e priorização.
   - Aba 1: Partes Interessadas (Stakeholders)
     * Análise de poder, influência, interesse e engajamento.
   - Aba 2: Matriz MoSCoW
     * Priorização dos desejos (Must Have, Should Have, Could Have, Won't Have).
   - Aba 3: Histórias de Usuário (User Stories)
     * Lista de histórias formatadas (Como um... Desejo... Para...).
     * Mapeamento de requisitos funcionais alinhados ao Diagrama de Casos de Uso.

4. PASTA: BPMN
   --------------------------------------------------
   Conteúdo: Modelagem de Processos de Negócio (BPMN) do sistema.
   - Arquivos divididos por macroprocesso:
     * Registro: Fluxo de cadastro e validação de clientes/pedidos.
     * Venda: Fluxo completo de cotação, proposta e fechamento de venda.
     * Relatório: Fluxo de geração e análise de relatórios gerenciais.
========================================================================
