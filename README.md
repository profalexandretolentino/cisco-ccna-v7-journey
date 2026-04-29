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
    subgraph Upper_Layers [Upper Layers: Host Integration]
        L7[7. Application / Aplicação] --- L6[6. Presentation / Apresentação]
        L6 --- L5[5. Session / Sessão]
    end

    subgraph Transport_Layer [Heart of OSI]
        L4[4. Transport / Transporte]
    end

    subgraph Lower_Layers [Lower Layers: Network Data Flow]
        L3[3. Network / Rede] --- L2[2. Data Link / Enlace]
        L2 --- L1[1. Physical / Física]
    end

    style Upper_Layers fill:#e1f5fe,stroke:#01579b
    style Transport_Layer fill:#fff9c4,stroke:#fbc02d
    style Lower_Layers fill:#f1f8e9,stroke:#33691e
    style L4 font-weight:bold
```

    
🚀 Professional Goals | Objetivos Profissionais

    [ ] Complete Module 1: Introduction to Networks (ITN)

    [ ] Implement Network Automation scripts with Python

    [ ] Prepare for International IT Market (Japan 2027)
