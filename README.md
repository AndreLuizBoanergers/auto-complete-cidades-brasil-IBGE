# 🔍 API de Busca de Cidades do Brasil

Uma API simples em Node.js + Express que fornece busca inteligente de cidades brasileiras com base em nome, UF, região ou outros filtros.

---

## ✅ Funcionalidades

- Busca por nome da cidade (`são`, `belo`)
- Busca por UF (`sp`, `rj`, `mg`)
- Busca por região (`regiao:sudeste`, `regiao:norte`)
- Retorna dados completos: IBGE, população, porte, estado
- Totalmente autônoma (usa JSON local)

---

## 📦 Dependências

- `express`: servidor web
- `fs`: leitura do arquivo JSON de cidades
- `path`: manipulação de caminhos de arquivos
- `fuse.js`
> Nenhuma dependência externa além do Node.js!

---

## 🚀 Como Usar

### 1. Clone ou crie o projeto

```bash
mkdir busca-cidades-api
cd busca-cidades-api
npm init -y
