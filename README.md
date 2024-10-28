# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

Resumo:
Objetivo Geral
Nível de conhecimento básico sobre:
•	Conceitos do Azure
•	Principais serviços do Azure
•	Principais soluções e ferramentas de gerenciamento, segurança geral e segurança de rede
•	Governança, privacidade e recursos de conformidade e gerenciamento de custos do Azure

Prova AZ-900 (Certificação de entrada)
Tendência a nivelar o seu conhecimento de cloud de uma forma geral
Cloud - Data Center virtualizado (servidores, recursos e aplicações de todo tipo)

Conteúdo Programático
•	Computação em nuvem
•	Benefícios da nuvem
•	Tipos de serviços de nuvem

Módulo 1: Conceitos de Nuvem
AZ-900: Introdução aos Conceitos Básicos do Microsoft Azure
Computação em nuvem
•	O que é computação em nuvem
•	Responsabilidade compartilhada
•	Modelos de nuvem
•	Custo de capital versus custo operacional (FinOps)

Computação em nuvem: domínio do objetivo
•	Definir computação em nuvem.
•	Definir modelos de nuvem, incluindo público, privado e híbrido.
•	Identificar os casos de uso apropriado para cada modelo de nuvem.
•	Descreve o modelo baseado no consumo.
•	Comparar os modelos de preços de nuvem.

O que é computação em nuvem?
A computação em nuvem é o fornecimento de serviços de computação pela Internet, habilitando inovações mais rápidas, recursos flexíveis e economias de escala.
Toda empresa precisa ter um Date Center com vários servidores. Com o tempo, cada vez mais se tornou necessário ter mais máquinas (data center maior, etc). Virtualização de computadores e de servidores. Emular em uma máquina várias outras máquinas. Se tornou insustentável para alguns tipos de operações (caro). Computação em nuvem = virtualização não criada por empresas, mas por grandes plataformas (Microsoft, Amazon, Google, Oracle). Fornecimento de serviços através da internet. Criar recursos de maneira muito rápida. Criar, excluir, alterar ambientes inteiros através de um portal na internet. Computação em nuvem entrega serviços através da internet de uma maneira muito rápida pagando somente pelo que usa. Criar recursos e entregar para os clientes de uma maneira muito mais rápida.

Nuvem Privada
•	As organizações criam um ambiente em nuvem em seu próprio data center
•	As organizações são responsáveis por operar os serviços que fornecem.
•	Não fornece acesso aos usuários fora da organização
Ambiente 100% on-premise (consiste em construir um sistema de TI local utilizando a infraestrutura do seu empreendimento)
Arquitetura, servidores, roteadores, firewall próprios somente para a minha empresa.
Ambiente em nuvem no seu data center
	As organizações têm controle total sobre os recursos e a segurança.
	As organizações são responsáveis pela manutenção e pelas atualizações de hardware.

Nuvem Pública
•	Pertence a serviços de nuvem ou provedor de hosting
•	Fornece recursos e serviços a várias organizações e usuários
•	Acessada via conexão de rede segura (geralmente pela Internet)
Entrega de serviços e recursos a uma série de cliente por meio de um único provider.
Não existe divisão por categoria (cliente, pessoa física)
	Nenhuma despesa de capital vai ser exigida para você escalar, você não paga na hora, você paga somente depois.
	As organizações pagam apenas pelo que utilizam.

Nuvem Híbrida
•	Combina nuvens públicas e privadas para permitir que os aplicativos sejam executados no local mais adequado.
Pode comunicar recursos da nuvem privada a pública e vice-versa.
	As organizações determinam onde executar seus aplicativos.
	As organizações controlam a segurança, a conformidade e os requisitos legais.
	Fornece a maior flexibilidade.

Despesas de capital (CapEx)
•	O gasto inicial de dinheiro em infraestrutura física.
•	As despesas da CapEx têm um valor que se reduz com o tempo.

Despesas operacionais (OpEx)
•	Gastar com produtos e serviços conforme necessários, pagamento conforme o uso
•	Seja cobrado imediatamente.

Modelo baseado em consumo
Melhor previsão de custos. (Painel para acompanhar os custos)
São fornecidos preços para recursos e serviços individuais.
A cobrança é feita com base no seu uso real.
Quando o recurso fica indisponível, recebe créditos para recompensar
Na nuvem, você paga conforme o seu uso (visibilidade com você está gastando, consegue colocar travas em cima de custo, painel específico par analisar o custo e indicações sobre como você está utilizando seus recursos, se há modelos de economia que podem ser aplicados.

Sistemas de Controle de Versão
Controlam as versões de um arquivo ao longo do tempo.
Registra o histórico de atualizações de um arquivo;
Gerencia quais foram as alterações, a data, o autor, etc;
Organização, controle e segurança.

Dentre os Sistemas de Controle de Versão (VCS), temos:
VCS Centralizado (CVCS)
Ex.: CVS, Subversion.
Apenas um servidor que contém todos os arquivos responsáveis pelo controle de versão

Caso ele fique fora do ar, não é possível salvar ou colaborar com alguma interação.
VCS Distribuído (DVCS)
Ex.: Git, Mercurial.
O banco de versão é duplicado localmente, possui uma cópia do que está no servidor principal, e permite edição mesmo com os servidores fora do ar.
 
Clona o repositório completo, o que inclui o histórico de versões.
Cada clone é um backup;
Possibilita um fluxo de trabalho mais flexível;
Possibilidade de trabalhar sem conexão à rede.

Sistema de Controle de Versão Distribuído.
•	Gratuito e Open Source (Código Aberto);
•	Ramificações (branching) e fusões (merging) eficientes;
•	Leve e rápido.
https://git-scm.com/
git clone → clona um repositório Git existente para um novo diretório (pasta) local.
git commit → grava alterações no repositório.
git pull → “puxa” as alterações do repositório remoto para o local (busca e mescla).
git push → “empurra” as alterações do repositório local para o remoto.

O que é GitHub?
Plataforma de hospedagem de código para controle de versão com Git, e colaboração 

Aprendizagem Baseada em Projetos (PBL)
Método de imergir em grandes ideias e criar soluções tangíveis. Neste método, você constrói projetos práticos que refletem problemas e desafios do mundo real. Esses projetos não apenas aumentam seu conhecimento, mas também demonstram suas competências.

O que é um Projeto Open Source?
É um projeto de Código Aberto, livre para ser utilizado, modificado e distribuído. Alguns exemplos são:
Linux, sob a licença GNU General Public License (GPL);
Roadmaps DIO, sob a licença MIT License (MIT).

Formas de contribuir em um Projeto Open Source
	Relatar algum problema ou bug;
	Sugerir melhorias ou adição de novos recursos;
	Escrever ou atualizar a documentação;
	Contribuir com um código;
	Divulgar e/ou doar.

Ao final do módulo, pude colocar todos meus conhecimentos adquiridos em prática, com o projeto de adicionar meu profile README e abrindo um Pull Request solicitando a atualização do repositório original da DIO.
