# NIST - National Institute of Standarts and Technology

_U.S Department of Commerce_

```
The NIST Definition of Cloud Computing
Recommendations of the National Institute of Standards and Technology
Peter Mell
Timothy Grance
```

<hr>

## Exemplos de Nuvem:

    1. Azure Cloud
    2. AWS
    3. Google Cloud
    4. Alibaba Cloud
    5. Salesforce
    6. Dell
    7. IBM
    8. DigitalOcean
    9. Dropbox
    10. ...

## Definição de Cloud Computing
### On-demand self-service

    Oferecer provicionamento de recursos e gerenciamento sempre que necessario.

### Broad network access

    Acesso via rede liberado.

### Resource pooling

    Os recursos sevem a multiplos clientes com recusos provisórios e escalonaveis. Esses serviços podem ser escalonaveis para atender as necessidades de cada cliente, sem que nenhuma auteração seja aparente para o cliente ou usuário final.

### Rapid elasticity

    Os recursos devem escalonar rapidamente e em alguns casos automaticamente, podendo ser realocado ilimitadamente e a qualquer momento.

### Measured service

    O uso de recursos podem ser monitorados, controlado e relatado, fornecendo transparência tanto para o provedor como para o consumidor.

## Nuvem Pública, Privada e Híbrida
### Pública - Serviço externo
    Uma aplicação baseada na nuvem é totalmente implantada na nuvem e todos os aspectos da aplicação são executados nela. As aplicações na nuvem ou foram criadas nela ou foram migradas de uma infraestrutura prévia para usufruírem dos benefícios da computação em nuvem. As aplicações baseadas na nuvem podem se beneficiar de fragmentos secundários da infraestrutura ou podem utilizar serviços de nível superior que reduzem as necessidades de gerenciamento, arquitetura e escalabilidade da infraestrutura principal.

### Privada (On-premises) - Serviço local
    A implantação de recursos locais, usando ferramentas de gerenciamento de virtualização e recursos, às vezes é chamada de "nuvem privada". A implantação local não oferece muitos dos benefícios da computação em nuvem, mas, às vezes, é preferida por sua capacidade de oferecer recursos dedicados. Na maioria dos casos, este modelo de implantação é igual à infraestrutura de TI antiga, pois usa tecnologias de gerenciamento e virtualização de aplicações para tentar aumentar a utilização de recursos.

### Híbirda - União pública e privada
    Uma implantação híbrida é uma maneira de conectar infraestrutura e aplicações entre recursos da Web e recursos atuais que não se encontram na nuvem. O método mais comum de implantação híbrida é o que ocorre entre a nuvem e a infraestrutura local atual para estender e aumentar a infraestrutura de uma empresa na nuvem enquanto recursos da nuvem são conectados ao sistema interno. Para obter mais informações sobre como a AWS pode ajudar você com a sua implantação híbrida, acesse a nossa página híbrida.

## IaaS (Infraestrutura como Serviço)
### O que é?
A Infraestrutura como um serviço, às vezes abreviada como IaaS, contém os componentes básicos da TI em nuvem e, geralmente, dá acesso (virtual ou no hardware dedicado) a recursos de rede e computadores, como também espaço para o armazenamento de dados. A Infraestrutura como um serviço oferece a você o mais alto nível de flexibilidade e controle de gerenciamento sobre os seus recursos de TI e se assemelha bastante aos recursos de TI atuais com os quais muitos departamentos de TI e desenvolvedores estão familiarizados hoje em dia.

### Vantagens
* Escalabilidade: Os recursos podem ser escalonados conforme necessário.
* Redução de custos: Elimina a necessidade de manter hardware físico.
* Controle: Os usuários têm controle sobre o sistema operacional e configuração.
* Implementações rápidas: Implantações de servidores podem ser feitas em minutos.

### Desvantagens
* Gerenciamento: Os usuários são responsáveis pela manutenção do sistema operacional e configuração.
* Complexidade: Pode ser complexo para iniciantes configurar e gerenciar.
* Custos variáveis: Os custos podem aumentar com o uso excessivo.

## PaaS (Plataforma como Serviço)
### O que é?
Com a Plataforma como um serviço, as empresas não precisam mais gerenciar a infraestrutura subjacente (geralmente, hardware e sistemas operacionais), permitindo que você se concentre na implantação e no gerenciamento das suas aplicações. Isso o ajuda a tornar-se mais eficiente, pois elimina as suas preocupações com aquisição de recursos, planejamento de capacidade, manutenção de software, correção ou qualquer outro tipo de trabalho pesado semelhante envolvido na execução da sua aplicação.

### Vantagens
* Desenvolvimento simplificado: Os desenvolvedores podem se concentrar na criação de aplicativos, sem se preocupar com a infraestrutura subjacente.
* Escalabilidade automática: A plataforma pode dimensionar automaticamente os recursos conforme necessário.
* Integração fácil: Integra-se com outras ferramentas de desenvolvimento.
* Atualizações automáticas: Atualizações de sistema e segurança são tratadas pelo provedor.

