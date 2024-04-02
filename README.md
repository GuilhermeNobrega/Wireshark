<div align="center">

  # Wireshark

</div>

<div align=center>
  <img src='https://www.wireshark.org/docs/wsug_html_chunked/images/ws-main.png' height="200%" width="700" healt="wirewire">
</div>
<hr>
  
O **Wireshark** é uma poderosa ferramenta de análise de protocolo de rede e captura de pacotes. Ele permite que os usuários capturem e visualizem o tráfego de rede em tempo real e analisem dados capturados de forma detalhada. O Wireshark suporta uma ampla variedade de protocolos de rede e é uma ferramenta essencial para administradores de rede, engenheiros de segurança e profissionais de TI em geral.

## Principais recursos

- **Captura de pacotes**: O Wireshark permite capturar pacotes de dados em tempo real em uma rede, fornecendo uma visão detalhada do tráfego de rede.

- **Análise de pacotes**: Os usuários podem analisar pacotes capturados para entender o comportamento da rede, identificar problemas de desempenho e diagnosticar problemas de rede.

- **Suporte a vários protocolos**: O Wireshark suporta uma ampla variedade de protocolos de rede, incluindo TCP/IP, UDP, HTTP, DNS, SSH, SSL/TLS, e muitos outros.

- **Visualização detalhada**: Ele fornece uma interface gráfica intuitiva para visualizar detalhes de pacotes, incluindo cabeçalhos de protocolo, payloads, endereços IP, portas, e muito mais.

- **Filtragem avançada**: Os usuários podem aplicar filtros avançados para analisar pacotes específicos com base em critérios como endereço IP, porta, tipo de protocolo, tipo de conteúdo e muito mais.

## Como usar

1. **Instalação**: Baixe e instale o Wireshark a partir do [site oficial](https://www.wireshark.org/).

2. **Captura de pacotes**: Selecione a interface de rede desejada e inicie a captura de pacotes.

3. **Análise de pacotes**: Visualize os pacotes capturados na interface principal do Wireshark e analise os detalhes conforme necessário.

4. **Aplicação de filtros**: Aplique filtros para filtrar pacotes específicos com base em critérios de interesse.

5. **Análise detalhada**: Use recursos adicionais, como gráficos de fluxo, estatísticas de protocolo e decodificação de pacotes, para uma análise mais detalhada.

## Exemplos de uso

- Monitoramento de tráfego de rede em tempo real.
- Diagnóstico de problemas de desempenho de rede.
- Identificação de ataques de segurança e anomalias de rede.
- Depuração de aplicativos e serviços de rede.

## Interface

Veja uma breve explicação do funcionamento:

<div align=center>
  <img src='https://s2-techtudo.glbimg.com/Uo-MZ_zu_VPSNtLCL6oKxkqmeKg=/0x0:620x295/984x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_08fbf48bc0524877943fe86e43087e7a/internal_photos/bs/2021/5/G/en7VckSPimFhnvIqJoaA/2012-09-14-wire101.png' height="200%" width="700" healt="wirewire">
</div>

Em filter você pode usar diversos comandos para filtrar os pacotes que vagaram ou estão vagando na sua rede. Você	pode	clicar	duas	vezes	em	um	pacote	para	obter	mais	informações	sobre	ele.
<br>
<div align=center>
  
# Componentes:
  
</div>

<div align=center>
  <img src='https://github.com/GuilhermeNobrega/GuilhermeNobrega/blob/main/wiresss.PNG' height="200%" width="700" healt="wirewire">
</div>

- **Menus de Comando**:
  - Os menus de comando do Wireshark são menus suspensos padrão localizados na parte superior da janela. Os menus "File" e "Capture" são os mais importantes para iniciantes:
    - **File**: Permite salvar dados de pacotes capturados ou abrir um arquivo contendo dados de pacotes capturados anteriormente, além de sair do aplicativo Wireshark.
    - **Capture**: Permite começar a captura de pacotes.

- **Janela de Listagem de Pacotes**:
  - Esta janela exibe um resumo de uma linha para cada pacote capturado, incluindo o número do pacote, o momento da captura, endereços de origem e destino, tipo de protocolo e informações específicas do protocolo contido no pacote. A lista de pacotes pode ser classificada de acordo com qualquer uma dessas categorias, clicando sobre o nome da coluna.

- **Janela de Detalhes do Cabeçalho do Pacote**:
  - Fornece detalhes sobre o pacote selecionado na janela de listagem de pacotes. Você pode selecionar um pacote clicando sobre o resumo de uma linha do pacote na janela de listagem de pacotes.

- **Janela de Conteúdo dos Pacotes**:
  - Exibe todo o conteúdo do quadro capturado, em ASCII e formato hexadecimal.

- **Campo de Filtragem de Pacotes**:
  - Na parte superior da interface gráfica do Wireshark, está o campo de filtragem para exibição de pacotes, onde um nome de protocolo ou outras informações podem ser inseridos para filtrar as informações exibidas na janela de listagem de pacotes.
