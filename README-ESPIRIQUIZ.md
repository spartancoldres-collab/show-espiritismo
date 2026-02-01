# 🌟 EspiriQuiz - Versão 3.0 com IA

**Quiz Interativo Inteligente sobre O Livro dos Espíritos**

Desenvolvido com 💜 por **Alessandro M. Barreto**

---

## ✨ NOVIDADES DA VERSÃO 3.0

### 🤖 Integração com IA Gemini

1. **✨ Mensagem de Luz Diária**
   - Reflexão espiritual gerada por IA
   - Baseada nos princípios espíritas
   - Nova mensagem a cada 24 horas

2. **🧠 Dica do Mentor (Método Socrático)**
   - IA não dá resposta direta
   - Guia seu raciocínio com perguntas
   - Usa analogias da doutrina

3. **📚 Aprofundamento Doutrinário**
   - Explicação filosófica profunda
   - Base científica da época de Kardec
   - Relação com outros princípios

### 🎮 Melhorias de Gameplay

- ✅ **Nome atualizado:** EspiriQuiz
- ✅ **Controle de som:** Botão flutuante para ativar/desativar
- ✅ **Botão sair:** Presente em todas as telas do jogo
- ✅ **Perguntas corrigidas:** Espaçamentos extras removidos
- ✅ **Conquista nova:** "Buscador da Sabedoria" (usar IA 10x)

---

## 🚀 INÍCIO RÁPIDO

### Opção 1: Sem IA (Funciona Imediatamente)

1. Abra `index.html` no navegador
2. Jogue normalmente
3. As funcionalidades de IA mostrarão mensagem sobre configuração

### Opção 2: Com IA (5 minutos para configurar)

1. Obtenha chave API gratuita: https://makersuite.google.com/app/apikey
2. Abra `index.html` em editor de texto
3. Encontre `const GEMINI_API_KEY = 'SUA_CHAVE_API_AQUI'`
4. Substitua pela sua chave
5. Salve e abra no navegador

**Guia completo:** Veja `GUIA-API-GEMINI.md`

---

## 🎯 FUNCIONALIDADES COMPLETAS

### 🏆 Sistema de Conquistas
- 9 conquistas desbloqueáveis
- Nova: 🧠 Buscador da Sabedoria

### 💡 Sistema de Ajudas
- Pular pergunta (1x)
- Eliminar 2 alternativas (1x)
- Dica tradicional (1x)
- **NOVO:** Dica do Mentor IA (ilimitado)

### 📖 Modo Estudo
- Sem limite de erros
- Explicações detalhadas
- **NOVO:** Aprofundamento com IA

### 📊 Estatísticas
- 7 métricas diferentes
- **NOVO:** Contador de uso da IA
- Ranking local top 10

### 🎨 Interface
- Design moderno e profissional
- **NOVO:** Controle de som flutuante
- **NOVO:** Botão sair em todas as telas
- Animações suaves
- Totalmente responsivo

### 🔊 Sistema de Áudio
- 5 sons zen premium
- **NOVO:** Controle on/off global
- Volume otimizado

---

## 📦 ESTRUTURA DE ARQUIVOS

```
espiriquiz/
│
├── index.html                    # Jogo completo com IA
├── questions_improved.json       # 100 perguntas balanceadas
├── manifest.json                 # PWA
├── sw.js                        # Service Worker
├── README.md                    # Este arquivo
├── GUIA-API-GEMINI.md          # Como configurar IA
└── IMPLEMENTACOES-COMPLETAS.md # Documentação técnica
```

---

## 🤖 SOBRE A IA

### Tecnologia
- **Google Gemini Pro** - IA de última geração
- Treinada em vastos conhecimentos
- Personalizada para Espiritismo

### Uso Responsável
- IA como ferramenta de **estudo**
- Não substitui leitura dos livros
- Complementa o aprendizado

### Privacidade
- Nenhum dado pessoal enviado
- Apenas perguntas e contexto
- Processamento na nuvem Google

---

## 🎮 CONTROLES DO JOGO

### Controle de Som (Novo!)
- 🔊/🔇 Botão no canto superior direito
- Desliga TODOS os sons
- Persiste entre telas

