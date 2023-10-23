# elvesQA-K6
# Testes de Carga com K6

Este repositório contém scripts e recursos relacionados ao uso do K6 para executar testes de carga e desempenho em suas aplicações web.

## Descrição

O [K6](https://k6.io/) é uma poderosa ferramenta de código aberto para testes de carga, permitindo que você avalie o desempenho de suas aplicações em escala. Este repositório foi criado para compartilhar scripts de teste e exemplos prontos para uso com o K6.

## Conteúdo

- *`/scripts`*: Este diretório contém scripts de teste escritos em JavaScript para o K6. Esses scripts podem ser usados para criar cenários de teste de carga personalizados.

- *`/config`*: Aqui você encontrará arquivos de configuração, como a definição de variáveis de ambiente, que podem ser usados nos scripts de teste.

## Uso

1. Instale o K6 em seu ambiente local, seguindo as instruções na [documentação oficial do K6](https://k6.io/docs/getting-started/installation).

2. Clone ou faça o download deste repositório.

3. Execute os testes de carga usando o K6. Por exemplo:
   ```bash
   k6 run scripts/seu_script.js
