
# Resumo para a Certificação Datadog Fundamentals

Este documento resume os principais pontos a serem estudados para a certificação Datadog Fundamentals, com base no guia de estudos fornecido e informações complementares.

## 1. Fundamentos de Computação

É essencial ter um entendimento básico de como os sistemas de computação funcionam. Isso inclui:

*   **CPUs (Unidades Centrais de Processamento):** Compreender o papel da CPU no processamento de instruções e sua importância para o desempenho do sistema.
*   **RAM (Memória de Acesso Aleatório):** Entender como a RAM funciona como memória volátil para armazenamento temporário de dados e programas em execução.
*   **Armazenamento de Dados:** Conhecer os diferentes tipos de armazenamento (HDDs, SSDs) e suas características (velocidade, capacidade, persistência).
*   **Sistemas Operacionais (especialmente Linux):** Ter familiaridade com conceitos básicos de sistemas operacionais, com foco em Linux, que é amplamente utilizado em ambientes de infraestrutura.

## 2. Implantação de Infraestrutura com Datadog

Compreender como o Datadog se integra a diferentes ambientes é crucial:

*   **Servidores:** Como o Datadog Agent é instalado e configurado em servidores físicos ou virtuais.
*   **Containers:** A integração do Datadog com tecnologias de contêineres como Docker e Kubernetes para monitorar aplicações conteinerizadas.
*   **Nuvem:** Como o Datadog coleta dados de serviços em nuvem (AWS, Azure, GCP) através de integrações nativas.

## 3. Configuração de Rede e Datadog Agent

O Datadog Agent é o componente principal para coleta de dados. É importante saber:

*   **Coleta de Dados pelo Agent:** Como o Agent coleta métricas, logs e traces de diferentes fontes.
*   **Portas de Comunicação:** Quais portas o Agent utiliza para se comunicar com a plataforma Datadog e com os serviços que ele monitora.
*   **Resolução de Problemas de Conectividade:** Diagnosticar e resolver problemas de rede que impedem o Agent de enviar dados.

## 4. Coleta de Dados: Métricas, Logs e Traces

Estes são os três pilares da observabilidade no Datadog:

*   **Métricas:** Dados numéricos que representam o estado de um sistema ao longo do tempo (ex: uso de CPU, memória, tráfego de rede). Entender como são coletadas e agregadas.
*   **Logs:** Registros de eventos gerados por aplicações e sistemas. Saber como são coletados, parseados e pesquisados.
*   **Traces:** Representações de requisições de ponta a ponta através de sistemas distribuídos. Compreender como o APM (Application Performance Monitoring) do Datadog coleta e visualiza traces.

## 5. Solução de Problemas do Datadog Agent

Ser capaz de diagnosticar e resolver problemas comuns com o Agent é uma habilidade fundamental:

*   **Verificação de Status:** Como verificar o status do Agent e identificar problemas.
*   **Logs do Agent:** Onde encontrar e como analisar os logs do Agent para depuração.
*   **Problemas Comuns:** Falha na coleta de métricas, logs ou traces; problemas de conectividade; alto consumo de recursos pelo Agent.

## 6. Visualização e Utilização de Dados

Transformar dados brutos em insights acionáveis é o objetivo final:

*   **Dashboards:** Criação e personalização de dashboards para visualizar métricas, logs e traces de forma eficaz.
*   **Monitors:** Configuração de alertas e notificações com base em limites de métricas, padrões de logs ou anomalias.
*   **Notebooks:** Utilização de notebooks para análise exploratória de dados, colaboração e documentação de investigações.

## Como Estudar e Praticar

*   **Datadog Learning Center:** Utilize os cursos e trilhas de certificação oficiais.
*   **Documentação Oficial:** Consulte a documentação para detalhes técnicos e guias de configuração.
*   **Hands-on:** A prática é fundamental. Crie uma conta gratuita no Datadog, instale o Agent em um ambiente de teste (VM, Docker), crie dashboards e monitores.
*   **Tutoriais e Blogs:** Explore recursos de terceiros para guias passo a passo e dicas.
*   **Laboratórios Práticos e Desafios:** Crie seus próprios cenários e tente resolver problemas específicos para solidificar o conhecimento.
*   **Simulados:** Procure por simulados online para testar seus conhecimentos e identificar áreas que precisam de mais estudo.