### Desvantagens
* Menos controle: Os desenvolvedores têm menos controle sobre a infraestrutura.
* Bloqueado em uma plataforma: A escolha da plataforma pode limitar a portabilidade do aplicativo.
* Menos flexibilidade em comparação com IaaS.

## SaaS (Software como Serviço)
### O que é?
O Software como um serviço oferece um produto completo, executado e gerenciado pelo provedor de serviços. Na maioria dos casos, as pessoas que se referem ao Software como um serviço estão se referindo às aplicações de usuário final. Com uma oferta de SaaS, não é necessário em como o serviço é mantido ou como a infraestrutura subjacente é gerenciada, você só precisa pensar em como usará este tipo específico de software. Um exemplo comum de aplicação do SaaS é o webmail, no qual você pode enviar e receber e-mails sem precisar gerenciar recursos adicionais para o produto de e-mail ou manter os servidores e sistemas operacionais no qual o programa de e-mail está sendo executado.

### Vantagens
* Facilidade de uso: Não requer instalação ou configuração complexa.
* Atualizações automáticas: As atualizações de software são gerenciadas pelo provedor.
* Acessibilidade: Pode ser acessado de qualquer lugar com uma conexão à Internet.
* Custos previsíveis: Normalmente, segue um modelo de assinatura.

### Desvantagens
Personalização limitada: Pode não ser altamente personalizável.
Dependência do provedor: Os usuários dependem do provedor para disponibilidade e segurança.
Armazenamento de dados confidenciais: Pode gerar preocupações de segurança para dados sensíveis.

## FaaS (Função como Serviço)
### O que é?
FaaS, ou Função como Serviço, é um modelo de computação serverless em que os desenvolvedores podem executar funções específicas de forma independente em resposta a eventos, sem se preocupar com a infraestrutura subjacente.

### Vantagens
* Escalabilidade automática: As funções são dimensionadas automaticamente em resposta à carga.
* Custo baseado no uso: Os usuários pagam apenas pelo tempo de execução das funções.
* Baixa complexidade operacional: Sem gerenciamento de servidores ou infraestrutura.
* Alta disponibilidade: Geralmente oferece alta disponibilidade e tolerância a falhas.

### Desvantagens
* Limitado a funções pequenas: Não é adequado para aplicativos monolíticos.
* Pode ter latência de inicialização: A primeira execução de uma função pode ter latência de inicialização.

## DBaaS (Banco de Dados como Serviço)
### O que é?
DBaaS, ou Banco de Dados como Serviço, é um modelo em que os provedores de nuvem oferecem bancos de dados gerenciados aos usuários, eliminando a necessidade de configurar e manter servidores de banco de dados.

### Vantagens
* Gerenciamento simplificado: O provedor cuida de tarefas de gerenciamento, como backups e atualizações.
* Escalabilidade fácil: Os bancos de dados podem ser dimensionados conforme necessário.
* Alta disponibilidade: Geralmente oferece alta disponibilidade e replicação de dados.
* Segurança: O provedor geralmente implementa medidas de segurança robustas.

### Desvantagens
* Custos: Os custos podem aumentar à medida que o tamanho do banco de dados ou a demanda por recursos aumentam.
* Personalização limitada: Pode haver limitações na personalização do banco de dados.
* Bloqueado em um provedor: A escolha do provedor pode limitar a portabilidade dos dados.

## DaaS (Desktop como Serviço)
### O que é?
DaaS, ou Desktop como Serviço, permite que os usuários acessem desktops virtuais hospedados na nuvem, fornecendo ambientes de trabalho remotos.

### Vantagens
* Acesso remoto: Os desktops podem ser acessados de qualquer lugar com uma conexão à Internet.
* Gerenciamento centralizado: Facilita o gerenciamento de desktops e aplicativos.
* Segurança: Os dados são armazenados na nuvem, reduzindo o risco de perda de dados locais.
* Escalabilidade: Desktops podem ser adicionados ou removidos conforme necessário.

### Desvantagens
* Dependência de conexão à Internet: A qualidade da experiência depende da largura de banda e da conexão à Internet.
* Custos contínuos: Geralmente envolve uma taxa recorrente para o uso do serviço.
* Requisitos de desempenho: Alguns aplicativos podem não funcionar tão bem em desktops virtuais.

## Outros serviços de cloud
1. SECaaS (Segurança como Serviço), 
2. DRaaS (Recuperação de Desastres como Serviço), 
3. NaaS (Rede como Serviço), 
4. AIaaS (Inteligência Artificial como Serviço), 
5. STaaS (Armazenamento como Serviço), 
6. NaaS (Rede como Serviço), 
7. IoTaaS (Internet das Coisas como Serviço), 
8. Analytics as a service.
9. BaaS (Backend como Serviço)
10. CaaS (Contêiner como Serviço)

# References

[NIST]("https://nvlpubs.nist.gov/nistpubs/legacy/sp/nistspecialpublication800-145.pdf")
[AWS]("https://aws.amazon.com/pt/types-of-cloud-computing/")
[IBM]("https://www.ibm.com/topics/iaas-paas-saas?mhsrc=ibmsearch_a&mhq=Saas")
[Google Cloud]("https://cloud.google.com/learn/paas-vs-iaas-vs-saas?hl=pt-br")
