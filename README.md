# PROJETO-FINAL-COMPASS
# 🚀 **PROJETO FINAL - KUBERNETES**
![Alt text](Images/CompassUOL.jpeg)
## 👥 **EQUIPE 1:**
- **Fabio Veras**  
- **Igor Junqueira**  
- **Victor de Souza Custodio**  

---

## 🎯 **Proposta de Solução para a Fast Engineering S/A**
**Empresa:** 🏢 TI Soluções Incríveis  
**Objetivo:** Desenvolver uma **arquitetura escalável, segura e gerenciada** por serviços AWS para atender ao crescimento de acessos e transações do eCommerce da Fast Engineering S/A.  
**Foco:** Implementar **melhores práticas DevOps** para garantir alta disponibilidade e desempenho.

---

## 🛠️ **1. Escopo do Projeto**

✅ **Design e Implementação** de infraestrutura baseada em Kubernetes na AWS.  
✅ **Migração e Otimização** do banco de dados com serviços gerenciados da AWS.  
✅ **Configuração de Armazenamento Persistente** para dados críticos e arquivos estáticos.  
✅ **Balanceador de Carga** com verificações automáticas de integridade (*health checks*).  
✅ **Segurança e Backups** robustos para proteção de dados.  
✅ **Monitoramento e Alertas** com ferramentas nativas da AWS.  
✅ **Elaboração do Diagrama** completo da nova arquitetura.  
✅ **Estimativa de Orçamento** para os serviços utilizados.  
✅ **Cronograma Macro** de entregas.

---

## 🏗️ **2. Arquitetura da Nova Solução**
![Alt text](Images/ArquiteturaProposta.png)
### **🔑 Componentes Principais:**
- **Amazon EKS (Elastic Kubernetes Service):** Hospedagem dos contêineres da aplicação React com suporte Multi-AZ para alta disponibilidade.  
- **Amazon RDS for MySQL:** Banco de dados gerenciado em PaaS com replicação Multi-AZ e backups automáticos.  
- **Amazon S3:** Armazenamento de arquivos estáticos e conteúdo multimídia com políticas de acesso restritas.  
- **Elastic Load Balancer (ELB):** Distribuição eficiente do tráfego com health checks automáticos.  
- **Amazon EFS (Elastic File System):** Sistema de arquivos compartilhado para persistência de dados entre pods.  
- **AWS IAM:** Controle rigoroso de acesso com políticas de menor privilégio.  
- **TLS/SSL:** Criptografia de tráfego para segurança dos dados em trânsito.
---

### **🔒 Segurança e Melhores Práticas:**
- **Configuração de VPC:** Sub-redes públicas e privadas para isolamento.  
- **Regras de Segurança:** Controle de acessos por portas específicas.  
- **Backups Automáticos:** Políticas de retenção para proteção de dados críticos.

---

## 💵 **3. Valores**

### **📊 Estimativa Mensal de Infraestrutura:**
![Alt text](Images/Orçamento1.jpeg)
![Alt text](Images/Orçamento2.jpeg)

*(Valores aproximados dependendo da escala e serviços utilizados.)*  

### **💼 Custos de Implementação:**
- **Configuração e Migração:** `$18,000`  
- **Consultoria e Treinamento:** `$4,000`  

---

## 🗓️ **4. Cronograma Macro de Entregas** *(1 mês)*

- **Semana 1:** Configuração inicial do EKS, VPC e IAM.  
- **Semana 2:** Migração do banco de dados para o RDS e setup do ELB.  
- **Semana 3:** Testes de carga, segurança e monitoramento.  
- **Semana 4:** Ajustes finais, documentação e entrega oficial.

---

## ⚙️ **Estratégias de Execução**
![Alt text](Images/DevSecOps.png)

1. **🛠️ Equipes Paralelas:** Configuração simultânea de EKS, RDS e ELB para otimizar o tempo.  
2. **🤖 Automação:** Uso de DevOps Tools e CloudFormation para provisionamento de infraestrutura.  
3. **📜 Scripts de Migração:** Automação para migração de dados eficiente.  
4. **📈 Monitoramento Ativo:** Dashboards com CloudWatch para análises em tempo real.  
5. **🚨 Plano de Contingência:** Mitigação de riscos em todas as etapas do projeto.

---

## 📝 **Considerações Finais**

Com uma equipe experiente em AWS e DevOps, a entrega em 1 mês é totalmente **viável**.  
A proposta garante:  
- **🔒 Segurança**  
- **📈 Escalabilidade**  
- **⚡ Alta Disponibilidade**  

Tudo isso para sustentar o crescimento de acessos e transações do eCommerce da **Fast Engineering S/A**! 🌐 

![Alt text](Images/AWS.jpeg)
