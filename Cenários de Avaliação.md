## Cenários de Avaliação

Os cenários de avaliação seguem o modelo detalhado a seguir:

* Estímulo: Representa uma ação ou evento que impacta no sistema;
* Fonte do Estímulo: Representa quem ou o que, de onde o estímulo se origina;
* Ambiente: Representa a condição ou estado do sistema ao receber o estímulo;
* Artefato: Representa a parte do sistema que é estimulada;
* Resposta: Representa a resposta do sistema ao estímulo;

### Cenário 01 - Disponibilidade

O primeiro cenário apresenta uma possível falha, queda ou atraso extenso na recuperação dos dados de monitoramento, com objetivo de entender se o sistema é capaz de garantir a disponibilidade das funções essenciais.

* Estímulo: Falha, queda ou atraso extenso no compartilhamento dos dados de monitoramento.
* Fonte: Dispositivos físicos de monitoramento e componentes de software relacionados.
* Artefato: Sistema de controle ou consulta, rede de monitoramento e canais de transmissão.
* Ambiente: Sistema em situação de falha.
* Resposta: Garantia e prevenção contra quedas. Detecção de falhas. Recuperação após falhas.

### Cenário 02 - Interoperabilidade

O segundo cenário está ligado à uma requisição de transferência de dados entre partes do sistema que possuem autorização para transferência.

* Estímulo: Transferência de dados entre dispositivos diversos e o sistema de monitoramento.
* Fonte: Comunicação entre diferentes partes que compõem o sistema.
* Artefato: Componentes do sistema que precisam interoperar.
* Ambiente: Sistema em seu funcionamento normal.
* Resposta: Uma requisição de transmissão de informação é devidamente aceita ou recusada independentemente do protocolo utilizado.

### Cenário 03 - Eficiência Energética

O terceiro cenário parte de uma avaliação de possíveis falhas em função da falta de bateria em um ou mais dispositivos que realizam o monitoramento de um paciente.

* Estímulo: Avaliação de vida útil dos dispositivos para implantação.
* Fonte: Entidades (cuidadores externos ou administrador do sistema), dispositivos físicos de monitoramento.
* Artefato: Ambiente de monitoramento do paciente.
* Ambiente: Sistema em seu funcionamento normal.
* Resposta: Capacidade de uso de dispositivos e protocolos eficientes energeticamente.

### Cenário 04 - Acurácia

O quarto cenário apresenta a tentativa de consulta aos dados do paciente monitorado por um cuidador externo autenticado.

* Estímulo: Consulta aos dados do paciente monitorado.
* Fonte: Entidade (cuidadores externos) e setores do sistema que interagem e armazenam os dados coletados.
* Artefato: Componentes de consulta e armazenamento de dados.
* Ambiente: Sistema em seu funcionamento normal.
* Resposta: Dados apresentados para o cuidador externo, de maneira precisa, de acordo com a coleta realizada.

### Cenário 05 - Segurança

O quinto cenário adotado se baseia na tentativa de acesso aos dados por um usuário, sistema ou parte do sistema sem autorização.

* Estímulo: Tentativa de acesso aos dados por um usuário ou sistema sem autorização.
* Fonte: Entidades, partes do sistemas ou sistemas externos que tentam acessar informações.
* Artefato: Setores do sistema que coletam, transmitem ou armazenam dados.
* Ambiente: Sistema em seu funcionamento normal.
* Resposta: Impedimento de acesso aos dados solicitados pela entidade sem autorização. Impedimento da alteração de dados.

### Cenário 06 - Latência

O sexto cenário leva em consideração um contexto onde um sinal de alerta é emitido quando um valor considerado perigoso for encontrado.

* Estímulo: Sinal de alerta emitido quando determinado um determinado dado ultrapassa o limite definido.
* Fonte: Setores do sistema que atuam sobre os dados coletados em tempo real.
* Artefato: Setores do sistema que se comunicam para transferência de dados coletados.
* Ambiente: Sistema em seu funcionamento normal.
* Resposta: Tempo de resposta do sistema em relação aos estímulos.
