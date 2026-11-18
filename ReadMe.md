# VR Text to Speech

## Descrição do projeto

O VR Text to Speech é um projeto de ferramenta de conversão de texto em fala (TTS) em um overlay para SteamVR, voltado ao uso no VRChat. A interface permitirá digitar mensagens em realidade virtual e reproduzir o áudio sintetizado por meio de um microfone virtual.

A síntese de voz utiliza o [Tiny Voca](https://github.com/n4ze3m/tiny-voca), um modelo leve com execução na CPU. A ferramenta implementa automações com OSC, protocolo utilizado pelo VRChat para comunicação com aplicações externas, e conta com correção de texto e um teclado personalizável com atalhos no próprio overlay.

## Ficha do projeto

### Domínio

O domínio do meu programa é híbrido: ele atua como uma camada embutida (overlay) sobre qualquer jogo no SteamVR, ocupando uma pequena janela visual no espaço 3D, mas dominando o canal de microfone virtual para projetar a voz dentro do mundo do jogo.

### Sentimento

O sentimento que ele busca gerar é o de pertencimento e agência social. Ele elimina o isolamento de quem não pode ou não quer usar a voz física, permitindo que o usuário sinta que realmente habita e participa daquela realidade.

### Teste da tela

Sobre o teste da tela, o programa não funcionaria em um monitor comum porque tirar o visor ou alternar janelas no desktop destruiria a imersão a cada frase. Estar no espaço 3D permite digitar usando a ergonomia natural das mãos e dos controles, mantendo a continuidade da presença virtual.

### Moldura

No meu programa, a moldura é o próprio overlay do SteamVR e a paisagem sonora onde a voz se insere: ele cria uma janela flutuante sobre o jogo ativo para receber o texto, mas rompe essa borda visual ao projetar o áudio diretamente no espaço 3D do ambiente virtual.

### Corpo

Já o corpo tem uma dupla função. Ele é o corpo físico do usuário, que usa as mãos ou os controles em VR para digitar e acionar a ferramenta, mas é principalmente um corpo protético e vocal: o programa empresta uma voz artificial e espacializada ao avatar do jogador, preenchendo a ausência da fala física e permitindo que ele marque presença e se comunique dentro da ilusão do mundo virtual.

### Risco

O risco aqui não é físico, mas perceptivo e social: com vozes cada vez mais naturais, o programa pode enganar os outros jogadores, fazendo-os acreditar que o áudio sintetizado é a voz biológica real do usuário, ao mesmo tempo em que corre o risco oposto de quebrar a ilusão se houver atraso na fala ou artificialidade excessiva.
