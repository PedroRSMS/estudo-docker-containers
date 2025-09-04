# Estudo Docker - Containers

## Sobre
Este repositório documenta meu aprendizado sobre Docker e containerização.

**Autor:** Pedro Rafael Sá Martins da Silva
**Curso:** Tecnico de Segurança cibernética
**Disciplina:** Banco de dados
**Data:** 02/09/2025

## O que estou aprendendo
- Conceitos fundamentais do Docker
- Como criar e gerenciar containers
- Trabalhar com imagens Docker
- Configurar bancos de dados em containers
- Usar Docker Compose para aplicações multi-container

## Estrutura do Projeto
- `containers/` - Dockerfiles e configurações de containers
- `compose/` - Arquivos docker-compose.yml
- `scripts/` - Scripts de configuração e inicialização
- `README.md` - Este arquivo de documentação

## Status do Estudo
- [X] Tarefa 1 - Primeiro container
- [X] Tarefa 2 - Container personalizado
- [X] Tarefa 3 - Banco de dados
- [X] Tarefa 4 - Docker Compose
- [X] Tarefa 5 - Aplicação completa

##  Reflexão Final
1. Qual a principal vantagem de usar containers com Docker em vez de instalar diretamente?
Docker isola aplicações em ambientes independentes, evitando conflitos e facilitando a portabilidade. Não é preciso instalar e configurar manualmente no sistema, garantindo que funcione igual em qualquer máquina.

2. Qual o propósito de um Dockerfile e sua importância?
O Dockerfile define passo a passo a construção da imagem do container, garantindo que o ambiente seja reproduzido exatamente igual em qualquer lugar, assegurando consistência e reprodutibilidade.

3. Quando o Docker Compose é essencial? Por que não usar só docker run?
Docker Compose é essencial para orquestrar múltiplos containers que trabalham juntos, simplificando a execução e configuração. Usar vários docker run manualmente é mais complexo e propenso a erros.

4. Importância dos volumes do Docker. O que acontece se não usarmos?
Volumes persistem dados fora do container. Sem eles, ao remover o container, todos os dados (como do banco de dados) seriam perdidos.

5. Como containers facilitam o trabalho em equipe?
Containers garantem que todos usem o mesmo ambiente, facilitando a configuração, evitando erros de ambiente e acelerando o desenvolvimento colaborativo.