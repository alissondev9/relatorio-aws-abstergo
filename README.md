# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 17 de fevereiro de 2026  
**Empresa:** Abstergo Industries  
**Responsável:** Alisson Moura

---

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por **Alisson Moura**. O objetivo do projeto foi selecionar 3 serviços AWS com a finalidade de promover a redução imediata de custos operacionais, mantendo desempenho, disponibilidade e segurança das aplicações.

---

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com objetivos específicos voltados à otimização de recursos e economia.

---

### Etapa 1
- **Nome da ferramenta:** Amazon EC2 Auto Scaling  
- **Foco da ferramenta:** Ajuste automático de capacidade computacional conforme a demanda  
- **Descrição de caso de uso:**  
Foi implementado o Auto Scaling para ajustar automaticamente a quantidade de instâncias EC2 em execução. Durante horários de menor uso, o sistema reduz o número de servidores ativos, diminuindo custos com processamento. Em períodos de pico, novas instâncias são criadas automaticamente para manter a performance, evitando gastos desnecessários com capacidade ociosa.

**Benefício principal:** Redução de custos com infraestrutura subutilizada.

---

### Etapa 2
- **Nome da ferramenta:** Amazon S3 Intelligent-Tiering  
- **Foco da ferramenta:** Otimização automática de custos de armazenamento  
- **Descrição de caso de uso:**  
Os arquivos armazenados no Amazon S3 foram migrados para a classe Intelligent-Tiering, que move automaticamente os dados entre camadas de armazenamento de acordo com a frequência de acesso. Dados pouco acessados passam para camadas mais baratas, sem necessidade de intervenção manual.

**Benefício principal:** Redução automática de custos de armazenamento sem perda de disponibilidade.

---

### Etapa 3
- **Nome da ferramenta:** AWS Cost Explorer + AWS Budgets  
- **Foco da ferramenta:** Monitoramento e controle de gastos  
- **Descrição de caso de uso:**  
Foi implementado o AWS Cost Explorer para análise detalhada dos custos por serviço, e o AWS Budgets para criação de alertas quando os gastos se aproximam dos limites definidos. Isso permite ação preventiva antes que os custos ultrapassem o orçamento.

**Benefício principal:** Controle financeiro e prevenção de gastos inesperados.

---

## Conclusão
A implementação das ferramentas na empresa **Abstergo Industries** tem como resultado esperado a redução imediata de custos operacionais em nuvem, maior eficiência no uso dos recursos e melhor controle financeiro, o que aumentará a eficiência e a produtividade da empresa.

Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias e práticas de otimização, como instâncias reservadas, arquitetura serverless e políticas de desligamento automático de recursos ociosos.

---

## Anexos
- Planilha de estimativa de custos antes e depois da implementação  
- Capturas de tela do AWS Cost Explorer  
- Documentação das políticas de Auto Scaling  
- Relatório de configuração do S3 Intelligent-Tiering  

---

**Assinatura do Responsável pelo Projeto:**  
Alisson Moura
