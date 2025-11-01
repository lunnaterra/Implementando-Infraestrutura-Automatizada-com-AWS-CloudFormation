# Desafio AWS CloudFormation - DIO

## Descrição do Projeto
Este projeto foi criado como parte do desafio DIO para demonstrar a implementação de infraestrutura automatizada na AWS usando CloudFormation.

## Objetivos
- Aplicar conceitos de Infraestrutura como Código (IaC) usando AWS CloudFormation.
- Criar uma stack automatizada com múltiplos recursos AWS.
- Documentar o processo para referência futura e estudo.

## Estrutura do Repositório
- `templates/` → Contém o template CloudFormation (`minha_stack.yaml`).
- `README.md` → Documentação detalhada do projeto.

## Recursos Criados
1. Bucket S3 (`MeuBucketS3`)
2. Instância EC2 (`MinhaInstanciaEC2`)
3. Security Group (`MeuSecurityGroup`) permitindo acesso SSH.

## Passos para Deploy
1. Fazer login no console AWS ou via AWS CLI.
2. Navegar até CloudFormation e criar uma nova stack.
3. Selecionar o template `minha_stack.yaml`.
4. Preencher parâmetros necessários.
5. Criar a stack e aguardar sua finalização.
6. Verificar os recursos criados no console AWS.

## Aprendizados
- Criação de recursos AWS automatizados via CloudFormation.
- Estruturação de templates YAML e organização em repositório.
- Controle de versão de templates com GitHub.

