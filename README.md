# 1. Visão geral do projeto

O Sistema de Planejamento de Estudos com IA é uma aplicação feita em Python utilizando IA para gerar planos de estudo personalizados.

O usuário informa:

- tema de estudo;
- quantidade de horas por dia;
- prazo disponível;
- nível de conhecimento.

A IA gera:

- cronograma;
- tópicos;
- metas;
- sequência ideal de aprendizado.

A aplicação terá foco em:

- simplicidade;
- baixo custo;
- rapidez;
- aprendizado de integração com IA.

---

# 2. Objetivos do projeto

## 2.1 Objetivo principal

Criar um sistema capaz de gerar planos de estudo inteligentes utilizando a API do Gemini.

---

## 2.2 Objetivos secundários

- Aprender integração com IA;
- Trabalhar com prompts;
- Aprender persistência com SQLite;
- Criar uma aplicação utilizável;
- Construir projeto para portfólio.

---

# 3. System Design

## 3.1 Design

```
Usuário
   ↓
Interface Streamlit
   ↓
Gemini Service
   ↓
Gemini API
   ↓
SQLite

Usuário acessa aplicação
        ↓
Preenche formulário
        ↓
Clica em "Gerar plano"
        ↓
Prompt é criado
        ↓
Gemini gera plano
        ↓
Resposta é salva SQLite
        ↓
Plano exibido na tela
```
---

## 3.2 Estrutura de pastas do projeto

```
study-planner/
│
├── app.py       
├── database.db
├── requirements.txt
│
├── services/
│   ├── gemini_service.py
│   └── database_service.py
│
├── prompts/
│   └── planner_prompt.py
│
├── models/
│   └── study_plan.py
│
└── utils/
    └── formatter.py
```

---

# 4. Ferramentas Utilizadas

| Camada         | Tecnologia       |                                  
|------------------|----------------
| Back - end               | Python    
| Banco de Dados        | SQLite          
| Versionamento     | Git e GitHub        
| Front End   | HTML, CSS e JavaScript
| API  | Gemini

# 5. Benefícios do projeto

- Integração de sistema com IA
- Consumo de APIs
- Execução de engenharia de prompt

---
