# Padrão de configuração do projeto

## Itens de configuração

| ID | Item | Pasta | Responsável |
|---|---|---|---|
| IC01 | Aplicação da aula | `/` (`navegar-com-seguranca.html`) | Aléxis Neto Guimarães |
| IC02 | Roteiro dos módulos | `material/modulos/` | Aléxis Neto Guimarães |
| IC03 | Banco de perguntas do quiz | `material/quiz/` | Aléxis Neto Guimarães |
| IC04 | Simulações e recomendações | `material/simulacoes/` | Aléxis Neto Guimarães |
| IC05 | Diagramas | `diagramas/` | Aléxis Neto Guimarães |
| IC06 | Requisitos e plano de configuração | `docs/` | Aléxis Neto Guimarães |
| IC07 | Relatórios de desempenho | `relatorios/` | Aléxis Neto Guimarães |

## Mensagens de commit

Formato: `tipo(item): descrição curta no imperativo`

| Tipo | Uso |
|---|---|
| `feat` | nova funcionalidade ou conteúdo |
| `fix` | correção de erro no conteúdo ou no código |
| `docs` | documentação, requisitos, diagramas |
| `refactor` | reorganização sem mudar o comportamento |

Exemplos: `docs(requisitos): renumerar RF e RNF da baseline`, `fix(quiz): corrigir alternativa da pergunta 3`.

Commits criados pelo navegador do GitHub também seguem esse formato.

## Versões e tags

- `MAIOR`: mudança de escopo da aula (novo módulo, nova etapa da AE)
- `MENOR`: nova funcionalidade ou conteúdo dentro do escopo
- `CORREÇÃO`: ajustes de texto, erros e acessibilidade

Uma tag é criada somente quando a baseline passa pela auditoria de configuração.

## Solicitação de mudança

1. Abrir uma *issue* descrevendo a mudança e o item afetado.
2. Avaliar o impacto nos requisitos (`docs/requisitos.md`).
3. Aplicar a mudança em commit seguindo o padrão acima.
4. Registrar no `CHANGELOG.md` e, se for baseline, criar a tag.
