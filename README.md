# GitHub Actions — Automação de Workflows

## Sobre o projeto

Projeto desenvolvido como atividade prática para estudar o funcionamento do GitHub Actions e suas possibilidades de integração e automação de processos.

O objetivo é compreender como criar workflows utilizando arquivos YAML, configurar eventos de execução e automatizar tarefas relacionadas ao desenvolvimento de software.

## Tecnologias utilizadas

- Git
- GitHub
- GitHub Actions
- YAML
- Python

## O que é GitHub Actions?

GitHub Actions é uma plataforma de automação integrada ao GitHub que permite criar workflows para executar tarefas automaticamente a partir de eventos definidos no repositório.

As configurações são realizadas por meio de arquivos YAML armazenados em:

`.github/workflows/`

## Possibilidades de utilização

### 1. Automação de tarefas
- Execução automática de scripts.
- Atualização de arquivos.
- Geração de relatórios.
- Automatização de processos repetitivos.

### 2. Testes automatizados
- Execução de testes unitários.
- Identificação de erros.
- Validação de alterações no código.
- Verificação da integridade do projeto.

### 3. Integração contínua (CI)
- Validação automática a cada push.
- Execução de testes em Pull Requests.
- Verificação de qualidade do código.
- Identificação antecipada de problemas.

### 4. Entrega contínua (CD)
- Publicação automatizada de versões.
- Deploy em servidores.
- Atualização de aplicações.
- Automatização de processos de entrega.

### 5. Agendamento de tarefas
- Execução diária ou semanal.
- Rotinas programadas com cron.
- Monitoramento periódico.
- Geração automática de informações.

### 6. Notificações e integrações
- Envio de notificações.
- Integração com APIs externas.
- Comunicação com ferramentas como Slack e Discord.
- Alertas sobre falhas nos workflows.

### 7. Segurança e qualidade
- Análise de vulnerabilidades.
- Verificação de dependências.
- Análise estática de código.
- Identificação de possíveis problemas de segurança.

## Principais eventos de execução

| Evento | Descrição |
|---|---|
| push | Executa quando alterações são enviadas ao repositório |
| pull_request | Executa quando uma Pull Request é criada ou atualizada |
| schedule | Executa em horários programados |
| workflow_dispatch | Permite execução manual |
| issues | Responde a eventos relacionados a issues |
| release | Executa quando uma versão é publicada |

## Estrutura dos workflows

```text
.github/
└── workflows/
    └── arquivo.yml
```

Um workflow pode conter:

- `name`: nome do workflow.
- `on`: eventos que iniciam sua execução.
- `jobs`: tarefas executadas.
- `runs-on`: ambiente de execução.
- `steps`: etapas do processo.
- `uses`: utilização de ações existentes.
- `run`: execução de comandos.

## Objetivo de aprendizagem

Explorar os recursos de automação do GitHub Actions, compreender a estrutura dos workflows e identificar como essa ferramenta pode ser aplicada em projetos de desenvolvimento, integração contínua, testes automatizados e entrega de software.

## Autor

**Jhonatan**

[GitHub — Jhon0498](https://github.com/Jhon0498)
