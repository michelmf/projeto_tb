# Informações sobre os dados

Este projeto utilizou o conjunto de dados de pacientes coletados na Policlínica Augusto Amaral Peixoto (Hoje Centro Municipal de Saúde Augusto Amaral Peixoto), localizada no bairro de Guadalupe, no Rio de Janeiro. As informações diponíveis durante a pesquisa correspondem a pacientes de ambos os sexos, com idade variando entre 2 e 96 anos, de diversas etnias (brancos, negros, mulatos, indígenas e asiáticos), residentes no estado do Rio de Janeiro e entrevistados em os anos de 2006 e 2009, todos com suspeita de tuberculose pulmonar.

A base é composta por 4381 exemplos descritos por 281 atributos, tais como: idade, sexo, peso, sintomas presentes, diagnóstico final sobre a doença, bem como datas de diversos exames realizados, os nomes dos enfermeiros encarregados de realizarem determinados procedimentos, entre muitas outras informações, como endereço dos pacientes e outras informações pessoais. Devido à restrições dos dados por causa da pesquisa, os mesmos não podem ser disponibilizados nesse repositório.

Dentre os 4381 exemplos presentes, 871 pacientes foram diagnosticados com tuberculose, 1856 pacientes diagnosticados como não possuindo a doença, e 1654 pacientes não tiveram conclusões sobre o desfecho da doença, seja por abandono de acompanhamento ou outros. Assim, trata-se de uma base com as classes desbalanceadas, onde 2727 exemplos possuem diagnósticos confirmados pelos profissionais envolvidos na pesquisa, dos quais aproximadamente 68% dos casos possuem desfecho negativo, e 32% dos casos sendo confirmados como positivo. Percebe-se que a quantidade de exemplos que possuem desfecho é de aproximidadamente o dobro daqueles diagnosticados como positivos.

## Resumo dos dados

* Quantidade de atributos: 281

* Quantidade de exemplos : 4381

    * Quantidade de pacientes confirmados com TB: 871

    * Quantidade de pacientes sem a doença: 1856

    * Casos inconclusivos: 1654