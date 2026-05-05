# 💪 FitMeet — Treino Personalizado em Tempo Real

<div align="center">
  <img src="./preview/preview.png" alt="Interface FitMeet" width="900">
</div>

## 📝 Descrição do Projeto
O **FitMeet** é uma solução de videoconferência interativa desenvolvida para otimizar a experiência de treinos remotos. O projeto visa mitigar a fragmentação do ecossistema de treinamento online, onde usuários frequentemente alternam entre múltiplas aplicações para comunicação e monitoramento técnico.

### 🎯 O Problema que o FitMeet Resolve
Atualmente, a experiência de treino online é fragmentada: alunos dependem de softwares de terceiros para vídeo, cronômetros externos para controle de tempo e registros manuais para contagem de repetições. O FitMeet unifica essas camadas em uma **interface única**, integrando vídeo em alta definição com ferramentas de controle de performance em tempo real.

## 🚀 Tecnologias Utilizadas
A arquitetura do projeto foi construída sobre um stack focado em performance mobile e comunicação de baixa latência:

*   **Linguagem:** Kotlin
*   **Android SDK:** Nível 34
*   **Engine de Vídeo:** Jitsi Meet SDK 9.2.2 (via WebRTC)
*   **Interface (UI):** Material Design 3
*   **Estrutura de Dados:** ViewBinding para manipulação de layout
*   **Processamento:** Handler/Runnable para gerenciamento de threads de cronômetro
*   **Servidor de Sinalização:** meet.jit.si

## 🛠️ Funcionalidades Principais
*   **Módulo Lobby/Sala:** Sistema de gerenciamento de sessões para conexão segura entre instrutor e aluno.
*   **Monitoramento Integrado:** Cronômetro e contador de repetições sobrepostos à camada de vídeo.
*   **Comunicação HD:** Utilização de protocolos WebRTC para garantir estabilidade visual durante as séries.

---
**Desenvolvido como atividade prática por:** Gustavo Luan Araújo Santos.
*Projeto estruturado sob a metodologia "Made with Manus".*

[Voltar ao portfólio principal](https://github.com/gustavoluan-dot/portfolio-gustavo-luan-araujo-santos)
