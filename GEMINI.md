# Histórico do Projeto: Gerador de Escala 6x1 (Açougue)

Este projeto foi desenvolvido para automatizar a gestão de folgas de uma equipe de açougue, seguindo regras específicas de regime 6x1 e rodízio de domingos.

## 🚀 Funcionalidades Implementadas

- **Dashboard em Tempo Real:** Visualização do total da equipe, quem está de folga no dia atual e a data de hoje.
- **Algoritmo de Escala Automatizado:**
    - **Folga Fixa:** Marcação automática do dia fixo escolhido para cada colaborador.
    - **Rodízio 2x1 de Domingos:** Cálculo matemático baseado em uma data de referência para garantir que, após dois domingos trabalhados, o terceiro seja folga.
- **Gestão de Conflitos:** Identificação visual de semanas onde o colaborador tem duas folgas (fixa + domingo).
- **Banco de Dados Local:** Persistência de dados através do `localStorage` do navegador.
- **Interface de Gerenciamento:** Cadastro, edição (para trocas de folgas) e exclusão com confirmação nominal.
- **Impressão Otimizada (PDF):**
    - Tabela de resumo de folgas por nome.
    - Tabela dedicada de domingos para conferência rápida.
- **Destaque Visual:** Coluna "HOJE" destacada automaticamente no calendário.

## 🛠️ Tecnologias Utilizadas
- HTML5 / CSS3 (Tailwind CSS via CDN)
- JavaScript Puro (Vanilla JS)
- Lucide Icons para interface visual

## 💡 Sugestão de Melhoria Futura
**Sistema de Backup e Sincronização:** Implementar uma função de "Exportar Dados" (gerar um arquivo .json) e "Importar Dados". Isso permitiria que o usuário fizesse cópias de segurança da sua equipe ou transferisse os dados para outro computador/navegador sem depender exclusivamente do cache local do navegador atual.

---
**Desenvolvido com auxílio do Gemini CLI**
**Créditos: LUAN**