### Botão Sair (Novo!)
- ← Botão no canto superior esquerdo
- Volta ao menu principal
- Confirmação se estiver jogando

### Atalhos de Teclado
- **Escape:** Pausar/Sair
- **Espaço:** Avançar após resposta
- **1-4:** Selecionar alternativa

---

## 📚 COMO JOGAR

### Modo Normal
1. Escolha dificuldade e capítulo
2. Responda perguntas
3. **Use ajudas tradicionais estrategicamente**
4. **NOVO:** Peça dica da IA quando precisar
5. **NOVO:** Após acertar, aprofunde com IA

### Modo Estudo
1. Sem pressão de pontuação
2. Aprenda com explicações
3. **NOVO:** Solicite aprofundamento IA
4. Revise quantas vezes quiser

---

## 🔑 CONFIGURAR API GEMINI

### Passo Rápido:

```javascript
// No arquivo index.html, linha ~260
const GEMINI_API_KEY = 'AIzaSy...' // Cole sua chave aqui
```

### Guia Completo:
Veja `GUIA-API-GEMINI.md` para instruções detalhadas.

### Obtendo Chave (Grátis):
1. Acesse: https://makersuite.google.com/app/apikey
2. Faça login com Google
3. Clique "Create API key"
4. Copie a chave gerada

**Limites Gratuitos:**
- 60 requisições/minuto
- 1.500 requisições/dia
- 1 milhão tokens/mês
- **Totalmente suficiente!**

---

## 💬 EXEMPLOS DE IA

### Mensagem de Luz Diária
```
"A caridade não consiste apenas em dar esmola, mas em sermos 
bondosos, indulgentes e benévolos. Cada ato de amor eleva o 
espírito..."
```

### Dica do Mentor
```
"Reflita: se Deus é a causa primária, o que isso nos diz sobre
o acaso? Pense também no que vemos na natureza - há ordem ou
desordem?"
```

### Aprofundamento Doutrinário
```
"Esta resposta se fundamenta na lei de causalidade universal.
Kardec usou a lógica científica de sua época ao afirmar que
todo efeito tem uma causa..."
```

---

## 🎯 DIFERENÇAS DAS VERSÕES

| Recurso | v1.0 | v2.0 | v3.0 (atual) |
|---------|------|------|--------------|
| Conquistas | ❌ | ✅ 8 | ✅ 9 |
| Ajudas | ❌ | ✅ 3 | ✅ 3 + IA |
| IA Gemini | ❌ | ❌ | ✅ |
| Controle Som | ⚠️ Menu | ⚠️ Menu | ✅ Global |
| Botão Sair | ❌ | ❌ | ✅ |
| Espaçamentos | ⚠️ | ⚠️ | ✅ |
| Nome | Show Esp. | Show Esp. | **EspiriQuiz** |

---

## 📱 HOSPEDAGEM

### GitHub Pages (Recomendado)
Veja `GUIA-GITHUB-PAGES.md`

**Atenção:** Deixe repositório **privado** para proteger chave API!

### Netlify/Vercel
- Upload da pasta
- Deploy automático
- HTTPS grátis

---

## 🐛 SOLUÇÃO DE PROBLEMAS

### IA não funciona
1. Verifique chave API
2. Teste conexão internet
3. Veja console do navegador (F12)

### Sons não tocam
1. Clique em qualquer botão primeiro
2. Verifique se não está no mudo
3. Use botão de controle de som

### Perguntas não carregam
1. Certifique-se que `questions_improved.json` existe
2. Verifique nome do arquivo
3. Veja console para erros

---

## 🎨 PERSONALIZAÇÃO

### Alterar Nome do Jogo
Busque "EspiriQuiz" e substitua

### Alterar Cores
Edite variáveis CSS no `<style>`

### Adicionar Perguntas
Edite `questions_improved.json`

### Customizar Prompts IA
Edite funções:
- `generateDailyMessage()`
- `generateMentorTip()`
- `generateDeepDive()`

---

## 📊 ESTATÍSTICAS RASTREADAS

