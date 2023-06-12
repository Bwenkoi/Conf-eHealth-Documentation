## Visão de Componentes

![service_model](https://github.com/Bwenkoi/Conf-eHealth-Documentation/assets/28735848/641a9bcb-f807-4898-86a8-307fc95eebac)

\textbf{Domain Entities:} Esse tipo de componente representa as entidades existentes dentro do domínio \textit{eHealth}, sendo que, em cada micro-serviço elas podem ser modeladas de uma forma diferente.

\textbf{Use Case:} Esse tipo de componente representa os casos de usos que serão colocados em cada micro-serviço.

\textbf{Producer Interface:} Utilizado para que seja possível um caso de uso produzir eventos para o restante da aplicação, deve-se elaborar uma interface que abstraia a escolha de tecnologia.

\textbf{Kafka Producer:} É responsável pelas publicações de mensagens no Apache Kafka. Dessa forma esse tipo componente deve implementar a \textit{Producer interface}. 

\textbf{Kafka Consumer:} É responsável por receber publicações de mensagens/eventos através do Apache Kafka e invocar os casos de uso referentes.

\textbf{HTTP API:} Recebe requisições HTTP em formato JSON. 

\textbf{Controller:} Esse tipo de componente sempre deve existir quando um micro-serviço possuir uma HTTP API. Esse componente deve implementa a interface HTTP API de forma que seja possível tratar as requisições recebidas e acionar os casos de usos referentes.

\textbf{Repository Interface:} Para que seja possível um caso de uso armazenar dados, deve-se elaborar uma interface que abstraia a escolha de tecnologia de armazenamento para cada entidade do sistema.

\textbf{Cloud Repository:} Implementação de um \textit{repository pattern} para armazenamento de dados na \textit{cloud}. Esse tipo componente deve implementar uma \textit{Repository Interface}, dessa forma cada entidade deve possuir um repositório próprio.

\textbf{Service invoker interface:} Para que seja possível um caso de uso se comunicar com outro micros-serviço será necessário implementar um interface para invocação. Essa comunicação pode ocorrer através de uma interface HTTP ou gRPC.

\textbf{Communicate interface:} Essa interface é necessária para que seja possível a invocação de outro micro-serviço de forma que o mesmo não se acople em uma tecnologia especifica de comunicação. É recomendado usar uma interface HTTP ou gRPC.

\textbf{Service invoker:} Esse tipo de componente deve implementar as interfaces \textit{Communicate interface} e a \textit{Service invoker interface} para comunica-se com outros microsserviços do sistema.
