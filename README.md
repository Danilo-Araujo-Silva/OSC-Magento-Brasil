Cuidado! Aten��o!!!
=================
Por motivo de seguran�a do seu projeto, recomendamos que se for usar esse m�dulo, que fa�a o download do mesmo diretamente no Github e n�o peguem arquivos distribuido na web por arquivos zipados! Lembre-se esse arquivos trabalha diretamente pagamentos e com dados sigilosos de seus clientes.
Dessa forma evita que pessoas mau intencionadas peguem o m�dulo que � FREE e coloquem scripts para hakear seu projeto!
Link para download em: https://github.com/deivisonarthur/OSC-Magento-Brasil/zipball/master

M�dulo OSC-Magento-Brasil - Normatiza��o do m�dulo para o padr�o brasileiro
=================
O projeto OCS-MAgento-Brasil � uma iniciativa para traduzir e adaptar o m�dulo free de OSC(One Step Checkout) para Magento chamado IWD OnePageCheckout.
O m�dulo ir� traduzir, adicionar estados, formatar, validar campos e adicionar novos campos.
Iremos tratar os principais campos, como: Rua, Bairro, Cidade, Estado, Cep com busca por Ajax com busca nos Correios, CPF/CNPJ, IE(Inscri��o Estadual), tipo pessoa, Telefone, Celular,...

Oque esse m�dulo ir� fazer?
=================
Com o m�dulo OSC-Magento-Brasil ir� se ter o meio mais famoso de checkout do Magento conhecido por OSC(One Step Checkout) e iremos fazer outros ajustes, como:

* Tradu��o dos Campos do formul�rio. (feito!)
* Inclus�o dos estados brasileiros. (feito!)
* Remodela��o do campo endere�o do magento de 4 linhas. Dividindo e formatando para Endere�o, N�mero, Bairro e Cidade. (feito!)
* Utiliza��o do campo taxvat por padr�o como campo de CPF/CNPJ. (feito!)
* Busca do endere�o por ajax direto do site dos Correios. (feito!)
* Formata��o dos campos por m�scara. Exe: Telefone com 9 ou 8 d�gitos (99) ?9999-9999. (feito!)

Para segunda etapa irei implementar outros campos, como:
* Inclus�o do campo tipo pessoa (F�sica ou Jur�dica)
* IE(Inscri��o Estadual) para gere��o da NFE
* Inclus�o do campo RG(Identidade)
* Inclus�o do campo Org�o Emissor do RG
* Op��o de desligar campos
* Como chegou a nossa loja virtual?

Tamb�m pretendo implementar op��es de seguran�a, como:
* Detec��o de utiliza��o de proxy com envio de email ao administrador
* Detec��o de compras suspeitas com envio de email ao administrador (Ir� verificar por Geolocaliza��o local onde foi feito a compra e bater com o local de entrega)
* Integra��o com o sistema de detec��o de fraude Maxmind (http://www.maxmind.com)
veja mais dicas sobre an�lise de risco e fraude no Magento em: http://www.deivison.com.br/blog/2012/07/25/modulo-de-analise-de-risco-e-fraude-no-magento-sem-mensalidade/

Desenvolvedores e mantenedores do projeto M�dulo OSC-Magento-Brasil:
=================
* Deivison Arthur Lemos Serpa
http://www.deivison.com.br
* Denis Colli Spalenza
http://www.xpdev.com.br

Vers�o BETA do projeto
=================
O m�dulo ainda encontra-se em fase de desenvolvimento! Ou seja, Ainda em est�gio Beta - v 1.0.0!

Pe�o por gentileza que n�o copiem o projeto e saem distribuindo zipado pela web! Porque isso?
=================
Por v�rios fatores!

1 - Pois fazendo dessa forma automaticamente estar� removendo os m�ritos dos desenvolvedores e respons�veis pelo projeto.
2 - Pegando o m�dulo diretamente no GITHUB, estar�o pegando o componente atualizado e certificado que iram pegar os fontes diretamente com os mantenedores do projeto.
3 - Dessa forma aumentaram a seguran�a dos seus projetos! Pois existem muitas pessoas mau intencionadas que pegam projetos open source, editam e colocam c�digos maliciosos para se infiltrar nos projetos. Por isso recomendamos pegarem m�dulos diretamente no GITHUB com os mantenedores do projeto!

Cr�ditos
=================
* Projeto base de OSC utilizado:
http://www.interiorwebdesign.com/magento/magento-one-step-checkout-module.html
* Script base para implementa��o da busca do CEP por Ajax:
http://www.pinceladasdaweb.com.br/blog/2012/01/31/webservice-consulta-de-cep-diretamente-ao-site-dos-correios/
* Tradu��es pt-BR do Magento:
http://www.cerebrum.com.br/index.php/magento-portugues-download-traducao-brasil-cielo-redecard-american-express.html