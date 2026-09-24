# D169T — Tradutor Universal de Jogos

**D169T** é um tradutor universal de jogos para Português Brasileiro. Roda no Android, suporta múltiplas engines, e usa a API DeepSeek para tradução de alta qualidade.

---

## 🎮 Engines Suportadas

| Engine | Status | Método |
|--------|--------|--------|
| **Ren'Py** | ✅ Consolidado | Runtime filter + `tl/<lang>/` |
| **RPG Maker MV/MZ** | ✅ Consolidado | `data/I18NTexts.json` + `plugins.js` |
| **RPG Maker VX/Ace** | ⚠️ Parcial | Marshal binário (`rubymarshal`) |

**Roadmap:**
- 🔜 **Godot Engine** (em desenvolvimento, sem previsão)

---

## ⚠️ Requisito Importante: Chave DeepSeek

**O D169T NÃO INCLUI uma chave DeepSeek.** Para usar, você precisa criar a sua (grátis).

### Como obter sua chave (passo a passo)

1. **Crie conta na DeepSeek Platform:**
   - Acesse: https://platform.deepseek.com/signup
   - Cadastre com e-mail ou Google

2. **Adicione crédito (mínimo $2):**
   - Vá em "Top up"
   - Aceita cartão internacional
   - $2 traduz ~50 jogos médios

3. **Gere sua API Key:**
   - Vá em "API Keys" → "Create new key"
   - Copie a chave (começa com `sk-...`)
   - **Guarde em local seguro** — só aparece uma vez

4. **Cole no D169T:**
   - Abra o app → Configurações
   - Cole a chave
   - Pronto!

### 💰 Quanto custa?

**Muito barato:**
- **Jogo médio (5.000 frases):** ~$0.02 (R$ 0.10)
- **Jogo grande (20.000 frases):** ~$0.08 (R$ 0.40)
- **$2 dura:** ~50-100 jogos traduzidos

**Off-peak (13:30-21:30 BRT):** 50% desconto!

---

## 🚀 Como usar

### 1. Baixe o APK

- Vá em [Releases](../../releases)
- Baixe o `D169T-vX.Y.Z.apk` mais recente
- Instale no Android

### 2. Configure a chave

- Abra o D169T
- Configurações → Cole sua chave DeepSeek
- Teste a conexão

### 3. Traduza!

- Toque em "+" → Adicione o jogo
- Selecione a pasta do jogo
- Toque em "Traduzir"
- Aguarde (barra de progresso em tempo real)

---

## 🛠️ Como funciona por dentro

### Pipeline
