# lia-coach-mvp

MVP Beta Operacional

# LIA Coach - AI-Powered Leadership Platform

![Status: MVP Beta Operacional](https://img.shields.io/badge/Status-Beta_Operacional-green)
![Platform: Cloud-Native](https://img.shields.io/badge/Platform-Cloud--Native-blue)

O **LIA Coach** é uma plataforma SaaS de mentoria em liderança que utiliza IA generativa para democratizar o desenvolvimento executivo. O projeto foca em escalabilidade tecnológica e acessibilidade total (WCAG compliance), com impacto social direto em parceria com o **Instituto Luiz Braille (ILBES)**.

## 🚀 Stack Tecnológica Atual
- **LLM Engine:** Google Gemini API (Flash 2.0).
- **Orquestração:** n8n (Self-hosted workflows para automação de processos).
- **Banco de Dados:** Supabase (PostgreSQL com Row Level Security).
- **Interface:** Google Apps Script + Landing Page Responsiva.

## 🏗️ Arquitetura do Sistema
O sistema opera em um modelo de micro-serviços orquestrados:
1. **Trigger:** Webhook recebido via Forms/Web Interface.
2. **Processamento:** n8n valida créditos e status no Supabase.
3. **Inteligência:** Gemini API processa o contexto do usuário e gera mentoria personalizada.
4. **Output:** Entrega multicanal com persistência de log para análise de métricas.

## 📈 Roadmap de Cloud (Google Cloud Program)
Este repositório serve como base para a migração planejada para a infraestrutura Google Cloud:
- [ ] Migração de chamadas API diretas para **Vertex AI**.
- [ ] Implementação de **Cloud Run** para hospedagem da orquestração.
- [ ] Integração com **BigQuery** para analytics preditivo de aprendizado.

---
**Founder:** Ivan Arenque Passos | **Empresa:** MKTPASSOS (CNPJ: 43.982.223/0001-04).
