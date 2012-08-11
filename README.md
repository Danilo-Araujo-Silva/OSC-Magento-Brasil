M�dulo OSC-Magento-Brasil - Normatiza��o do m�dulo para o padr�o brasileiro
=================
O projeto OCS-MAgento-Brasil � uma iniciativa para traduzir e adaptar o m�dulo free de OSC(One Step Checkout) para Magento chamado IWD OnePageCheckout.
O m�dulo ir� traduzir, adicionar estados, formatar, validar campos e adicionar novos campos.
Iremos tratar os principais campos, como: Rua, Bairro, Cidade, Estado, Cep com busca por Ajax com busca nos Correios, CPF/CNPJ, IE(Inscri��o Estadual), tipo pessoa, Telefone, Celular,...

Oque esse m�dulo ir� fazer?
=================
Com o m�dulo OSC-Magento-Brasil ir� se ter o meio mais famoso de checkout do Magento conhecido por OSC(One Step Checkout) e iremos fazer outros ajustes, como:

* Tradu��o dos Campos do formul�rio
* Formata��o dos campos por m�scara. Exe: Telefone com 9 ou 8 d�gitos (99) ?9999-9999
* Inclus�o dos estados brasileiros
* Inclus�o do campo tipo pessoa (F�sica ou Jur�dica)
* Remodela��o do campo endere�o do magento de 4 linhas. Dividindo e formatando para Endere�o, N�mero, Bairro e Cidade.
* Utiliza��o do campo taxvat por padr�o como campo de CPF/CNPJ
* Inclus�o do campo IE(Inscri��o Estadual) para gere��o da NFE
* Busca do endere�o por ajax direto do site dos Correios
* Op��o de desligar campos

Para segunda etapa irei implementar outros campos, como:
* Como chegou a nossa loja virtual?
* RG(Identidade)
* Org�o Emissor do RG

Tamb�m pretendo implementar op��es de seguran�a, como:
* Detec��o de utiliza��o de proxy com envio de email ao administrador
* Detec��o de compras suspeitas com envio de email ao administrador (Ir� verificar por Geolocaliza��o local onde foi feito a compra e bater com o local de entrega)
* Integra��o com o sistema de detec��o de fraude Maxmind (http://www.maxmind.com)


Aten��o!!!
=================
O m�dulo ainda encontra-se em fase de desenvolvimento! Ou seja, ainda n�o funiona e foi colocado no Git para colabora��es de desenvolvedores ao projeto!

Cr�ditos
=================
Baseado no projeto:
http://www.interiorwebdesign.com/magento/magento-one-step-checkout-module.html