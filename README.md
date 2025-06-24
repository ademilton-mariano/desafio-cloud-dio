# Relatório de Implementação de Serviços AWS

**Data:** 24/06/2025  
**Empresa:** Abstergo Industries  
**Responsável:** Ademilton Mariano

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por **Ademilton Mariano**. O objetivo do projeto foi elencar e aplicar três serviços AWS com foco em **redução imediata de custos**, **melhoria de desempenho** e **automação de tarefas operacionais**.

## Descrição do Projeto

O projeto foi dividido em **três etapas principais**, cada uma responsável por abordar um aspecto estratégico para a empresa: computação, armazenamento e monitoramento. Abaixo, detalhamos cada etapa:

### Etapa 1: Amazon EC2 com Auto Scaling e Spot Instances
- **Foco da ferramenta:** Computação escalável com custo otimizado.
- **Descrição de caso de uso:**  
  Substituímos os servidores físicos e instâncias sob demanda por **instâncias Spot EC2** integradas com **Auto Scaling Groups**. Isso permitiu executar cargas de trabalho não críticas com redução de até 70% nos custos. Em horários de pico, o Auto Scaling ajusta automaticamente o número de instâncias.

### Etapa 2: Amazon S3 com S3 Intelligent-Tiering
- **Foco da ferramenta:** Armazenamento inteligente e econômico de dados.
- **Descrição de caso de uso:**  
  Migramos os backups e documentos arquivados para o **Amazon S3**, ativando a política de **Intelligent-Tiering**, que move automaticamente os objetos entre classes de armazenamento de acordo com o acesso.

### Etapa 3: Amazon CloudWatch
- **Foco da ferramenta:** Monitoramento e alertas automáticos.
- **Descrição de caso de uso:**  
  Configuramos **CloudWatch** para coletar logs e métricas de aplicações e servidores. Criamos alarmes de uso de CPU, falhas em APIs e limites de billing.

## Conclusão

A implementação dos serviços AWS trouxe **redução de custos operacionais**, **melhoria na gestão dos recursos computacionais** e **maior controle sobre o ambiente de TI**. Recomenda-se continuar investindo em soluções baseadas em nuvem e realizar revisões periódicas das políticas de uso para garantir a otimização contínua dos recursos.

## Anexos

- 📘 [policy-s3-intelligent-tiering.json](./policy-s3-intelligent-tiering.json)  
- 🧾 [relatorio-economias.csv](./relatorio-economias.csv)  
- 🔔 [alertas-cloudwatch.txt](./alertas-cloudwatch.txt)  
- 📄 [manual-ec2-spot.pdf](./manual-ec2-spot.pdf)  
- 🖼️ [diagrama-arquitetura.png](./diagrama-arquitetura.png)

---

**Assinatura do Responsável pelo Projeto:**  
**Ademilton Mariano**
