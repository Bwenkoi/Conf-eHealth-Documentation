## Visão de Implantação

![ImpMacro](https://github.com/Bwenkoi/Conf-eHealth-Documentation/assets/28735848/a994934d-8987-40f5-8d69-911ef1383b3b)

Em uma arquitetura de micro-serviços, principalmente no cenário atual, o isolamento em contêineres se faz necessário. Porém, gerenciar de forma manual vários contêineres pode ser um inviável, dessa forma foi necessário escolher uma ferramenta para realizar a gerência dos microsserviços da aplicação. O Kubernetes permite gerenciar o \textit{deploy} de vários contêineres em um sistema e a manutenção dos mesmos. O Kubernetes também ajuda o sistema a cumprir alguns atributos de qualidade como a performance - já que permite replicar instâncias do mesmo micro-serviço de forma automática através do seu \textit{balance} interno - e a disponibilidade, se for operado em conjunto com uma plataforma de nuvem replicando instâncias a nível geográfico.

A visão de cada micro-serviço pode ser vista na Figura \ref{fig:ImpMicro} de maneira individual e o mesmo modelo será seguido para todos os outros.

![ImpMicro](https://github.com/Bwenkoi/Conf-eHealth-Documentation/assets/28735848/fabd7fd0-c58c-4d84-b125-77a0d6cf16c7)
