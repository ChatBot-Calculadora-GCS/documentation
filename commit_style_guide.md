# Guia de estilo para mensagens de commit do Github

## Formato
As mensagens de commit devem seguir o seguinte formato:

[tipo] (escopo) - assunto

[corpo]

[rodapé]

Onde:
- tipo: Uma palavra que descreve a natureza da mudança (ex: "feat", "fix", "docs", etc.).
- escopo: Uma palavra que descreve a parte do projeto que está sendo modificada (ex: "Nosso projeto", "Classificador", “Notícias”).
- assunto: Uma breve descrição do que foi feito (ex: "Adicionar validação de e-mail no formulário de cadastro").
- [corpo]: Uma explicação mais detalhada das mudanças feitas, justificativas, etc.
- [rodapé]: Informações adicionais, como número de issues relacionadas, referências a outras mudanças, etc.

## Tipos
Os tipos de mensagens de commit devem ser apenas um dentre as opções a seguir:
- feat: Uma nova funcionalidade adicionada
- fix: Alterações que afetam o sistema de compilação ou dependências externas, uma correção de bug
- refactor: Uma alteração de código que não corrige um bug nem adiciona um recurso, mas torna o código mais limpo, eficiente ou bem documentado
- docs: Documentação
- revert: Reverter um commit anterior
- test: Adiciona testes ausentes ou corrige testes existentes
- style: Alterações que não afetam o comportamento do código (espaço em branco, formatação, falta ponto e vírgula, etc.)
- perf: Uma alteração de código que melhora o desempenho da aplicação
- build: Alterações que afetam o sistema de compilação ou dependências externas
- chore: Alterações na configuração, build, ou outras alterações que não modificam os arquivos src ou de teste
- ci: Alterações em nossos arquivos e scripts de configuração de CI (exemplos de escopos: Travis, Circle, BrowserStack, SauceLabs)

## Escopo
Os escopos podem ser usados para indicar qual parte do projeto está sendo modificada. Alguns exemplos de escopos desta aplicação incluem:
- GCS
- ED
- IA
- PROG1
- PROGMOV
- PROGWEB

O assunto deve ser uma descrição clara e sucinta do que foi feito. Ele deve ser escrito em letras maiúsculas.

## Assunto
O assunto deve ser uma descrição clara e sucinta do que foi feito. Ele deve ser escrito em letras minúsculas, com exceção da primeira letra, e sem ponto final.

## Corpo
O corpo é opcional e pode ser usado para fornecer mais informações sobre as mudanças feitas. Ele deve ser escrito em letras minúsculas e separado do assunto por uma linha em branco.

## Rodapé
O rodapé é opcional e pode ser usado para fornecer informações adicionais, como números de issues relacionadas, referências a outras mudanças, etc. Ele deve ser escrito em letras minúsculas, com exceção da primeira letra, e separado do corpo por uma linha em branco.

## Exemplo
feat(GCS): Adiciona descrição do trabalho

Adiciona descrição do trabalho final da disciplina de gerência de configuração de software do 5° semestre (2023.1) do professor Awdren de Lima Fontão

Fixes #123
