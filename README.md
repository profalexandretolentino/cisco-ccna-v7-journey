# 🌐 Cisco CCNA v7 Journey | Jornada CCNA

**English:** This repository documents my progress through the Cisco CCNA v7 certification, focusing on "Introduction to Networks" (ITN). It includes lab notes, Packet Tracer files, and network automation scripts as part of my professional roadmap for 2027.  

**Português:** Este repositório documenta meu progresso na certificação Cisco CCNA v7, com foco em "Introdução a Redes" (ITN). Inclui notas de laboratório, arquivos do Packet Tracer e scripts de automação como parte do meu roadmap profissional para 2027.

---

## 🗺️ Study Roadmap | Roteiro de Estudos

**EN:** Organized following the official Cisco Networking Academy curriculum.  
**PT:** Organizado seguindo o currículo oficial da Cisco Networking Academy.

```mermaid
graph TD
    A[OSI & TCP/IP Models] --> B[Ethernet & Switching]
    B --> C[IPv4/IPv6 Addressing]
    C --> D[Subnetting & ICMP]
    D --> E[Basic Security & Config]
```

📂 Repository Structure | Estrutura do Repositório

    /labs: * EN: Cisco Packet Tracer (.pkt) files and topology images.

        PT: Arquivos do Packet Tracer e imagens de topologia.

    /notes: * EN: Summary of networking concepts and CLI commands.

        PT: Resumo de conceitos de rede e comandos CLI.

    /automation: * EN: Python scripts for network configuration and automation.

        PT: Scripts Python para configuração e automação de rede.

📚 Technical Summary: OSI Model | Resumo Técnico: Modelo OSI
```mermaid
graph TD
    subgraph OSI_MODEL [OSI Reference Model]
        direction TB
        L7[7. Application / Aplicação] --> L6[6. Presentation / Apresentação]
        L6 --> L5[5. Session / Sessão]
        L5 --> L4[4. Transport / Transporte]
        L4 --> L3[3. Network / Rede]
        L3 --> L2[2. Data Link / Enlace]
        L2 --> L1[1. Physical / Física]
    end

    %% Estilização para ficar Profissional
    style L7 fill:#ff1c1c,stroke:#fff,color:#fff
    style L4 fill:#00ff41,stroke:#000,color:#000
    style L1 fill:#2196f3,stroke:#fff,color:#fff
    style OSI_MODEL fill:#f4f4f4,stroke:#333,stroke-width:2px
```

    
🚀 Professional Goals | Objetivos Profissionais

    [ ] Complete Module 1: Introduction to Networks (ITN)

    [ ] Implement Network Automation scripts with Python

    [ ] Prepare for International IT Market (Japan 2027)
