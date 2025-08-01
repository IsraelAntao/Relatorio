# Repositório Projeto

Requisitos Funcionais
Os requisitos funcionais descrevem as funcionalidades que o sistema deve oferecer aos seus usuários.
RF01 - Cadastro e Gestão de Usuários: Permitir o cadastro de diferentes perfis de usuários (estudante, professor, coordenador, psicopedagogo, administrador) com níveis de acesso e permissões distintos.

RF02 - Importação e Sincronização de Dados Acadêmicos: Possibilitar a importação automatizada de dados de desempenho (notas, frequência), histórico de matrículas e informações do Sistema Q-Acadêmico da instituição.

RF03 - Cálculo de Indicadores de Risco: O sistema deve calcular indicadores de risco de evasão para cada estudante com base nos dados disponíveis e no modelo preditivo.

RF04 - Geração de Alertas e Notificações: Enviar alertas automáticos (via e-mail, SMS ou notificação no sistema) para os estudantes, professores, psicopedagogo, psicólogo e coordenador do curso.

RF05 - Painel de Controle por Perfil: Apresentar painéis de controle personalizados para cada tipo de usuário, exibindo informações relevantes ao seu perfil (ex: lista de alunos em risco para coordenadores e docentes, desempenho individual para alunos).

RF06 - Registro de Intervenções: Permitir que professores, coordenadores e equipe de apoio registrem as ações de intervenção realizadas com os estudantes (ex: reuniões, aconselhamentos, encaminhamentos).

RF07 - Relatórios e Dashboards: Gerar relatórios periódicos e dashboards interativos sobre a taxa de evasão, fatores de risco predominantes, eficácia das intervenções e desempenho geral do curso.

RF08 - Ferramenta de Comunicação Interna: Oferecer um canal de comunicação seguro e rastreável entre estudantes e a equipe de apoio, e entre a equipe de apoio e professores/coordenadores.

RF09 - Consulta de Histórico do Aluno: Permitir a consulta do histórico acadêmico, financeiro (se relevante e com privacidade), e de intervenções para cada estudante.

RF10 - Análise de Tendências: Capacidade de analisar tendências de evasão ao longo do tempo e por diferentes turmas ou disciplinas.



Casos de Uso
Os casos de uso descrevem a interação entre um ator (usuário) e o sistema para alcançar um objetivo específico.
CU01: Gerenciar Perfil de Usuário
Ator: Todos os usuários (Estudante, Professor, Coordenador, Psicopedagogo, Psicólogo, Administrador)
Descrição: O usuário pode visualizar e atualizar suas informações de perfil (nome, e-mail, senha).
CU02: Visualizar Alunos em Risco
Ator: Coordenador, Psicopedagogo, Psicólogo, Professor (para seus alunos)
Descrição: O ator visualiza uma lista de alunos que foram identificados como estando em risco de evasão.
CU03: Registrar Intervenção
Ator: Coordenador, Psicopedagogo, Psicólogo, Professor
Descrição: O ator registra uma ação de apoio ou intervenção realizada com um aluno em risco.
CU04: Consultar Histórico do Aluno
Ator: Coordenador, Psicopedagogo, Psicólogo, Professor
Descrição: O ator consulta o histórico acadêmico, de frequência e de intervenções de um aluno específico.
CU05: Gerar Relatório de Evasão
Ator: Coordenador, Administrador
Descrição: O ator gera relatórios detalhados sobre as taxas de evasão, causas e eficácia das intervenções.
CU06: Importar Dados Acadêmicos
Ator: Administrador
Descrição: O administrador importa dados acadêmicos de sistemas externos para o sistema de monitoramento.
CU07: Receber Alerta de Risco
Ator: Coordenador, Psicopedagogo, Psicólogo, Professor
Descrição: O ator recebe uma notificação ou e-mail quando um aluno sob sua responsabilidade é identificado como em risco de evasão.
CU08: Enviar Mensagem para Aluno
Ator: Coordenador, Psicopedagogo, Psicólogo, Professor
Descrição: O ator envia uma mensagem interna ou e-mail para um aluno através do sistema.
CU09: Visualizar Desempenho Pessoal
Ator: Estudante
Descrição: O estudante visualiza seu próprio desempenho acadêmico, frequência e possíveis alertas de risco (com aconselhamento).
