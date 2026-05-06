# AWS Scalable Web Architecture

Projeto prático demonstrando uma arquitetura web escalável na AWS, utilizando serviços gerenciados e boas práticas de alta disponibilidade.

---

## 📌 Arquitetura

A solução simula uma aplicação web distribuída com separação entre frontend e backend, utilizando serviços da AWS para garantir performance, escalabilidade e resiliência.

### Componentes:

- **Amazon S3** → Hospedagem do frontend estático
- **CloudFront** → CDN para distribuição global
- **Application Load Balancer (ALB)** → Balanceamento de carga
- **EC2** → Backend (simulação com Nginx)

---

## 📂 Estrutura do Projeto


---

## 🚀 Fluxo da Aplicação

1. Usuário acessa a aplicação via CloudFront
2. CloudFront entrega conteúdo estático do S3
3. Requisições dinâmicas são encaminhadas para o ALB
4. ALB distribui para instâncias EC2 (backend)
5. Backend responde via Nginx

---

## 🎯 Objetivo

Demonstrar na prática:

- Arquitetura escalável na AWS
- Separação de camadas (frontend / backend)
- Uso de CDN para performance global
- Balanceamento de carga
- Conceitos de alta disponibilidade

---

## 📸 Evidências

As imagens na pasta `evidence/` demonstram:

- Configuração do S3
- Distribuição CloudFront
- Load Balancer
- Instâncias EC2
- Aplicação em execução

---

## 🛠 Tecnologias utilizadas

- AWS S3
- AWS CloudFront
- AWS ALB
- AWS EC2
- Nginx
- HTML

---

## 💡 Próximos passos (melhorias)

- Implementar Auto Scaling Group
- Adicionar HTTPS com ACM
- Integrar com Route 53
- Monitoramento com CloudWatch
- Deploy automatizado (CI/CD)

---

## 👩‍💻 Autor

Projeto desenvolvido por Suzana Almeida  
Foco em Cloud, Arquitetura e Soluções Escaláveis
