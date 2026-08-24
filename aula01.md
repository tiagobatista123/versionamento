# Introdução
 O markdown é uma linguagem de marcação simples para formatar textos de maneira rápida e legível no github e amplamente usado para;

    -Arquivos "README.md"
    -Documentação de projetos
    -Anotações técnicas
    -Relatórios de atividades
    -Instruções de instalações
    -Registro de aulas
    -ISSUES e Pull Requests

A extenção padrão do arquivo markdown é ".md"

exemplo;
    README.md


1. O que é markdown?
   Markdown permite aplicar formatação simples em um texto usando caracteres simples;

Exemplo:
    #Meu Projeto
Este projeto foi desenvolvido durante a aula de **Versionamento de código**

## Tecnologias

    -Git
    -Github
    -Vscode

No Github, esse conteúdo será apresentado de forma formatada com título, texto em negrito e lista.

2. Criando um arquivo markdown.
no visual code studio:

    1. Abra a pasta do projeto
    2. Clique em "new file"
    3. Informe o nome do arquivo
    ex.: README.md

    Para registros de aulas, também podem ser utilizados nomes como;

    Semana-01.md
    Semana-02.md
    aula01.md

## Boas Práticas 

     Prefira nomes
        • curtos
        • descritivos
        • escrito em letras minúsculas
        • sem acentos
        • sem espaços
        • separados por hífem quando necessário

## Recomendado
  
        • resumo-git.md
        • aula-01.md
        • comandos-git.md

## Evite
  
       • Resumo git.md
       • Aula01.md
       • Atividade Prática Github.md
       • Meu Arquivo Novo.md

# 3. Título e subtítulos
Markdown utiliza a caractere `#` para criar títulos

```markdownn
# Título principal
## título nivel 1
### título nivel 2
#### título nivel 3
##### título nivel 4
###### título nivel 5
```
# Título principal
## título nivel 1
### título nivel 2
#### título nivel 3
##### título nivel 4
###### título nivel 5

Boa Prática
    Utilize uma estrutura hierárquica

    Exemplo:
``` markdown
# Semana 8 - Introdução ao Git
## Objetivos da aula
## Conceitos aprendidos
### Repositório
### Commit
### Branch
### Atividiade de prática
## Conclusão
```
# Semana 8 - Introdução ao Git
## Objetivos da aula
## Conceitos aprendidos
### Repositório
### Commit
### Branch
### Atividiade de prática
## Conclusão
    Evite pular niveis sem necessidade como;

# Título
### Subtítulo

4. Parágrafo
    Para criar um parágrafo, deixe uma
    linha em branco entre os textos.
      Git é um sistema de controle distribuído

    Ele permite registrar e acompanhar alterações realizadas nos arquivos de um projeto

5. Negrito
   Utilize 2 asteriscos
   **textos em negrito**
O **git** é um sistema de controle de versão

6. Itálico
   Utilize 1 asterisco
   *texto em itálico*

O comando *git status* permite verificar o estado do repositório.

Entretanto para representar comandos, o ideal é utilizar a formatação de código a seguir.

7. Negrito e Itálico
    ***Texto em negrito e itálico***

    ***git add***

8. Listas são ordenadas
   Utilize antes de cada item.
    - git
    - github
    - visual code studio
  
  Também é possível criar níveis
  - git
    - commit
    - branch
    - merge
  - github
    - repositório
    - pull request
    - issues
  
Boa Prática
  ### utilize listas para representar
    - conceitos
    - requisitos
    - tecnologias
    - etapas
    - recursos
    
9. Listas Numeradas
    1. Criar repositório
    2. Adicionar os arquivos
    3. Criar o commit
    4. Enviar para o Github
    
Ideal para procedimentos que precisam ser executados em ordem.

10. Listas de tarefas - Checklists
O github permite criar caixas de seleção
    - [ ] Criar o repositório
    - [x] Criar o README
    - [ ] Realiza a atividade
    - [ ] Criar o commit
    - [ ] Envia para o Github

Esse recurso é especialmente útil para  compartilhar atividades e projetos.