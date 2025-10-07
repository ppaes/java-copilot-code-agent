# Issue Templates - Guia para Professores

Este diretório contém formulários padronizados para ajudar professores a solicitar mudanças no Sistema de Gestão Escolar da Mergington High School.

## 📝 Templates Disponíveis

### 1. Adicionar Nova Atividade
**Quando usar:** Você deseja criar uma nova atividade extracurricular no sistema.

**O que é necessário:**
- Nome da atividade
- Descrição detalhada
- Categoria (esportes, artes, música, acadêmico, tecnologia, ciência, outro)
- Número máximo de participantes
- Dias da semana (segunda a domingo)
- Horário de início e término (formato 24h, ex: 15:30)
- Informações adicionais (opcional)

**Exemplo de uso:**
```
Nome: Robotics Club
Descrição: Clube de robótica para estudantes interessados em programação e engenharia
Categoria: technology (tecnologia)
Max Participantes: 15
Dias: Quarta-feira, Sexta-feira
Horário: 15:30 - 17:30
```

### 2. Modificar Atividade Existente
**Quando usar:** Você precisa alterar detalhes de uma atividade que já existe.

**O que é necessário:**
- Nome exato da atividade a ser modificada
- Quais alterações são necessárias (descrição, horário, dias, capacidade, categoria, nome)
- Novos valores para os campos que serão alterados
- Detalhes e motivo das modificações

**Exemplo de uso:**
```
Atividade: Chess Club
Modificações necessárias:
- Alterar horário
- Alterar capacidade máxima

Novo horário de início: 16:00
Novo horário de término: 18:00
Nova capacidade: 25
Motivo: Aumentar vagas devido à alta demanda
```

### 3. Gerenciar Inscrições de Estudantes
**Quando usar:** Você precisa inscrever ou desinscrever estudantes de atividades.

**O que é necessário:**
- Tipo de ação (inscrever ou desinscrever)
- Nome da atividade
- E-mails dos estudantes (um por linha)
- Seu nome de usuário de professor
- Motivo (opcional)

**Exemplo de uso:**
```
Ação: Inscrever estudante(s) em atividade
Atividade: Drama Club
E-mails:
  maria.silva@mergington.edu
  joao.santos@mergington.edu
Professor: teacher.rodriguez
```

### 4. Relatar um Bug
**Quando usar:** Você encontrou um problema, erro ou comportamento inesperado no sistema.

**O que é necessário:**
- Descrição clara do problema
- Gravidade (crítico, alto, médio, baixo)
- Área afetada (listagem, filtros, inscrições, login, interface, API, etc.)
- Passos para reproduzir o problema
- Comportamento esperado vs. comportamento atual
- Mensagens de erro (se houver)
- Capturas de tela (opcional mas útil)
- Navegador usado (se aplicável)

**Exemplo de uso:**
```
Problema: Não consigo ver a lista de participantes na atividade Chess Club
Gravidade: Médio
Área: Listagem de atividades
Passos:
1. Fazer login como professor
2. Acessar a página principal
3. Clicar em "Chess Club"
4. A lista de participantes não aparece

Esperado: Ver todos os estudantes inscritos
Atual: Lista vazia mesmo com estudantes inscritos
```

### 5. Solicitar Nova Funcionalidade
**Quando usar:** Você tem uma ideia para uma nova funcionalidade ou melhoria no sistema.

**O que é necessário:**
- Descrição clara da funcionalidade
- Problema ou necessidade que ela resolve
- Prioridade (alta, média, baixa)
- Área do sistema afetada
- Como você imagina que deveria funcionar
- Casos de uso (exemplos específicos)
- Alternativas consideradas (opcional)
- Quem se beneficiaria (professores, estudantes, administradores, todos)

**Exemplo de uso:**
```
Funcionalidade: Exportar lista de participantes em Excel
Problema: Preciso compartilhar listas de participantes com outros professores e coordenadores
Prioridade: Média
Área: Gestão de atividades

Como deveria funcionar:
- Botão "Exportar" em cada atividade
- Ao clicar, baixa arquivo Excel com:
  * Nome da atividade
  * Lista de e-mails dos participantes
  * Data de exportação
```

## 🚀 Como Usar os Templates

1. **Acesse a aba "Issues"** no repositório do GitHub
2. **Clique em "New Issue"**
3. **Selecione o template apropriado** para sua necessidade
4. **Preencha todos os campos obrigatórios** (marcados com asterisco)
5. **Seja o mais específico possível** - quanto mais detalhes, melhor
6. **Clique em "Submit new issue"**
7. **O agente Copilot será automaticamente designado** para trabalhar na sua solicitação

## ✨ Dicas para Issues Efetivas

### ✅ Boas Práticas
- **Seja específico:** "Alterar horário do Chess Club para 16:00-18:00" é melhor que "Mudar horário"
- **Forneça exemplos:** Use dados reais quando possível
- **Use os campos corretamente:** Preencha todos os campos obrigatórios
- **Revise antes de enviar:** Verifique se todas as informações estão corretas

### ❌ Evite
- Issues vagas ou genéricas
- Múltiplas solicitações não relacionadas em uma única issue
- Falta de informações necessárias
- Termos técnicos desnecessários

## 📋 Critérios de Aceitação

Cada template inclui critérios de aceitação que definem quando a tarefa está completa. Estes critérios ajudam a garantir que:
- Todos os requisitos foram atendidos
- A implementação foi testada
- Não há efeitos colaterais indesejados
- A documentação foi atualizada quando necessário

## 🤝 Suporte

Se você tiver dúvidas sobre qual template usar ou como preencher um formulário:
- Consulte a [Documentação do Sistema](../../docs/README.md)
- Participe das [Discussões da Comunidade](https://github.com/ppaes/java-copilot-code-agent/discussions)
- Entre em contato com o administrador do sistema

## 📚 Informações Técnicas

### Estrutura do Sistema
O sistema possui as seguintes áreas principais:
- **Gestão de Atividades:** Criar, modificar, listar atividades
- **Gestão de Inscrições:** Inscrever/desinscrever estudantes
- **Autenticação:** Login de professores e administradores
- **Interface Web:** Frontend responsivo

### Dados do Sistema
- **Professores padrão:** admin, teacher.rodriguez, teacher.chen
- **Categorias de atividades:** sports, arts, music, academic, technology, science, other
- **Formato de horário:** 24 horas (HH:MM), ex: 15:30
- **Dias da semana:** Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday

### Validações Automáticas
O sistema valida automaticamente:
- Formato de e-mail dos estudantes
- Capacidade máxima de atividades
- Duplicação de inscrições
- Credenciais de professores
- Formato de horários

---

**Versão:** 1.0  
**Última atualização:** 2024  
**Mantido por:** Equipe de Tecnologia da Mergington High School
