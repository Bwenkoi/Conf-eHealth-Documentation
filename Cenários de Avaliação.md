## Cenários de Avaliação

Os cenários de avaliação seguem o modelo detalhado a seguir:

* Estímulo: Representa uma ação ou evento que impacta no sistema;
* Fonte do Estímulo: Representa quem ou o que, de onde o estímulo se origina;
* Ambiente: Representa a condição ou estado do sistema ao receber o estímulo;
* Artefato: Representa a parte do sistema que é estimulada;
* Resposta: Representa a resposta do sistema ao estímulo;

### Cenário 01 - Disponibilidade

O primeiro cenário apresenta uma possível falha, queda ou atraso extenso na recuperação dos dados de monitoramento, com objetivo de avaliar se o sistema é capaz de garantir a disponibilidade das funções essenciais.

* Estímulo: Falha, queda ou atraso extenso no compartilhamento dos dados de monitoramento.       
* Fonte: Entidades (paciente e cuidadores externos), dispositivos físicos e software.
* Artefato: Sistema de controle ou consulta, rede de monitoramento e canais de transmissão.
* Ambiente: Sistema em seu funcionamento normal.
* Resposta: Garantia e prevenção contra quedas. Detecção de falhas. Recuperação após falhas.

### Cenário 02 - Interoperabilidade

O segundo cenário está ligado à uma requisição de transferência de dados entre partes do sistema que possuem autorização para transferência.

* Estímulo: Requisição de transferência de dados entre dispositivos diversos e o sistema de monitoramento.
* Fonte: Comunicação entre diferentes partes que compõem o sistema.
* Artefato: Componentes do sistema que desejam interoperar.
* Ambiente: Sistema em seu funcionamento normal.
* Resposta: Uma requisição de transmissão de informação é devidamente aceita independentemente do protocolo utilizado.

### Cenário 03 - Eficiência

O terceiro cenário parte de uma possível falha em função da falta de bateria em um ou mais dispositivos que realizam o monitoramento de um paciente.

* Estímulo: Falha em função da falta de bateria em um ou mais dispositivos.
* Fonte: Dispositivos físicos de monitoramento.
* Artefato: Ambiente de monitoramento do paciente.
* Ambiente: Sistema em seu funcionamento normal.
* Resposta: Tempo de vida útil dos dispositivos antes de uma falha.

### Cenário 04 - Acurácia

O quarto cenário apresenta uma situação ocorrida a partir da tentativa de consulta aos dados do paciente monitorado por um cuidador externo.

* Estímulo: Setores do sistema que interagem e armazenam os dados coletados.    
* Fonte: Tentativa de consulta aos dados do paciente monitorado.
* Artefato: Componentes de consulta e armazenamento de dados.
* Ambiente: Sistema em seu funcionamento normal.
* Resposta: Dados apresentados para o cuidador externo, de maneira precisa.

### Cenário 05 - Segurança

O quinto cenário adotado se dá pela tentativa de acesso aos dados por um usuário ou parte do sistema sem autorização.

* Estímulo: Tentativa de acesso aos dados por um usuário ou sistema sem autorização.
* Fonte: Atores, partes do sistemas ou sistemas externos que tentam acessar informações sem autorização.
* Artefato: Setores do sistema que coletam, transmitem ou armazenam dados.
* Ambiente: Sistema em seu funcionamento normal.
* Resposta: Impedimento de acesso aos dados solicitados pela entidade sem autorização. Impedimento da alteração de dados.

### Cenário 06 - Latência

O sexto cenário considera um contexto onde um sinal de alerta é emitido quando um valor considerado perigoso for encontrado.

* Estímulo: Sinal de alerta emitido quando determinado dado ultrapassa o threshold definido.
* Fonte: Setores do sistema que atuam sobre as informações coletadas em tempo real.
* Artefato: Setores do sistema que se comunicam para transferência de dados.
* Ambiente: Sistema em seu funcionamento normal.
* Resposta: Tempo de resposta do sistema em relação aos estímulos.
