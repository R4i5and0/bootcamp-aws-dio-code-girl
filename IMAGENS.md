## ✨ Os Tipos de Instâncias EC2  
![Imagem explicativa sobre tipos de instância EC2](imagem1.png)

---

## 🤓 Entendendo a Nomenclatura das Instâncias EC2

### `c7gn.xlarge` – O que esse nome significa?

O nome de uma instância EC2 segue uma convenção que revela suas principais características. Vamos entender cada parte:

#### 🧩 Componentes do Nome

- **`c` – Família da Instância:**  
  Computação Otimizada. Ideal para tarefas intensivas em CPU, como processamento em lote e codificação de vídeo.

- **`7` – Geração da Instância:**  
  Representa a geração atual. Quanto maior o número, mais recente e eficiente.

- **`g` – Família do Processador:**  
  Indica uso de processadores AWS Graviton (baseados em ARM).

- **`n` – Capacidade Adicional:**  
  Rede otimizada, com maior performance de pacotes por segundo e menor latência.

- **`.xlarge` – Tamanho da Instância:**  
  Define os recursos (vCPU, memória, largura de banda). Por exemplo, `2xlarge` tem o dobro de capacidade de uma `xlarge`.

---

💡 **Resumo:**  
A nomenclatura `c7gn.xlarge` não é aleatória — ela encapsula informações sobre desempenho, arquitetura e capacidade da instância EC2.

---

## 🧠 Mapa Visual dos Serviços de Computação da AWS  
![Imagem com diagrama de serviços de computação AWS](imagem2.png)

---

## 🔍 Explicação do Diagrama

Este diagrama apresenta os principais serviços de computação da AWS, organizados por categoria:

### 🖥️ EC2 – Instâncias Virtuais
- Amazon EC2  
- EC2 Auto Scaling  
- EC2 Image Builder  
- Amazon Lightsail

### 📦 Containers
- Amazon ECS / ECS Anywhere  
- Amazon EKS / EKS Anywhere  
- Amazon ECR  
- AWS Fargate  
- AWS Batch

### ⚡ Serverless
- AWS Lambda  
- AWS Fargate

### 🌍 On-premises / Edge
- AWS Local Zones  
- AWS Dedicated Local Zones  
- AWS Outposts  
- AWS Wavelength

### 💰 Otimização de Custos
- EC2 Spot Instances

### 🔀 Elastic Load Balancing (ELB)
- Application Load Balancer  
- Network Load Balancer  
- Gateway Load Balancer

---

💡 **Dica:**  
Esse mapa ajuda a entender como os serviços se conectam e qual escolher para cada tipo de aplicação.

---

## 🧩 Diagrama de Nomeação EC2 (Versão Visual)  
![Imagem com diagrama de nomeação EC2](imagem3.png)

---

## 📘 Convenção do Nome dos Tipos de Instância

Este diagrama mostra visualmente como o nome de uma instância EC2 é construído:

- **`c`** → Família da instância  
- **`7gn`** → Geração + Processador + Capacidade adicional  
- **`xlarge`** → Tamanho da instância

---

✏️ *Legenda:*  
"Convenção do nome dos tipos de instância  
Entendendo mais sobre os nomes"
