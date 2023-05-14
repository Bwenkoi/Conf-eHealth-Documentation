# Conf-eHealth-Documentation

Uma utilizacão importante e atual de aplicações IoT (Internet of Things) está presente na área da saúde. Em uma aplicação eHealth os dispositivos IoT são capazes de monitorar os pacientes em seu ambiente pessoal. Esses dispositivos fazem a transmissão das informações coletadas entre dispositivos e para um cuidador externo (médico, enfermeiro ou sistema automatizado). Entretando, existem difilculdades para garantir a confiabilidade dessa aplicações, uma vez as mesmas tratam de dados sensíveis e mesmo uma pequena falha pode significar perigos a saúde de um paciênte. 

Neste cenário, o objetivo desta documentação apresentar a Arquitetura de Referência (RA) para um sistema de saúde eHealth/Healthcare relacionado ao monitoramento remoto de um paciente e a tomada de decisão, podendo essa ter um caráter emergencial com alta confiablidade. Arqutetura foi nomeada como Conf-eHealth.

Uma Arquitetura de Referência define um conjunto de padrões e boas práticas que guiam a construção de arquiteturas futuras dentro do domínio de aplicação. Uma RA também pode ser desenvolvida para facilitar o entendimento e compartilhar valores entre vários produtos, organizações e disciplinas sobre as arquiteturas e direções futuras.

Esta Arquitetura de Referência tem como base a Confiabilidade. Porém, este é um termo amplo e que pode ser interpretado de diferentes maneiras. Neste caso a Confiabilidade será considerada como um conjunto de seis atributos, como pode ser visto na Figura a seguir.

![model-conf](https://github.com/Bwenkoi/Conf-eHealth-Documentation/assets/28735848/341647db-067e-4cd2-8fa3-b7b0f4cea24c)

Os atributos de qualidade apresentados são derivados das principais preocupações relacionadas a um sistema de monitoramento de saúde, são elas:

*Disponibilidade: O monitoramento de um paciente precisa ser ininterrupto independentemente da condição de saúde momentânea do mesmo. Neste contexto, uma notificação emergencial pode ser feita a qualquer momento através dessas aplicações, assim, a disponibilidade do sistema precisa ser garantida 24 horas por dia e 7 dias por semana.
*Interoperabilidade: Uma vez que diferentes sensores podem estar medindo diferentes atributos da saúde de um paciente e ao mesmo tempo, a interoperabilidade do sistema precisa ser garantida.
*Eficiência: Os sensores que monitoram os pacientes precisam ser eficientes, para garantir o monitoramento por um grande período de tempo sem necessidade de trocas de dispositivos em função do gasto energético dos dispositivos. 
*Acurácia: As aplicações \textit{web/mobile} precisam permitir decisões assertivas sobre a saúde do paciente. Assim, para garantir essa assertividade, a acurácia dos dados precisa ser garantida. Mesmo dados corretos podem levar a decisões erradas, se não forem claros e apresentados de maneira fiel à condição do paciente.
*Segurança: O servidor em nuvem armazena os dados provenientes do ambiente de monitoramento do paciente, e deve ser acessado pelas aplicações \textit{web/mobile} para consultas. Esse processo precisa garantir a segurança dos dados, pois os mesmos são sensíveis e pessoais a cada paciente. Além disso, a autenticação de usuários e dispositivos é essencial em todas as comunicações.
*Latência: A comunicação entre sensores e aplicações \textit{web/mobile} precisa acontecer em tempo real, ou seja, com baixa latência. Em aplicações que monitoram a respiração ou os batimentos cardíacos de um paciente, por exemplo, poucos segundos de atraso podem fazer diferença para salvar uma vida.

A representação visual dos requisitos de qualidade interagindo com a aplicação pode ser vista na Figura a seguir.

![Arquitetura-eHealth](https://github.com/Bwenkoi/Conf-eHealth-Documentation/assets/28735848/004bfced-b52d-4b68-885e-94482ff590e1)


