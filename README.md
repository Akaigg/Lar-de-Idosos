# Requisitos Funcionais:

# 2.1.1 Gestão de Usuários
- RF01: O sistema deve permitir o cadastro de usuários (administradores, cuidadores e familiares).
- RF02: O sistema deve permitir login e logout com autenticação segura.
- RF03: O sistema deve permitir diferentes níveis de acesso conforme o perfil do usuário.
- RF04: O administrador deve poder editar e excluir usuários.
# 2.1.2 Cadastro de Idosos
- RF06: O sistema deve permitir o cadastro completo dos residentes (nome, idade, histórico médico, contatos, etc.).
- RF07: O sistema deve permitir a edição dos dados dos residentes.
- RF08: O sistema deve permitir a exclusão de residentes.
- RF09: O sistema deve armazenar informações de responsáveis/familiares vinculados ao residente.
- RF10: O sistema deve permitir visualizar o perfil completo do residente.
# 2.1.3 Controle de Medicamentos
- RF11: O sistema deve permitir o cadastro de medicamentos para cada residente.
- RF12: O sistema deve registrar informações como nome do medicamento, dosagem, horário e orientações médicas.
- RF14: O cuidador deve poder confirmar a administração do medicamento.
- RF15: O sistema deve armazenar histórico de administração de medicamentos.
- RF16: O sistema deve permitir editar ou excluir medicamentos cadastrados.
- RF17: O sistema deve alertar em caso de atraso na administração do medicamento.
# 2.1.4 Agenda e Rotinas
- RF18: O sistema deve permitir o cadastro de atividades (consultas, fisioterapia, recreação, etc.).
- RF19: O sistema deve exibir uma agenda diária/semanal.
- RF20: O sistema deve vincular atividades a residentes específicos.
- RF21: O sistema deve permitir que cuidadores confirmem a realização das atividades.
- RF22: O sistema deve enviar lembretes sobre atividades programadas.
- RF23: O sistema deve permitir edição e exclusão de eventos da agenda.
# 2.1.5 Relatórios
- RF24: O sistema deve gerar relatórios de administração de medicamentos.
- RF25: O sistema deve gerar relatórios de atividades realizadas.
- RF26: O sistema deve permitir exportação de relatórios (PDF ou CSV).
- RF27: O sistema deve permitir visualização de histórico por residente.

# 2.2 Requisitos Não Funcionais (RNF)

# 2.2.1 Usabilidade
- RNF01: O sistema deve ter interface simples e intuitiva.
- RNF02: O sistema deve ter linguagem clara e acessível.
- RNF03: O sistema deve ser utilizável por pessoas com baixo conhecimento técnico.
# 2.2.2 Desempenho
- RNF04: O sistema deve responder às ações do usuário em até 3 segundos.
- RNF05: O sistema deve suportar múltiplos usuários simultâneos sem perda de desempenho.
# 2.2.3 Segurança
- RNF06: O sistema deve proteger dados sensíveis (criptografia de senha).
- RNF07: O sistema deve garantir controle de acesso por nível de usuário.
- RNF08: O sistema deve seguir boas práticas da LGPD.
# 2.2.4 Confiabilidade
- RNF09: O sistema deve ter disponibilidade mínima de 95%.
- RNF10: O sistema deve evitar perda de dados em caso de falha.
# 2.2.5 Escalabilidade
- RNF11: O sistema deve permitir aumento de usuários sem necessidade de grandes mudanças.
- RNF12: O sistema deve suportar expansão para múltiplas unidades de lar de idosos.
# 2.2.6 Manutenibilidade
- RNF13: O sistema deve possuir código organizado e documentado.
- RNF14: O sistema deve permitir atualizações sem interromper totalmente o serviço.
# 2.2.7 Compatibilidade
- RNF15: O sistema deve ser compatível com navegadores modernos.
# 2.2.8 Acessibilidade
- RNF16: O sistema deve seguir diretrizes básicas de acessibilidade.
