# ManutencaoRegistrosFIP
Implementação da rastreabilidade via Ficha de Identificação do Produto (FIP) para o setor automobilístico.

1	OBJETIVO DO DOCUMENTO

O propósito deste documento é descrever detalhadamente as informações técnicas utilizadas para a implementação do desenvolvimento no projeto <EMPRESA>. 


2	DESCRIÇÃO FUNCIONAL
O termo FIP – Ficha de Identificação do Produto representa a rastreabilidade do processo produtivo de produtos no setor automobilístico.

A solução abrangerá a criação de uma tabela de Registro FIP, uma tabela de Modelo FIP e tabelas auxiliares de nível simples. Além disso, para cada tabela, será disponibilizado um aplicativo para manutenção dos registros, bem como uma lista para exibição dos dados.

Após a criação, o registro FIP será vinculado ao “Número de Série” de um produto. Dessa forma, ao liberar uma ordem de montagem de um veículo, o campo “Número de Série” da ordem de produção receberá a associação a um registro FIP. Com isso, a rastreabilidade será aplicada por meio do vínculo entre o número FIP e a ordem de produção via número de série. Esse número será transferido para o estoque do produto e, posteriormente, vinculado à nota fiscal de venda.

A geração do código do registro FIP seguirá um algoritmo que utilizará tabelas internas e um controle sequencial de atributos.

O aplicativo de manutenção da FIP deverá incluir telas de consulta com informações relacionadas à ordem de venda vinculada ao registro FIP, bem como dados da ordem de produção associada.

Além disso, será desenvolvido um formulário básico para impressão de informações essenciais que poderão ser consultadas na fábrica. O formulário também deverá conter um espaço dedicado à coleta de dados para rastreabilidade.


![image](https://github.com/user-attachments/assets/eb638ecc-2d86-4a52-a437-46dc94b2dbdd)



O desenvolvimento da demanda terá início com a implementação das seis tabelas auxiliares, que serão utilizadas para manutenção de dados. Após a criação das tabelas conforme as especificações, serão desenvolvidos os respectivos aplicativos para manutenção dos registros.

Os aplicativos serão implementados utilizando a tecnologia Fiori Elements, seguindo o template padrão. Para isso, serão utilizadas CDS Views e seus respectivos modelos de objetos, garantindo a integração e consistência dos dados.

![image](https://github.com/user-attachments/assets/4fd19cb4-5064-4080-8468-67ad1d31ee1d)
