## ✨ Os Tipos de Instâncias EC2  
<img width="714" height="425" alt="image" src="https://github.com/user-attachments/assets/39eee973-a9c2-42c8-9fbe-34de4255ee77" />

---

## 🤓 Entendendo a Nomenclatura das Instâncias EC2

### Significado do Nome de uma Instância EC2: `c7gn.xlarge`

O nome de uma instância EC2, como `c7gn.xlarge`, segue uma convenção que descreve suas principais características. Cada parte do nome fornece informações específicas sobre a família, geração, processador, capacidades adicionais e tamanho da instância.

### 🧩 Componentes do Nome

#### 🔹 `c` – Família da Instância (Instance Family)
- Indica o tipo de carga de trabalho para o qual a instância é otimizada.
- `c` significa **Computação Otimizada** (*Compute Optimized*).
- Ideal para tarefas que exigem alto poder de processamento, como:
  - Processamento em lote
  - Codificação de vídeo

#### 🔹 `7` – Geração da Instância (Instance Generation)
- Representa a geração da família da instância.
- Gerações mais altas (como `7`) são:
  - Mais novas
  - Mais poderosas
  - Com melhor custo-benefício em relação às anteriores

#### 🔹 `g` – Família do Processador (Processor Family)
- Indica características específicas do hardware.
- `g` significa que a instância utiliza **processadores AWS Graviton** (baseados em ARM).

#### 🔹 `n` – Capacidade Adicional (Additional Capability)
- Sinaliza capacidades extras da instância.
- `n` indica **rede otimizada** (*Optimized Networking*), oferecendo:
  - Maior performance de pacotes por segundo (PPS)
  - Latências mais baixas

#### 🔹 `.xlarge` – Tamanho da Instância (Instance Size)
- Define o tamanho da instância e seus recursos.
- Os tamanhos são relativos dentro da mesma família:
  - Por exemplo, `2xlarge` tem o dobro de recursos (vCPU, memória) de uma `xlarge`.
- Também influencia diretamente na **largura de banda de rede** disponível.

---

💡 **Resumo**:  
A nomenclatura `c7gn.xlarge` não é aleatória — ela encapsula informações cruciais sobre desempenho, arquitetura e capacidade da instância EC2.

---

## ✨ Explicação do Diagrama de Serviços de Computação da AWS  
<img width="789" height="941" alt="image" src="https://github.com/user-attachments/assets/5a0389bb-6347-4457-bb67-6be8c16f9450" />

---

## 🧠 Mapa Visual dos Serviços de Computação da AWS

Esta imagem apresenta um panorama organizado dos principais serviços e componentes que formam o ecossistema de **Computação (Compute)** da Amazon Web Services. Os elementos estão agrupados em áreas funcionais, facilitando a compreensão do papel de cada serviço.

---

## 🔹 1. Amazon EC2 e seus Componentes *(Canto Superior Esquerdo)*

- **Amazon EC2:** Serviço principal para criar servidores virtuais (instâncias).
- **AMI (Amazon Machine Image):** Templates usados para criar novas instâncias.
- **Instances:** Máquinas virtuais com diferentes tipos e tamanhos.
- **Auto Scaling:** Adiciona ou remove instâncias automaticamente conforme a demanda.
- **Instance with CloudWatch:** Integração nativa com o serviço de monitoramento CloudWatch.
- **Spot Instance / Spot Fleet:** Modelos de preço reduzido que utilizam capacidade ociosa da AWS.
- **Elastic IP address:** Endereços IP estáticos associáveis às instâncias.

---

## 🐳 2. Serviços de Contêineres e Simplificados *(Canto Superior Direito)*

- **Amazon ECR (Elastic Container Registry):** Armazena e gerencia imagens de contêiner (ex: Docker).
  - Ícone: `ECR registry` representa o repositório de imagens.
- **Amazon ECS (Elastic Container Service):** Orquestra e executa aplicações em contêineres.
  - Ícones: `EC2 compute container` indicam execução em instâncias EC2.
- **Amazon Lightsail:** Plataforma simplificada com pacotes fáceis de usar — ideal para iniciantes.

---

## 🌐 3. Rede e Conectividade *(Amazon VPC – Canto Inferior Esquerdo)*

- **Amazon VPC:** Cria uma rede virtualmente isolada na nuvem.
- **Ícones de Rede:**
  - `Internet Gateway`: Acesso à internet
  - `Router`: Direcionamento de tráfego interno
  - `VPN Gateway`: Conexão com rede local
  - `VPC Peering`: Conexão entre diferentes VPCs

---

## ⚙️ 4. Outros Serviços de Computação e Balanceamento de Carga *(Canto Inferior Direito)*

- **AWS Batch:** Executa grandes volumes de trabalhos em lote.
- **AWS Elastic Beanstalk:** Plataforma como Serviço (PaaS) para implantação simplificada de aplicações.
  - Ícones: `Application` e `Deployment` representam o processo.
- **AWS Lambda:** Computação sem servidor (Serverless) que executa código em resposta a eventos.
  - Ícone: `Lambda function`
- **Elastic Load Balancing:** Distribui tráfego entre instâncias EC2.
  - Tipos: `Classic Load Balancer` e `Application Load Balancer`

---

💡 **Dica:** Esse mapa é excelente para visualizar como os serviços se conectam e se complementam dentro do universo de computação da AWS.
