# 🎮 Jogo do Número Secreto com Reconhecimento de Voz

Este projeto é uma aplicação web interativa que utiliza reconhecimento de voz para permitir que o usuário tente adivinhar um número secreto gerado aleatoriamente. O projeto foca em acessibilidade, manipulação dinâmica do DOM e lógica de programação avançada.

## Tecnologias e Ferramentas

* **HTML5 & CSS3:** Estruturação semântica e estilização moderna com foco em responsividade.
* **JavaScript (ES6+):** Motor principal da aplicação.
* **Web Speech API:** Implementação de reconhecimento de voz nativo do navegador para interação do usuário.
* **Google Fonts:** Integração de tipografia externa para melhoria da UI/UX.

## Destaques Técnicos de Implementação

Ao analisar o código-fonte, destacam-se as seguintes competências técnicas:

1. **Recursividade e Manipulação de Arrays:** - Implementação de uma função recursiva para gerar números aleatórios, garantindo que o mesmo número não seja sorteado consecutivamente até que a lista de possibilidades se esgote.
   - Uso de `Array.includes()` e `Array.push()` para gerenciamento de estado dos números já sorteados.

2. **Integração com Web Speech API:**
   - Configuração de `SpeechRecognition` para captura de áudio em tempo real.
   - Tratamento de eventos de voz para converter fala em dados numéricos processáveis.

3. **Manipulação Avançada do DOM:**
   - Funções genéricas para alteração de conteúdo textual (`innerHTML`) e fala (`responsiveVoice`), promovendo a reutilização de código.
   - Controle dinâmico de atributos de elementos (como habilitar/desabilitar botões) baseado no fluxo do jogo.

4. **Template Literals:**
   - Uso de interpolação de strings para tornar as mensagens de feedback ao usuário dinâmicas e claras (ex: exibição do número de tentativas).

## Como Executar

1. Clone o repositório:
   ```bash
   git clone [https://github.com/thurr-vini/numero_secreto.git](https://github.com/thurr-vini/numero_secreto.git)
