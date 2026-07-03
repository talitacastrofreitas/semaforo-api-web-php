# 🚦 Semáforo API

API simples desenvolvida em **PHP** para fornecimento de status de semáforo (verde, amarelo e vermelho), utilizada como base para sistemas de monitoramento e indicadores de status.

---

## 🎯 Objetivo

Disponibilizar uma API leve e rápida para retorno de status de sistema utilizando o conceito de semáforo:

- 🟢 Verde → Sistema funcionando normalmente  
- 🟡 Amarelo → Atenção / instabilidade  
- 🔴 Vermelho → Falha ou indisponibilidade  

---

## ⚙️ Tecnologias Utilizadas

- PHP  
- JSON  
- API REST (simples)  
- Apache (ou servidor PHP embutido)  

---

## 📡 Como funciona

A API responde requisições HTTP retornando o status atual do semáforo em formato JSON.

### Exemplo de resposta:

```json
{
  "status": "verde"
}
