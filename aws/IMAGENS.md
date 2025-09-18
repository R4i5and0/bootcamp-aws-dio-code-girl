
## Os Tipos de insTâNCIAS EC2 ✨
<img width="714" height="425" alt="image" src="https://github.com/user-attachments/assets/39eee973-a9c2-42c8-9fbe-34de4255ee77" />
<br>
<br>

### Explicação do Diagrama de Serviços de Computação da AWS  ✨
<img width="789" height="941" alt="image" src="https://github.com/user-attachments/assets/5a0389bb-6347-4457-bb67-6be8c16f9450" />

Esta imagem apresenta um mapa visual dos principais serviços e componentes que formam o ecossistema de **Computação (Compute)** da Amazon Web Services. Ela está organizada em grupos lógicos que representam diferentes áreas e funcionalidades:

#### 1. Amazon EC2 e seus Componentes (Canto Superior Esquerdo)
Este é o bloco central e mais detalhado, representando o serviço de máquinas virtuais da AWS e seus principais recursos:
* **Amazon EC2:** O serviço principal para criar servidores virtuais (instâncias).
* **AMI (Amazon Machine Image):** Os "moldes" ou templates usados para criar novas instâncias.
* **Instances:** Representa as máquinas virtuais em si, que podem ser de diversos tipos e tamanhos.
* **Auto Scaling:** A funcionalidade que adiciona ou remove instâncias automaticamente para atender à demanda.
* **Instance with CloudWatch:** Mostra a integração nativa com o serviço de monitoramento CloudWatch.
* **Spot Instance / Spot Fleet:** Modelos de preço de baixo custo que utilizam a capacidade ociosa da AWS.
* **Elastic IP address:** Endereços de IP estáticos que podem ser associados às suas instâncias.

#### 2. Serviços de Contêineres e Simplificados (Canto Superior Direito)
Este grupo foca em serviços para rodar aplicações em contêineres e uma opção simplificada de servidor virtual:
* **Amazon ECR (Elastic Container Registry):** Um serviço para armazenar, gerenciar e implantar imagens de contêiner (como o Docker). O ícone `ECR registry` representa o repositório onde as imagens ficam guardadas.
* **Amazon ECS (Elastic Container Service):** Um serviço para orquestrar e executar aplicações em contêineres. Os ícones `EC2 compute container` mostram que o ECS pode rodar esses contêineres em instâncias EC2.
* **Amazon Lightsail:** Uma plataforma simplificada que oferece pacotes fáceis de usar de servidores virtuais, armazenamento e rede, ideal para iniciantes ou projetos simples.

#### 3. Rede e Conectividade (Amazon VPC - Canto Inferior Esquerdo)
Este bloco mostra os componentes do **Amazon VPC (Virtual Private Cloud)**, que é a base de rede para os serviços de computação:
* **Amazon VPC:** O serviço que cria sua rede virtualmente isolada na nuvem.
* **Ícones de Rede:** Representam os componentes que permitem a conectividade, como `Internet Gateway` (para acesso à internet), `Router` (para direcionar o tráfego dentro da VPC), `VPN Gateway` (para conectar com sua rede local) e `VPC Peering` (para conectar diferentes VPCs).

#### 4. Outros Serviços de Computação e Balanceamento de Carga (Canto Inferior Direito)
Este grupo reúne outros modelos de computação e o serviço de distribuição de tráfego:
* **AWS Batch:** Um serviço para executar grandes volumes de trabalhos de processamento em lote.
* **AWS Elastic Beanstalk:** Um serviço de PaaS (Plataforma como Serviço) que facilita a implantação de aplicações, gerenciando a infraestrutura por você. Os ícones `Application` e `Deployment` representam esse processo.
* **AWS Lambda:** O principal serviço de computação sem servidor (Serverless), onde você executa código em resposta a eventos através de uma `Lambda function`.
* **Elastic Load Balancing:** Distribui o tráfego de entrada entre múltiplas instâncias EC2 para garantir alta disponibilidade e desempenho. Os ícones mostram os tipos `Classic Load Balancer` e `Application Load Balancer`.
