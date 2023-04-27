# Bos Backend Event Module


Módulo que faz parte da arquitetura BOS (BierOnStack) e serve para adicionar coleções *(resources)* com códigos customizados para serem expostos via API Bos Backend. Quando se utilizam **coleções (resouces)**, o Bos automaticamente cria um DataStore para armazemaneto de dados e então expõe métodos para consumo de dados dessas coleções na geração automática das API`s. Entretando, quando se deseja expor um **endpoint** que irá processar algo, sem necessariamente haver persistência de dados, utiliza-se esse módulo.
Conheça o projeto BOS, sua framework para desenvolver softwares [BOS BierOnStack](https://github.com/eduardo-bier-bos/bos)


## Instalação


Todo projeto criado pelo BOS (BosApp), já tem com a referência para o Bos Backend Event Module instalado nativamente.


## Uso


Para usar recursos do Event Module, você deve acessar o dashboard do BOS e adicionar uma coleção do tipo **Event**. Após isso, selecionar a coleção e ir na opção **Event**. Será aberto um local **(On Get)** para que você insira seu código customizado, que será automaticamente exposto ao frontend e API.


## Autor

[Carlos Eduardo Bier](https://about.me/eduardo.bier.bos)