- Total de partidas
- Recorde pessoal
- Jogos perfeitos
- Taxa de acertos
- Jogos sem ajudas
- Tempo mais rápido
- Capítulos jogados
- **NOVO:** Uso da IA

---

## 🏆 CONQUISTAS

1. 🌟 Primeira Vitória
2. 💯 Jogo Perfeito
3. ⚡ Raio de Luz
4. 🔥 Persistente
5. 📚 Estudioso
6. 👑 Mestre Espírita
7. 🎓 Autodidata
8. 🏆 Recorde Quebrado
9. **🧠 Buscador da Sabedoria (NOVO!)**

---

## 💝 CRÉDITOS

**Desenvolvedor:**
Alessandro M. Barreto

**Baseado em:**
O Livro dos Espíritos - Allan Kardec

**Tecnologias:**
- React 18
- Tailwind CSS
- Google Gemini AI
- Mixkit (sons)

**Agradecimentos:**
- Allan Kardec - pela obra
- Comunidade Espírita
- Google AI Team
- Você - por jogar!

---

## 📄 LICENÇA

Open Source - Uso educacional livre

**Mantenha os créditos:**
Alessandro M. Barreto

---

## 📞 SUPORTE

### Dúvidas sobre o Jogo:
- Veja documentação incluída
- Abra issue no GitHub
- Envie email

### Dúvidas sobre API Gemini:
- Veja `GUIA-API-GEMINI.md`
- Documentação: https://ai.google.dev/docs
- Suporte Google: https://support.google.com

---

## 🚀 ROADMAP

### v3.1 (Próximo)
- [ ] IA explica respostas erradas
- [ ] Chat com mentor espiritual
- [ ] Geração de exercícios personalizados

### v3.2
- [ ] IA gera novas perguntas
- [ ] Sistema de níveis com IA
- [ ] Recomendações de estudo

### v4.0
- [ ] Multiplayer com IA árbitro
- [ ] Debates espíritas com IA
- [ ] Análise de evolução do jogador

---

## 📖 DOCUMENTAÇÃO

- `README.md` - Este arquivo (visão geral)
- `GUIA-API-GEMINI.md` - Configurar IA (detalhado)
- `GUIA-GITHUB-PAGES.md` - Hospedar online
- `IMPLEMENTACOES-COMPLETAS.md` - Técnico completo

---

## 🎮 DEMONSTRAÇÃO

**Funcionalidades:**
✅ Quiz interativo profissional
✅ 100 perguntas balanceadas
✅ 9 conquistas desbloqueáveis
✅ 3 níveis de dificuldade
✅ Sistema de ajudas
✅ Modo estudo
✅ Ranking local
✅ PWA instalável
✅ **IA Gemini integrada**
✅ **Controle de som global**
✅ **Botão sair universal**
✅ **Espaçamentos corrigidos**

---

## 🌟 DIFERENCIAIS

### Único quiz espírita com:
- 🤖 IA especializada em Espiritismo
- 🧠 Método socrático de ensino
- 📚 Aprofundamento filosófico
- ✨ Mensagens diárias inspiradoras
- 🎯 Perguntas verdadeiramente desafiadoras

---

## 📝 CHANGELOG

### v3.0 (Atual)
- ✨ Integração completa com IA Gemini
- 🔊 Controle de som global
- ← Botão sair em todas as telas
- 🧹 Espaçamentos corrigidos
- 📛 Renomeado para EspiriQuiz
- 🏆 Nova conquista de IA

### v2.0
- 🏆 Sistema de conquistas
- 💡 Sistema de ajudas
- 📖 Modo estudo
- 📊 Estatísticas avançadas
- 🏅 Ranking local

### v1.0
- 🎮 Jogo base funcional
- 📚 Perguntas do livro
- 🔊 Sistema de som

---

**Versão:** 3.0 AI Edition
**Data:** Janeiro 2026
**Status:** ✅ Produção

---

*"O Espiritismo é, ao mesmo tempo, uma ciência de observação e uma doutrina filosófica."*
**- Allan Kardec**

---

**Desenvolvido com 💜 por Alessandro M. Barreto**

Para a comunidade espírita, com amor, dedicação e tecnologia de ponta. 🙏✨🤖
