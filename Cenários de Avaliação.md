## Cenários de Avaliação

Todos os cenários seguem o modelo detalhado a seguir:

* Estímulo: Representa uma ação ou evento que impacta no sistema;
* Fonte do Estímulo: Representa quem ou o que, de onde o estímulo se origina;
* Ambiente: Representa a condição ou estado do sistema ao receber o estímulo;
* Artefato: Representa a parte do sistema que é estimulada;
* Resposta: Representa a resposta do sistema ao estímulo;
* Medida da Resposta: Representa a maneira como a resposta é medida.

### Cenário 01 - Disponibilidade

O primeiro cenário apresenta uma possível falha, queda ou atraso extenso na recuperação dos dados de monitoramento, com objetivo de avaliar se o sistema é capaz de garantir a disponibilidade das funções essenciais.

* Estímulo: Falha, queda ou atraso extenso no compartilhamento dos dados de monitoramento.       
* Fonte: Entidades (paciente e cuidadores externos), dispositivos físicos e software.
* Artefato: Sistema de controle ou consulta, rede de monitoramento e canais de transmissão.
* Ambiente: Sistema em seu funcionamento normal.
* Resposta: Garantia e prevenção contra quedas. Detecção de falhas. Recuperação após falhas.
* Medida: O tempo de disponibilidade do sistema deve se manter acima de 99% do dia. Em caso de queda o tempo de detecção da falha e recuperação do monitoramento não deve exceder a 2 (dois) minutos.

### Cenário 02 - Interoperabilidade

O segundo cenário está ligado à uma requisição de transferência de dados entre partes do sistema que possuem autorização para transferência.

* Estímulo: Requisição de transferência de dados entre dispositivos.
* Fonte: Comunicação entre diferentes partes que compõem o sistema.
* Artefato: Componentes do sistema que desejam interoperar.
* Ambiente: Sistema em seu funcionamento normal.
* Resposta: Uma requisição de transmissão de informação é devidamente aceita ou recusada.
* Medida: A porcentagem de transmissões feitas corretamente deve se manter acima dos 95\%, enquanto a quantidade de transmissões rejeitadas não pode ultrapassar o valor de 5%.

### Cenário 03 - Eficiência

O terceiro cenário parte de uma possível falha em função da falta de bateria em um ou mais dispositivos que realizam o monitoramento de um paciente.

* Estímulo: Falha em função da falta de bateria em um ou mais dispositivos.
* Fonte: Dispositivos físicos de monitoramento.
* Artefato: Ambiente de monitoramento do paciente.
* Ambiente: Sistema em seu funcionamento normal.
* Resposta: Tempo de vida útil dos dispositivos antes de uma falha.
* Medida: O tempo de vida útil do ambiente de monitoramento deve ser maior que 30 (trinta) dias até a necessidade de troca dos dispositivos.

### Cenário 04 - Acurácia

O quarto cenário apresenta uma situação ocorrida a partir da tentativa de consulta aos dados do paciente monitorado por um cuidador externo.

* Estímulo: Setores do sistema que interagem e armazenam os dados coletados.    
* Fonte: Tentativa de consulta aos dados do paciente monitorado.
* Artefato: Componentes de consulta e armazenamento de dados.
* Ambiente: Sistema em seu funcionamento normal.
* Resposta: Quantidade de dados perdidos em um período de tempo determinado.
* Medida: O percentual de dados considerados corretos armazenados durante o monitoramento do paciente não deve ser menor que 99%.

### Cenário 05 - Segurança

O quinto cenário adotado se dá pela tentativa de acesso aos dados por um usuário ou parte do sistema sem autorização.

* Estímulo: Tentativa de acesso aos dados por um usuário ou sistema sem autorização.
* Fonte: Entidades, partes do sistemas ou sistemas externos que tentam acessar informações.
* Artefato: Setores do sistema que coletam, transmitem ou armazenam dados.
* Ambiente: Sistema em seu funcionamento normal.
* Resposta: Impedimento de acesso aos dados solicitados pela entidade sem autorização. Impedimento da alteração de dados.
* Medida: Quantidade de acessos barrados pelo sistema. Quantidade de dados afetados por uma tentativa de alteração.

### Cenário 06 - Latência

O sexto cenário parte da tentativa de consulta aos dados do paciente monitorado em tempo real ou sinal de alerta emitido caso um valor perigoso for encontrado.

* Estímulo: Tentativa de consulta aos dados do paciente monitorado em tempo real ou sinal de alerta emitido caso um valor perigoso for encontrado.
* Fonte: Setores do sistema que transmitem as informações coletadas em tempo real.
* Artefato: Setores do sistema que se comunicam para transferência de dados.
* Ambiente: Sistema em seu funcionamento normal.
* Resposta: Tempo de resposta do sistema em relação aos estímulos.
* Medida: O tempo de resposta ao consultar os dados do ambiente de monitoramento ou ao envio um sinal de alerta em caso do sistema detectar um valor perigoso não pode ser maior do que 2 (dois) segundos.
