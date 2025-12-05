
# Azure OpenAI no Playground

## Objetivo Geral
Aprender a utilizar o Azure OpenAI no Playground, incluindo configuração, pré-requisitos e integração com recursos do Azure.
- Deploy de recurso Azure OpenAI
- Funcionamento multimodal do Playground
- Configurações do Chat
- Integração com Blobs e informações

## Playground: O que é e para que serve?
O Playground do Azure OpenAI é uma interface interativa que permite testar, ajustar e experimentar modelos de IA de forma prática e visual. Nele, você pode criar prompts, configurar parâmetros, analisar respostas e integrar recursos multimodais, tudo em tempo real.

1. Desenvolvimento de Prompts
    - Permite criar e testar diferentes comandos (prompts) para os modelos de IA, observando como pequenas mudanças podem alterar as respostas.
    - Ideal para quem deseja aprimorar técnicas de prompt engineering, ajustando instruções para obter resultados mais precisos ou criativos.

2. Preparação e Ajuste do Modelo
    - Possibilita configurar o contexto inicial do modelo, definir mensagens do sistema (system messages) e exemplos (shots) para orientar o comportamento da IA.
    - Você pode simular cenários de zero-shot (sem exemplos) ou few-shot (com exemplos), ajustando o grau de instrução fornecido ao modelo.

3. Recursos disponíveis no Playground

## Conceitos Importantes
- Estocasticidade: como a aleatoriedade influencia as respostas
- Tokenização: como os textos são processados em tokens

## Parâmetros do Playground
Configuração de Parâmetros:
- Temperatura: Controla o grau de aleatoriedade das respostas. Valores baixos tornam as respostas mais previsíveis; valores altos aumentam a criatividade e diversidade.
- Top P: Define o percentual de palavras consideradas na geração da resposta, influenciando a variedade de resultados.
- Tokens Máximos: Limita o tamanho da resposta gerada, útil para evitar textos muito longos ou curtos demais.
- Penalidades: Ajusta a frequência e presença de palavras, evitando repetições ou incentivando novidades.
- Sistema de Mensagens: Permite definir instruções base e contexto para o modelo, tornando as respostas mais alinhadas ao objetivo do usuário.

## System Message e Shots
- Contexto inicial do modelo
- Definição de comportamento
- Zero-Shot e exemplos

## Criatividade e Diversidade nas Respostas
- Diferença entre Temperatura e Top-P
- Recomendações de uso

## Multimodalidade
O Playground suporta modelos capazes de gerar não apenas texto, mas também imagens (Dall-E), áudio e até interações com dados externos (blobs).
Você pode criar imagens a partir de descrições detalhadas, gerar áudio com base em texto e integrar dados para enriquecer o contexto das respostas.

## Integração com Blobs e Dados Externos
Permite conectar o Playground a fontes de dados externas, como Azure Blob Storage, para fornecer informações adicionais ao modelo.
Isso é útil para cenários onde o contexto precisa ser enriquecido com dados específicos do usuário ou da empresa.

## Hands On e Testes Práticos
- O Playground oferece ambiente para testes práticos, onde você pode experimentar diferentes configurações, documentar resultados e iterar com base em feedback.
- Ideal para validar hipóteses, prototipar soluções e aprender na prática como os modelos respondem a diferentes estímulos.

## Melhores Práticas
Recomenda-se começar com configurações padrão, ajustar um parâmetro por vez e documentar os resultados para facilitar o aprendizado e a evolução dos experimentos.
Iterar com base em feedback é fundamental para aprimorar a qualidade das respostas e adaptar o modelo às necessidades reais.

## Exemplos Práticos

### Exemplo 1: Deploy do Azure OpenAI
```bash
# No portal Azure, acesse "Criar recurso" e selecione "Azure OpenAI"
# Configure permissões de administrador e método de pagamento
# Realize o deploy e aguarde a disponibilidade do recurso
```

## Créditos
Conteúdo criado pelo Microsoft Copilot utilizando o material de apoio como referência e ajustado por Wglastonio.