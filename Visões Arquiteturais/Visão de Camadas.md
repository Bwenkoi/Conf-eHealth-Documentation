## Visão de Camadas

![LayerView](https://github.com/Bwenkoi/Conf-eHealth-Documentation/assets/28735848/aa139f12-38d4-47d5-8d76-fc8aa1bc54e4)

Device-Gateway: Está é a camada responsável pela comunicação e adaptação dos dispositivos com o sistema de monitoramento. A camada em questão precisa se comunicar com diferentes dispositivos através de diferentes protocolos, ou seja, a camada deve permitir a interoperabilidade do sistema. Dessa forma, é responsabilidade dessa camada receber os comandos de configuração e atuação no padrão da aplicação, convertê-los nos padrões dos dispositivos alvos e transmiti-los pelos protocolos específicos dos dispositivos. Além de receber os dados em vários formatos e padronizar no formato único da aplicação.

Core Mgmt: É a camada "central" da arquitetura, responsável pelo gerenciamento das demais partes do sistema. Porém para especificar as responsabilidades internas, essa camada pode ser entendida pelo funcionamento em conjunto de três núcleos, são eles:

* Data-Context: Responsável pela comunicação com o banco de dados, armazenamento e disponibilização dos dados para consulta via API;
* Business/Flow Health: Responsável pela comunicação entre os outros componentes da camada, e também, pelas regras de negócio definidas para a construção do sistema no contexto;
* Context-Mgmt: Responsável pela transmissão de comandos de configuração e atuação da aplicação sobre os dispositivos entre as camadas Visualization/GUI e Device-Gateway.

Visualization/GUI: Esta camada é responsável pela apresentação dos dados para o usuário. O dados são consumidos pela camada através das APIs disponibilizadas pelo Data-Context, e apresentados para os usuários. Caso seja necessário alterações de contexto de aplicação, essa camada faz a comunicação com o Context-Mgmt, que reflete as alterações para o Device-Gateway.

Além das camadas, para a construção da arquitetura é preciso levar em consideração também as seguintes partes:
* Dispositivos (Devices): É imprescindível que os sensores presentes na rede de monitoramento sigam as especificações do Certificado de Boas Práticas de Fabricação (CBPF). Assim atributos de segurança e eficiência são garantidos pela norma.
* Autenticação (Auth): Todas as comunicações realizadas no sistema passam por autenticação para garantir a segurança do mesmo. A autenticação das partes é necessária tanto para garantia de conhecimento dos dispositivos quando dos usuários do sistema.
