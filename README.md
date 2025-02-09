# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

## Definição de cloud

- O que é cloud?
  Se trata de computação em nuvem que é a entrega de serviços de TI atravês da internet
  
- Tipos de Nuvem:
- Tipos de Serviço e nuvem
- Responsabilidade compartilhada

## Benefícios da Cloud

- alta disponibilidade - refere-se a sla
- escalabilidade - capacidade de ajuste dos recursos para atender as demandas
- elasticidade - dimensionamento automático do ambiente de acordo com as requisições.
- confiabilidade - recuperação de falha, resiliência
- previsibilidade - monitoramento de despesas
- segurança - a nuvem oferece ferramentas da segurança, mas a implementação é responsabilidade do cliente
- Governança - auditoria de nuvem, conformidade
- Gerenciabilidade - capacidade de gerenciamento pelo console, linha de comando, chamadas de API, PowerShell

## Definição dos Serviços da Nuvem e Responsabilidade compartilhada

- Tipos de Nuvem:
    - Púbilca
    - Privada
    - Híbrida
    - Multinuvem
 
- Tipos de Serviço e nuvem
  - Iaas: Infra como serviço
  - Saas: Software como serviço
  - Paas: Plataforma com serviço
    
- Responsabilidade Compartilhada
    - Responsabilidade do cliente
    - Resposabilidade do provedor da nuvem
    - Responsabilidade do provedor e cliente
    
![Captura de tela 2024-11-12 125943](https://github.com/user-attachments/assets/beff1938-2986-4a1f-8a65-be1857312e4e)

## Computação e Rede


Os Serviços de Computação do Azure oferecem uma base flexível e confiável para diversas necessidades de empresas, nessa aula falamos sobre:
 - Máquinas virtuais: que usam recursos como Conjuntos de Disponibilidade, Conjuntos de Atualização e Conjuntos de Dimensionamento para garantir que os serviços fiquem sempre disponíveis e funcionando bem.
   - Os Conjuntos de Disponibilidade protegem as VMs contra problemas físicos, distribuindo-as em diferentes racks dentro do datacenter.
   - Os Conjuntos de Atualização organizam as VMs em grupos, garantindo que atualizações e manutenções não interrompam tudo ao mesmo tempo.
   - Conjuntos de Dimensionamento permitem ajustar automaticamente a quantidade de VMs conforme a demanda, ajudando a economizar e melhorar o desempenho.
 - Contêineres do Azure: Permitem rodar aplicativos de forma leve e eficiente, com suporte para Kubernetes e instâncias independentes.
 - A Área de Trabalho Virtual: Facilita o acesso remoto seguro a desktops, garantindo flexibilidade e desempenho.

- Azure Functions: com ele é possível executar código sob demanda sem precisar de servidores, ideal para automação e escalabilidade.
- Serviços de Aplicativo: Simplificam a criação, hospedagem e gerenciamento de aplicativos web e APIs, com suporte a várias linguagens e alta disponibilidade.

## Armazenamento do Azure

- Contas de armazenamentos
  - Fila
  - Tabela
  - Conteiner
  - Compartilhamento de arquivos (SMB)
 
- Migração para Azure
  - Família DataBox
    - Data Box Disk - 35TB
    - Data Box - 80TB
    - Data Box Heavy - 800TB
    - Importação/Exportão de Job - a partir de 1TB
  - Aplicativos web
  - Banco de Dados (somente)
  - Servidores, banco de dados e aplicativos web
  - AzCopy (Terminal)
  - Storage Explorer (Gráfico)


 ## Arquitetura e serviços do Azure

- Microsoft Entra ID (antigo Azure active Directory) Usuários criados na nuvem não sincroniza com on-premises, mas o inverso funciona.

- Autenticação - verifica se o usuário pode logar e acessar osa recursos
- Autorização - depois de logado, o que o usuário tem permissão para fazer

### Autenticação:

- Logon único (SSO)
- Gerenciamento de aplicativos.
- Negócios para Negócios (B2B) - usuários externos (fornecedores ou parceiros) através de convite ou inscrição tem permissão para logar no ambiente, com suas devidas permissões
- Negócios para Consumidores (B2C) - é autenticado através de uma assinatura Google, Facebbok...

- Autenticação multifator - exige dois ou mais elementos para autenticação, o wur torna o acesso mais seguro

- Acesso Condicional -  avalia não apenas se o usuário e senha (ou MFA) estão batendo, mas se há algo incomum no acesso do usuário, como: Local do IP, dispositivo, aplicativo, horário. Ajuda a tornar o ambiente mais seguro e detectar possíveis risco de acesso de pessoas não autorizadas

- RBAC (acesso baseado em função) - permite um gerenciamento de acesso mais granular, liberando apenas o que o usuário pode utilizar

- Política de Confiança Zero - não confiar em ninguém

- Proteção completa (proteção em camadas) - Fornece vários níveis de proteção para dificultar a ação de agentes maliciosos, caso ocorra.

### Microsoft Defender para Nuvem - é um serviço de monitoramento que fornece proteção contra ameaças nos datacenters do Azure GCP, AWS e locais de forma centralizada, fornecendo recomendações de segurança, identificação de ataques potenciais...


