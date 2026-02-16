## Kubernetes Infrastructure – Resilience & Auto-Scaling Lab

🚀 Projeto de infraestrutura cloud-native desenvolvido com 
foco em orquestração de containers, alta disponibilidade e escalabilidade automática utilizando Kubernetes.

📌 **Sobre o projeto**
Este projeto consiste na implementação de uma infraestrutura robusta utilizando Kubernetes (Kind), projetada para hospedar aplicações de forma resiliente. O objetivo foi criar um ambiente que simula cenários reais de produção, onde a aplicação precisa se comportar de forma inteligente diante de picos de acesso ou falhas de hardware.

Durante o desenvolvimento, tive a oportunidade de aplicar e consolidar conhecimentos em SRE (Site Reliability Engineering) e DevOps, configurando um cluster multi-node capaz de realizar auto-cura (self-healing) e balanceamento de carga dinâmico, resultando em uma aplicação funcional, estável e escalável.

## 🧠 Tecnologias utilizadas

## Orquestração e Containers
**Kubernetes** (K8s) – Orquestração e gerenciamento de **containers** em escala.

**Kind** (Kubernetes in Docker) – Criação de clusters locais multi-node.

**Docker** – Tecnologia de containerização da aplicação e dos nós do cluster.

**Monitoramento e Escalabilidade**
**HPA** (Horizontal Pod Autoscaler) – Escalabilidade **horizontal** automática baseada em demanda.

**Metrics Server** – Coleta de dados de consumo de recursos do cluster.

**Kubernetes Dashboard**– Interface gráfica para gestão e monitoramento.

## Outras tecnologias e ferramentas
**Nginx** – Servidor web para entrega de conteúdo.

**Git & GitHub** – Versionamento de código e documentação.

**YAML** – Definição de infraestrutura como código (IaC).

## ⚙️ Funcionalidades
Cluster Multi-Node composto por 1 nó Control-Plane e 2 nós Workers.

Auto-Scaling dinâmico que ajusta o número de instâncias conforme a carga de trabalho.

Resiliência (Self-Healing) com detecção de falhas e redistribuição automática de carga.

Gestão de Recursos otimizada para garantir a estabilidade dos nós sobreviventes em casos de desastre.

Monitoramento centralizado via Dashboard oficial para acompanhamento de pods, serviços e eventos.

## 📚 Aprendizados e desafios
O desenvolvimento deste projeto de infraestrutura foi uma excelente oportunidade para aprofundar conhecimentos em diversas áreas, incluindo:

Planejamento de capacidade e organização de workloads em clusters.

Configuração de escalonamento automático para otimização de performance.

Resolução de desafios técnicos relacionados a limites de CPU e memória.

Integração de componentes de monitoramento e métricas em tempo real.

Simulação de desastres para validação da resiliência do sistema.

Aplicação de boas práticas de infraestrutura imutável e escalável.


## 🤝 Contato
Para mais informações, sugestões ou oportunidades:

## 🔗 GitHub: **https://github.com/ViniciusFroggel/Kubernetes-project**