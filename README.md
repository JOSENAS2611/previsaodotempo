Comentários e Explicações sobre o codigo
1.	Metadados e Bootstrap:
•	Os metadados e links para estilos são incluídos no <head>, com o Bootstrap carregado a partir de uma CDN para estilização rápida.
2.	Função getAddressByCep:
•	Busca o endereço correspondente ao CEP usando a API ViaCEP.
•	Verifica se houve erro na resposta da API e preenche os campos do formulário com os dados do endereço.
3.	Função getPrevisao:
•	Busca a previsão do tempo usando a API Open-Meteo.
•	Limpa o conteúdo anterior do elemento resposta.
•	Exibe os dados de previsão do tempo (máxima, mínima).
4.	Geolocalização:
•	A função getLocation verifica se a geolocalização é suportada pelo navegador e obtém a posição atual do usuário.
•	A função showPosition exibe as coordenadas obtidas nos campos de latitude e longitude.
5.	Chamar APIs:
•	A função chamarApis chama sequencialmente as funções para buscar o endereço pelo CEP e a previsão do tempo.
6.	Estrutura HTML:
•	O corpo da página contém seções bem definidas para o cabeçalho, formulário de entrada, resultados da pesquisa e rodapé.
•	O formulário permite a entrada de dados necessários para as consultas (CEP, latitude e longitude).
Modificações Realizadas
•	Exibição da Previsão dos proximos 7 dia inicio dia da consulta: O código foi modificado para exibir a previsão do tempo para os dias conta dia da  consulta, com dados de temperatura máxima e mínima.
•	Comentários Adicionais: Adicionei comentários ao longo do código para explicar o que cada parte está fazendo, facilitando a compreensão e manutenção do código.
Atualizações: Em 26 juho e 27 julho de 2024. Mudança do fundo da pagina.Colocado uma imagem de fundo e validação do inputs (obrigando o preenchimento para concluir a consulta).
