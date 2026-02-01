# 🤖 Guia: Como Configurar a API do Google Gemini

## Para ativar as funcionalidades de IA no EspiriQuiz

---

## 🎯 O QUE A IA FAZ

### 3 Funcionalidades Poderosas:

1. **✨ Mensagem de Luz Diária**
   - Reflexão espiritual para começar o dia
   - Baseada nos princípios espíritas
   - Nova mensagem a cada 24 horas
   - Reconfortante e motivadora

2. **🧠 Dica do Mentor (Método Socrático)**
   - IA não dá a resposta direta
   - Faz perguntas que guiam o raciocínio
   - Usa analogias da doutrina espírita
   - Estimula reflexão profunda

3. **📚 Aprofundamento Doutrinário**
   - Explicação filosófica da resposta
   - Base científica (época de Kardec)
   - Relação com outros princípios
   - Linguagem acessível e profunda

---

## 🔑 PASSO 1: Obter Chave API (5 minutos)

### 1.1 Acesse o Google AI Studio

```
https://makersuite.google.com/app/apikey
```

**Ou pesquise no Google:** "Google AI Studio API Key"

### 1.2 Faça Login

- Use sua conta Google
- Qualquer conta serve (Gmail, Google Workspace, etc)

### 1.3 Crie um Projeto (se necessário)

1. Clique em **"Create API key"**
2. Se pedir, crie um novo projeto ou selecione um existente
3. Nome sugerido: **"EspiriQuiz"**

### 1.4 Gere a Chave

1. Clique em **"Create API key in new project"** (ou existente)
2. Aguarde alguns segundos
3. Sua chave aparecerá (algo como: `AIzaSyA...`)

### 1.5 Copie a Chave

1. Clique em **"Copy"** ou copie manualmente
2. **IMPORTANTE:** Guarde em local seguro!
3. Você só verá esta chave uma vez

---

## 🛠️ PASSO 2: Adicionar Chave ao Código

### 2.1 Abra o arquivo `index.html`

Use qualquer editor de texto:
- Notepad (Windows)
- TextEdit (Mac)
- VS Code, Sublime, Notepad++ (avançado)

### 2.2 Encontre a Linha

Procure por (Ctrl+F ou Cmd+F):

```javascript
const GEMINI_API_KEY = 'SUA_CHAVE_API_AQUI'
```

Está aproximadamente na **linha 260**

### 2.3 Substitua

**ANTES:**
```javascript
const GEMINI_API_KEY = 'SUA_CHAVE_API_AQUI'
```

**DEPOIS:**
```javascript
const GEMINI_API_KEY = 'AIzaSyA...' // Cole sua chave aqui
```

**Exemplo real:**
```javascript
const GEMINI_API_KEY = 'AIzaSyBxxxxxxxxxxxxxxxxxxxxxxxxxxxxx'
```

### 2.4 Salve o Arquivo

- Ctrl+S (Windows)
- Cmd+S (Mac)

---

## ✅ PASSO 3: Testar

### 3.1 Abra o jogo

- Dê duplo clique em `index.html`
- Ou hospede no GitHub Pages

### 3.2 Teste as Funcionalidades

**No Menu Principal:**
1. Clique em **"✨ Receber Mensagem de Luz"**
2. Aguarde 3-5 segundos
3. Deve aparecer uma reflexão espiritual

**Durante o Jogo:**
1. Clique em **"🧠 Pedir Dica do Mentor"**
2. Aguarde a dica socrática
3. Após acertar, clique em **"📚 Aprofundamento Doutrinário"**

### 3.3 Sucesso!

Se funcionou, você verá:
- ✅ Textos gerados pela IA
- ✅ Linguagem natural e fluente
- ✅ Conteúdo relacionado ao Espiritismo

---

## 🐛 SOLUÇÃO DE PROBLEMAS

### ❌ Erro: "Configure sua chave API"

**Causa:** Chave não foi substituída corretamente

**Solução:**
1. Verifique se removeu `SUA_CHAVE_API_AQUI`
2. Certifique-se que a chave está entre aspas `'...'`
3. Salve o arquivo novamente

### ❌ Erro: "Erro ao conectar com a IA"

**Causa:** Chave inválida ou problema de conexão

**Soluções:**
1. **Verifique a chave:**
   - Acesse https://makersuite.google.com/app/apikey
   - Confirme que a chave está ativa
   - Gere nova chave se necessário

2. **Verifique conexão:**
   - Teste sua internet
   - Tente em outro navegador
   - Desative VPN se estiver usando

3. **Verifique cota:**
   - API Gemini tem limite gratuito
   - 60 requisições por minuto
   - 1500 por dia (grátis)

### ❌ IA retorna respostas genéricas

**Causa:** Normal no início

**Solução:**
- As primeiras respostas podem ser genéricas
- A IA aprende com o contexto
- Continue usando para respostas melhores

### ❌ IA demora muito (>30 segundos)

**Causa:** Servidor sobrecarregado

**Soluções:**
1. Aguarde e tente novamente
2. Reduza tamanho das perguntas
3. Verifique sua internet

---

## 💰 CUSTOS E LIMITES

### Plano Gratuito (Free Tier)

✅ **O que está incluído:**
- 60 requisições por minuto
- 1.500 requisições por dia
- 1 milhão de tokens por mês
- **Totalmente gratuito!**

✅ **Suficiente para:**
- Centenas de jogadores por dia
- Milhares de perguntas com IA
- Uso pessoal e pequenos grupos

