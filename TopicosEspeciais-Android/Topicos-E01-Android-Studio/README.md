# Tópicos Android E01: Explorando IDE Studio

Professor: João Eduardo Montandon

**Objetivo: Explorar a IDE Visual Studio por meio da manutenção de um app já existente.**

## Clone do projeto

Neste curso, nós iremos utilizar o GitHub como ferramenta de disponibilização e entrega das atividades. 
Portanto, é necessário que você tenha feito o tutorial Git & GitHub primeiro. 
Consulte o professor em caso de dúvidas.

**IMPORTANTE: VOCÊ DEVERÁ REALIZAR UM COMMIT APÓS A IMPLEMENTAÇÃO DE CADA TAREFA**

## Identificando pendências

Ao fazer o clone e abrir o projeto no Android Studio, você irá observar que o projeto já possui alguns arquivos previamente editados, tais como `MainActivity.java` e `activity_main.xml`.
Ao abrir esses arquivos (`ctrl+shift+N` seguido do nome dos arquivos), você perceberá a presença de alguns comentários no formato *TODO alguma pendência para se fazer aqui*.
Quando existentes, esses comentários servirão para auxiliá-lo na resolução das tarefas de cada atividades.

Esses comentários também podem ser facilmente identificados no painel TODO, geralmente localizado na barra de paineis inferior da IDE.
Você também poderá acessar o painel de *TODO* utilizando `ctrl+shift+A` e selecionar a opção TODO.

**TL;DR: Visualize a lista de TODOs a serem implementados na atividade**

## Atualizando design da tela

Entre os TODOs existentes, dois estão relacionados a melhorias a serem feitas no design da tela do aplicativo:

1. Aumentar a fonte do texto da mensagem de boas vindas
1. Reposicionar o botão

Faça alterações no layout do aplicativo para que os componentes fiquem em conformidade com as especificações passadas no TODO, para isso, você precisará:

1. Customizar a propriedade `android:textSize` da mensagem de boas vindas
1. Definir as propriedades `android:layout_above` com o valor `@id/btn_ok` e `android:layout_centerHorizontal` com o valor `true`

**TL;DR: Atualize o design da tela conforme as informações disponibilizadas no TODO**
 

## Formatação do código

Agora que as pendências de layout foram resolvidas, vamos trabalhar nas pendências de código propriamente dito.
Porém, primeiramente, será preciso formatá-lo corretamente para que possa entendermos pelo menos o que se passa!

Utilize a ferramenta de auto-formatação do Android Studio para deixar o código minimamente legível.
Esse comando pode ser acessado diretamente por meio das teclas de atalho `ctrl+alt+I` e `ctrl+alt+L`.
Fique a vontade para fazer ajustes que julgar necessário.

**TL;DR: Utilize a ferramenta de auto-formatação para organizar o código do arquivo `MainActivity.java`**

## Monitoramento do app

Após identar e formatar corretamente seu código, você irá observar que ficou muito mais fácil de se entender onde e como as demais tarefas deverão ser implementadas.
Basicamente, lhe resta agora implementar os comandos de logging.
Esse recurso é muito interessante pois permite a você monitorar em detalhes o funcionamento do aplicativo.
Você pode, por exemplo:

1. Verificar por meio de logs quais métodos, estruturas, e fluxos o seu está executando, e em qual ordem
1. Observar o comportamento e a modificação de valores de determinadas variáveis
1. Monitorar o envio e repostas a chamadas de serviços externos do aplicativo (GPS, bluetooth, sensores, etc)

Você deverá implementar duas mensagens de logging conforme especificações presentes nos TODOs.
Após a implementação, execute o aplicativo e verifique no logcat como/quando essas mensagens são apresentadas.

**TL;DR: Implemente as mensagens de logging conforme descrito nos TODOs e observe seus registros no logcat durante a execução do app.**  