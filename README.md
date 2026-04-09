# Requisitos Funcionais:

# 2.1.1 Gestão de Usuários
- RF01: O sistema deve permitir o cadastro de usuários.
- RF02: O sistema deve permitir login e logout com autenticação segura.
- RF03: O sistema deve permitir diferentes níveis de acesso conforme o perfil do usuário.
- RF04: O administrador deve poder editar e excluir usuários.
# 2.1.2 Cadastro de Idosos
- RF06: O sistema deve permitir o cadastro completo dos residentes (nome, idade, histórico médico, contatos).
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
- RF18: O sistema deve permitir o cadastro de atividades.
- RF19: O sistema deve exibir uma agenda diária/semanal.
- RF20: O sistema deve vincular atividades a residentes específicos.
- RF21: O sistema deve permitir que cuidadores confirmem a realização das atividades.
- RF22: O sistema deve enviar lembretes sobre atividades programadas.
- RF23: O sistema deve permitir edição e exclusão de eventos da agenda.
# 2.1.5 Relatórios
- RF24: O sistema deve gerar relatórios de administração de medicamentos.
- RF25: O sistema deve gerar relatórios de atividades realizadas.
- RF26: O sistema deve permitir exportação de relatórios.
- RF27: O sistema deve permitir visualização de histórico por residente.

# 2.2 Requisitos Não Funcionais (RNF)

# 2.2.1 Usabilidade
- RNF01: A interface deve ser simples o suficiente para que um cuidador ou enfermeiro sem experiência avançada em tecnologia consiga cadastrar um idoso ou registrar uma medicação em menos de 90 segundos.
- RNF02: O sistema deve ter linguagem clara e acessível.
- RNF03: Tempo médio de treinamento para novos funcionários do lar deve ser de 1 hora.
- RNF04: Feedback visual claro (confirmações em verde/vermelho) ao fazer registros.
# 2.2.2 Desempenho
- RNF05: O sistema deve responder às ações do usuário em até 2 segundos.
- RNF06: O sistema deve suportar múltiplos usuários simultâneos sem perda de desempenho.
- RNF07: Uso de CPU não deve exceder 30% em operações normais no cliente.
- RNF08: O sistema deve suportar carregamento de página em até 2 segundos.
- RNF09: Registros devem ser salvos e confirmados em menos de 2 segundos.
# 2.2.3 Segurança
- RNF10: O sistema deve proteger dados sensíveis (criptografia de senha).
- RNF11: O sistema deve garantir controle de acesso por nível de usuário.
- RNF12: O sistema deve seguir boas práticas da LGPD.
- RNF13: Bloqueio automático de conta após 5 tentativas inválidas de login.
# 2.2.4 Confiabilidade
- RNF14: O sistema deve ter disponibilidade mínima de 95%.
- RNF15: Taxa de falha de transações não deve exceder 0,1%.
- RNF16: O sistema deve evitar perda de dados em caso de falha.
- RNF17: Taxa de erro em registros de medicamentos deve ser inferior a 0,01%.
# 2.2.5 Escalabilidade
- RNF18: O sistema deve suportar aumento de 5x na quantidade de usuários simultâneos sem degradação significativa de desempenho.
- RNF19: Capacidade de lidar com picos de uso sem degradação.
- RNF20: Banco de dados deve suportar até 300 registros ativos com tempo de consulta abaixo de 5 segundos.
- RNF21: Arquitetura deve permitir deploy em cloud com auto-scaling.
# 2.2.6 Manutenibilidade
- RNF22: O sistema deve possuir código organizado e documentado.
- RNF23: O sistema deve permitir atualizações sem interromper totalmente o serviço.
- RNF24: O código deve ter cobertura de testes automatizados ≥ 80% nas camadas críticas.
- RNF25: Documentação técnica atualizada no repositório
# 2.2.7 Compatibilidade
- RNF26: O sistema deve ser compatível com os últimos 3 versões dos navegadores Chrome, Firefox, Edge e Safari.
- RNF27: Funcionar perfeitamente em desktops e notebooks.
# 2.2.8 Acessibilidade
- RNF28: O sistema deve seguir diretrizes básicas de acessibilidade.
- RNF29: O sistema deve estar em conformidade com WCAG 2.2 (mínimo:nível AA).
- RNF30: Suporte a aumento de fonte até 200% e zoom de tela sem perda de funcionalidade.