### Quando Paga?

- Apenas se ultrapassar limites gratuitos
- Improvável para uso normal
- Pode configurar alertas de cota

### Como Monitorar Uso

1. Acesse: https://console.cloud.google.com
2. Vá em **"APIs & Services"** → **"Dashboard"**
3. Veja uso em tempo real

---

## 🔒 SEGURANÇA DA CHAVE

### ⚠️ IMPORTANTE

**NUNCA compartilhe sua chave API publicamente!**

### ❌ NÃO FAÇA:

- ❌ Postar no GitHub público
- ❌ Compartilhar em fóruns
- ❌ Enviar por WhatsApp/Telegram
- ❌ Deixar em código fonte público

### ✅ FAÇA:

- ✅ Use apenas em código privado
- ✅ Revogue se expor acidentalmente
- ✅ Crie nova chave periodicamente
- ✅ Use variáveis de ambiente (avançado)

### Se Expôs a Chave:

1. Acesse https://makersuite.google.com/app/apikey
2. Clique nos **3 pontinhos** ao lado da chave
3. Selecione **"Delete"**
4. Crie nova chave

---

## 🌐 HOSPEDAGEM NO GITHUB PAGES

### Problema: Chave Visível

Quando você hospeda no GitHub Pages, o código fica público, incluindo sua chave API.

### Soluções:

#### Solução 1: Repositório Privado (Recomendado)

1. No GitHub, marque repositório como **Private**
2. GitHub Pages funciona mesmo em repo privado
3. Código não fica visível publicamente

**Como fazer:**
1. Settings → Danger Zone → Change visibility
2. Marque Private
3. Confirme

#### Solução 2: Backend Simples

Use um serviço como **Netlify Functions** ou **Vercel Serverless**:

```javascript
// Chame sua função ao invés da API direta
const response = await fetch('/.netlify/functions/gemini', {
  method: 'POST',
  body: JSON.stringify({ prompt })
})
```

A chave fica no servidor, não no código.

#### Solução 3: Compartilhar sem IA

- Remova a chave antes de publicar
- IA não funcionará para outros
- Você usa versão local com IA

---

## 📊 OTIMIZAÇÃO DE CUSTOS

### Dicas para Economizar:

1. **Cache de Respostas**
   - Mensagem diária salva por 24h
   - Não gera novamente no mesmo dia

2. **Limitar Requisições**
   - Desabilite temporariamente se atingir limite
   - Reative no dia seguinte

3. **Respostas Concisas**
   - Prompts bem escritos = respostas menores
   - Menos tokens usados

---

## 🎓 ENTENDENDO OS PROMPTS

### O que são Prompts?

Instruções que você dá para a IA. No código, há 3 prompts principais:

#### 1. Mensagem Diária
```javascript
"Gere uma reflexão espiritual inspiradora..."
```

#### 2. Dica do Mentor
```javascript
"Forneça uma dica que NÃO revele a resposta..."
```

#### 3. Aprofundamento
```javascript
"Explique a BASE FILOSÓFICA desta resposta..."
```

### Personalizando Prompts

Você pode editar os prompts no código para:
- Mudar tom (mais formal/informal)
- Ajustar tamanho das respostas
- Focar em aspectos específicos

**Localização:** Funções `generateDailyMessage()`, `generateMentorTip()`, `generateDeepDive()`

---

## 🔄 ATUALIZAÇÕES DA API

### Google AI Studio evolui constantemente

**Fique atento:**
- Novos modelos (Gemini 1.5, 2.0, etc)
- Mudanças nos limites
- Novas funcionalidades

**Como atualizar:**
1. Visite https://ai.google.dev/docs
2. Veja changelog
3. Adapte código se necessário

---

## 💡 RECURSOS ADICIONAIS

### Documentação Oficial:
- https://ai.google.dev/docs
- https://ai.google.dev/tutorials

### Exemplos de Código:
- https://github.com/google/generative-ai-docs

### Comunidade:
- Stack Overflow (tag: google-gemini)
- Reddit: r/GoogleGemini
- Discord de desenvolvedores Google

---

## 🎯 CHECKLIST FINAL

Antes de publicar, verifique:

- [ ] Chave API configurada
- [ ] Testado mensagem diária
- [ ] Testado dica do mentor
- [ ] Testado aprofundamento
- [ ] Repositório privado (se GitHub)
- [ ] Limites de cota verificados
- [ ] IA respondendo em português
- [ ] Respostas fazem sentido

---

## 🆘 SUPORTE

### Problemas com a API?

1. **Documentação:** https://ai.google.dev/docs
2. **Status da API:** https://status.cloud.google.com
3. **Suporte Google:** https://support.google.com

### Problemas com o Código?

1. Abra as Ferramentas de Desenvolvedor (F12)
2. Vá em **Console**
3. Veja mensagens de erro
4. Pesquise erro no Google

---

## 🎉 PARABÉNS!

Agora seu **EspiriQuiz** tem inteligência artificial integrada! 🤖✨

**Aproveite as funcionalidades:**
- ✨ Mensagens inspiradoras diárias
- 🧠 Mentoria socrática inteligente
- 📚 Aprofundamento doutrinário detalhado

**Desenvolvido com 💜 por Alessandro M. Barreto**

*"O Espiritismo é, ao mesmo tempo, uma ciência de observação e uma doutrina filosófica."* - Allan Kardec
