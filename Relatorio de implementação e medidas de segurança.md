# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

Data: 20/08/2025  
Empresa: ALM TECNOLOGIA  
Responsável: ALAN MENDES

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa **ALM TECNOLOGIA**, realizado por **ALAN MENDES**. O objetivo do projeto foi elencar medidas de segurança em conformidade com os serviços da AWS, com a finalidade de robustecer e aumentar a segurança na empresa.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas principais de segurança. A seguir, são descritas as etapas da implementação:

Medida 1:  
- **Gerenciamento de Acessos (IAM + Responsibility Model)**  
  Implantação do modelo de responsabilidade compartilhada da AWS, criação de usuários IAM com princípio do menor privilégio, ativação de MFA para usuários administrativos, uso de grupos e políticas customizadas para controle de acesso refinado e segregação de funções.

Medida 2:  
- **Criptografia e Conformidade (AWS Organizations / KMS / Trusted Advisor)**  
  Estruturação da conta-mestre utilizando o AWS Organizations para padronização das políticas de segurança nas contas filhas, ativação de criptografia em repouso com AWS KMS nos serviços (EBS/RDS/S3) e uso do Trusted Advisor para verificação contínua de boas práticas e conformidade.

Medida 3:  
- **Monitoramento e Auditoria (CloudWatch, CloudTrail, AWS Config)**  
  Ativação do AWS CloudTrail para trilhas de auditoria, configuração do AWS Config para registrar mudanças de configuração nos recursos e criação de alarmes e dashboards no Amazon CloudWatch a fim de monitorar eventos suspeitos, além da implantação de alertas de segurança em tempo real.

## Conclusão
A implementação das ferramentas na empresa **ALM TECNOLOGIA** gerou como resultado o fortalecimento da postura de segurança do ambiente AWS, garantindo conformidade com as melhores práticas recomendadas. A padronização dos acessos, proteção por criptografia, além de visibilidade total sobre alterações e logs, contribuíram diretamente para a redução de riscos e aumento do nível de governança da infraestrutura em nuvem.