# Integração contínua

É o processo de integrar modificações de codebase de forma contínua e automatizada, evitando assim erros humanos de verificação, garantindo mais agilidade e segurança no processo de desenvolvimento de um software

## Principais processos

- Execução de testes;
- Linter;
- Verificações de qualidade de código;
- Verificações de segurança;
- Geração de artefatos pontos para o processo de deploy;
- Identificação da próxxima versão a ser gerada no software;
- Geração de tags e releases.

## Status Check

- È a garantial que uma PR não podera ser mergeada ao repositório em antes ter passado pelo CI ou CR;

## Ferramentas populares

 - Jenkins;
 - Github Actions;
 - AWS Code Build;
 - Azure DevOps;
 - Google Cloud Build;
 - GitLab Pipelines /CI;

 ## Dinâmica

 - São conjunto de processos definidos por você. EX: Fazero build + rodar os testes de aplicação;
 - É possível ter mais do que um workflow por repositório
  - Definidos em arquivos `.yaml` em `.github/workflows`
  - Possui um ou mais `Jobs`
  - É iniciado baseado em eventos do GitHub ou através de agendamento.
  
  ![Alt text](workflow.png)

  ## Actions

   - É a ação que de fato será executada em um dos Steps de um Job em um Workflow. Ela pode ser Criada do zero ou ser reutilizada de actions pre-existentes.