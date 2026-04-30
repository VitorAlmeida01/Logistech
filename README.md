<h1>
    <img align="center" width="80px" src="https://avatars.githubusercontent.com/u/180440007?v=4" img width="80" alt="{a} logo" class="img-fluid"></a>
    <span>LOGISTECH Soluções Tecnológicas</span>
</h1>

Nosso grupo foi formado para atender as soluções de tecnologia das empresas onde a linha de produção apresenta problemas de retrabalho, desvio indevido de material e necessidade de melhorias no processo.

## Sobre o Projeto

O **Logistech** é uma plataforma B2B de monitoramento de linhas de produção industrial. O sistema integra sensores físicos (via Arduino) às esteiras de produção das empresas clientes, coletando leituras de distância em tempo real para identificar produtos viáveis e não viáveis durante o processo produtivo.

### Principais funcionalidades

- **Monitoramento de esteiras:** cada esteira possui sensores que registram a distância dos produtos e verificam se estão dentro do padrão esperado.
- **Alertas automáticos:** quando a distância registrada por um sensor difere do valor esperado da esteira, um alerta é gerado automaticamente via trigger no banco de dados.
- **Métricas configuráveis:** cada esteira possui faixas de métricas (Crítico, Atenção, Esperado, Ideal) com cores e intervalos personalizáveis.
- **Gestão de empresas e usuários:** suporte a múltiplas empresas com controle de usuários e endereços vinculados.
- **BobIA:** assistente de inteligência artificial integrado, alimentado pelo Google Gemini, para suporte e consultas sobre o sistema.
- **API Arduino:** módulo dedicado à comunicação com os dispositivos físicos Arduino instalados nas esteiras.

### Arquitetura

A aplicação é uma API REST desenvolvida em **Node.js** com **Express**, conectada a um banco de dados **MySQL**. O backend expõe endpoints para gerenciamento de empresas, usuários, endereços, esteiras, sensores, registros, alertas, métricas e integração com IA.

## Colaboradores
- Vinicius Oliveira Pedroso
- Israel Coaquira Jumpiri
- Gabriel Yuri Iwakura
- Vitor da Silva Almeida
- Matteo Garcia Rizzo

## Parceiros Tecnológicos
- <a href="https://www.sptech.school/">
      <img align="center" width="65px" src="https://moodle.sptech.school/pluginfile.php/1/core_admin/logo/0x150/1692971033/sptech_principal_ciano.png" alt="{a} logo" class="img-fluid"></a> https://www.sptech.school/

## Ferramentas
![Git](https://img.shields.io/badge/Git-000?style=for-the-badge&logo=git)
![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github)
![HTML5](https://img.shields.io/badge/HTML-000?style=for-the-badge&logo=html5)
![CSS3](https://img.shields.io/badge/CSS-000?style=for-the-badge&logo=css3&logoColor=30A3DC)
![SQL](https://img.shields.io/badge/sql-000?style=for-the-badge&logo=mysql)
![JavaScript](https://img.shields.io/badge/JavaScript-000?style=for-the-badge&logo=javascript)
![Trello](https://img.shields.io/badge/trello-000?style=for-the-badge&logo=trello&logoColor=30A3DC)
