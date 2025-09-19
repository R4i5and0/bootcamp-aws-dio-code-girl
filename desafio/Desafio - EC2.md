<img width="871" height="694" alt="image" src="https://github.com/user-attachments/assets/d00b94df-6319-4a53-937a-a83e0e7ca957" />
📊 [Clique aqui para visualizar o diagrama animado]file:///C:/Users/Raissa/Pictures/Diagrama%20de%20Organiza%C3%A7%C3%A3o.drawio.html

## Explicação do Fluxo do Sistema de Organização Pessoal 🎵📚

Este fluxograma foi criado para representar de forma clara e técnica a arquitetura de um sistema de organização pessoal dividido em dois módulos principais: **Biblioteca de Músicas** 🎵 e **Diário de Estudos** 📚. O objetivo é demonstrar como os serviços da AWS interagem para oferecer uma solução eficiente, escalável e organizada para o armazenamento, processamento e apresentação dos dados ao usuário.

### Fluxo Detalhado

- **👤 Interação do Usuário:**  
  O usuário acessa o sistema por meio de uma interface web hospedada no **Amazon EC2** 🖥️, que funciona como ponto central de interação.

- **📤 Envio de Arquivos:**  
  Através dessa interface, o usuário pode enviar diversos tipos de arquivos, como músicas 🎵, PDFs 📄 e imagens 🖼️, relacionados aos dois módulos do sistema, tanto para organizar seus estudos 📚 quanto para gerenciar sua biblioteca de músicas 🎶.

- **💾 Armazenamento Inicial:**  
  Os arquivos enviados são armazenados no **Amazon S3** ☁️, que oferece armazenamento seguro, escalável e durável para os dados brutos.

- **⚙️ Processamento Automático:**  
  O upload dos arquivos no S3 aciona automaticamente uma função no **AWS Lambda** 🔄, responsável por processar esses arquivos. Esse processamento inclui:
  - Extração de metadados das músicas 🎵.
  - Geração de resumos para documentos e imagens usados nos estudos 📚.
  - Organização dos arquivos conforme o módulo correspondente (Biblioteca de Músicas 🎵 ou Diário de Estudos 📚).

- **🗄️ Armazenamento Persistente dos Dados Processados:**  
  Os dados resultantes do processamento (metadados, resumos, organização) são armazenados no **Amazon EBS** 💽, que oferece armazenamento persistente e de alta performance para a instância EC2.

- **🔍 Consulta e Apresentação dos Dados:**  
  A interface web no EC2 consulta o Amazon EBS para recuperar e exibir as informações organizadas ao usuário, garantindo uma experiência integrada e eficiente.

---

Este fluxo foi cuidadosamente elaborado para ajudar o usuário a organizar tanto seus estudos 📚 quanto sua coleção de músicas 🎵, utilizando uma arquitetura robusta e escalável baseada nos serviços da AWS.
