# Portfólio — Pedro Esquerdo

Portfólio técnico voltado ao estudo prático de **conceitos de engenharia de software e tecnologia**.

A proposta é usar projetos progressivos para entender não apenas como uma tecnologia funciona, mas por que ela existe, quais problemas resolve, quais limitações aparecem em implementações simples e como a arquitetura pode evoluir.

## Conceito

O portfólio funciona como um laboratório de estudos.

Cada projeto parte de uma implementação mínima e avança por etapas, registrando:

- conceito estudado;
- implementação inicial;
- limitações observadas;
- evolução da arquitetura;
- padrões e tecnologias relacionados.

## Projeto em destaque

### Carteiro — mensageria

O [Carteiro](https://github.com/pedroesquerdo/carteiro) é um projeto de estudo progressivo sobre envio de e-mails e mensageria.

Evolução atual:

1. envio simples via SMTP ✅
2. API HTTP com envio síncrono ✅
3. persistência de e-mails e status
4. processamento assíncrono
5. RabbitMQ: producer, queue e consumer
6. ACK/NACK e retry
7. Dead Letter Queue
8. idempotência
9. templates e anexos
10. observabilidade e padrões de produção

## Trilhas planejadas

- Mensageria e eventos
- Filas e processamento assíncrono
- Criptografia
- Blockchain e sistemas distribuídos
- Protocolos e redes
- Web scraping
- Observabilidade e resiliência
- Persistência e bancos de dados
- Integrações e APIs

## Tecnologias

O conjunto de tecnologias varia conforme cada experimento. Entre elas:

- .NET / C#
- ASP.NET Core
- Python
- SQL Server
- PostgreSQL
- SMTP
- RabbitMQ
- Docker
- Linux
- REST APIs
- GitHub Actions

## Site

O site é uma aplicação estática em HTML, CSS e JavaScript publicada pelo GitHub Pages.

Para executar localmente:

- clone o repositório;
- acesse a pasta `portifolio`;
- rode um servidor HTTP local, por exemplo `python -m http.server 8080`.

## Autor

**Pedro Esquerdo**  
GitHub: [@pedroesquerdo](https://github.com/pedroesquerdo)
