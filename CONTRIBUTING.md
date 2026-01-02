# 🤝 Guia de Contribuição

Primeiro de tudo, **obrigado por considerar contribuir** com este projeto! 

Este é um guia **gratuito e colaborativo**, e contribuições da comunidade são o que o tornam cada vez melhor.

---

## 📋 Índice

- [Como posso contribuir?](#como-posso-contribuir)
- [Reportando bugs](#reportando-bugs)
- [Sugerindo melhorias](#sugerindo-melhorias)
- [Contribuindo com código/conteúdo](#contribuindo-com-códigoconteúdo)
- [Guia de estilo](#guia-de-estilo)
- [Código de conduta](#código-de-conduta)

---

## 🌟 Como posso contribuir?

Existem várias formas de contribuir, mesmo sem escrever código:

### 1. 🐛 Reportar erros ou informações desatualizadas
- Encontrou algo incorreto?
- Algum link quebrado?
- Informação desatualizada?

[Abra uma issue](../../issues/new) descrevendo o problema!

### 2. 💡 Sugerir melhorias
- Tem ideias para tornar o guia melhor?
- Quer propor novos tópicos?
- Conhece ferramentas úteis que não estão listadas?

[Abra uma issue](../../issues/new) com sua sugestão!

### 3. ✍️ Contribuir com conteúdo
- Adicionar exemplos da sua área
- Compartilhar casos de sucesso
- Escrever dicas específicas
- Melhorar explicações existentes

Veja a seção [Contribuindo com conteúdo](#contribuindo-com-códigoconteúdo)

### 4. 🌍 Traduzir o guia
- Ajude a tornar este conteúdo acessível em outros idiomas
- Inglês, Espanhol, Francês, e outros

### 5. 🎨 Criar recursos visuais
- Templates de banner
- Infográficos
- Diagramas explicativos
- Screenshots de exemplo

### 6. ⭐ Compartilhar
- Dê uma estrela no repositório
- Compartilhe nas redes sociais
- Indique para amigos e colegas

---

## 🐛 Reportando bugs

Ao reportar um problema, inclua:

**Descrição clara:**
- O que está errado?
- Onde está localizado? (seção, linha)

**Como reproduzir:**
- Passos para verificar o problema

**Resultado esperado:**
- Como deveria ser?

**Screenshots (se aplicável):**
- Imagens ajudam muito!

**Template de issue:**
```markdown
## 🐛 Descrição do problema
[Descreva o problema aqui]

## 📍 Localização
- Arquivo: `artigo.md`
- Seção: "Headline"
- Linha: 150

## ✅ Solução esperada
[Como deveria ser]

## 📸 Screenshots (opcional)
[Cole imagens se necessário]
```

---

## 💡 Sugerindo melhorias

Ao sugerir melhorias, inclua:

**Contexto:**
- Por que essa melhoria é importante?
- Que problema ela resolve?

**Proposta:**
- O que você sugere especificamente?
- Como isso ajudaria os usuários?

**Exemplos (se possível):**
- Referências ou exemplos práticos

**Template de issue:**
```markdown
## 💡 Sugestão de melhoria

**Problema/Oportunidade:**
[Descreva o contexto]

**Proposta:**
[Sua sugestão detalhada]

**Benefícios:**
- Benefício 1
- Benefício 2

**Exemplos (opcional):**
[Links, referências, exemplos práticos]
```

---

## ✍️ Contribuindo com código/conteúdo

### Processo de contribuição:

#### 1. Fork o repositório
Clique em "Fork" no canto superior direito

#### 2. Clone seu fork
```bash
git clone https://github.com/seu-usuario/guia-linkedin.git
cd guia-linkedin
```

#### 3. Crie uma branch
```bash
git checkout -b minha-contribuicao
```

**Nomes de branches sugeridos:**
- `adiciona-exemplos-marketing` — para novos exemplos
- `corrige-secao-headline` — para correções
- `melhora-formatacao` — para melhorias de formato
- `traduz-para-ingles` — para traduções

#### 4. Faça suas alterações

**Dicas:**
- Siga o [guia de estilo](#guia-de-estilo)
- Teste todos os links que adicionar
- Mantenha a formatação consistente
- Seja claro e direto

#### 5. Commit suas mudanças
```bash
git add .
git commit -m "Adiciona exemplos de headline para área de marketing"
```

**Mensagens de commit:**
- Use verbos no imperativo: "Adiciona", "Corrige", "Melhora"
- Seja específico e claro
- Mantenha commits pequenos e focados

**Bons exemplos:**
- ✅ "Adiciona seção sobre otimização de foto de perfil"
- ✅ "Corrige links quebrados na seção de recursos"
- ✅ "Melhora explicação sobre SSI Score"

**Evite:**
- ❌ "Mudanças várias"
- ❌ "Update"
- ❌ "Correções"

#### 6. Push para seu fork
```bash
git push origin minha-contribuicao
```

#### 7. Abra um Pull Request

No GitHub, vá até seu fork e clique em "New Pull Request"

**Template de PR:**
```markdown
## 📝 Descrição

[Descreva suas mudanças]

## 🎯 Tipo de mudança

- [ ] 🐛 Correção de bug/erro
- [ ] ✨ Nova funcionalidade/conteúdo
- [ ] 📝 Melhoria de documentação
- [ ] 🎨 Melhoria de formatação
- [ ] 🌍 Tradução

## ✅ Checklist

- [ ] Revisei meu próprio código/conteúdo
- [ ] Testei todos os links
- [ ] Segui o guia de estilo
- [ ] Atualizei documentação relacionada (se aplicável)

## 📸 Screenshots (se aplicável)

[Cole imagens se necessário]
```

---

## 📐 Guia de estilo

### Markdown

**Títulos:**
```markdown
# Título Principal (H1) — apenas para título do documento
## Seção Principal (H2)
### Subseção (H3)
#### Sub-subseção (H4)
```

**Ênfase:**
```markdown
**Negrito** para palavras-chave importantes
*Itálico* para ênfase suave
`Código` para comandos, arquivos, código
```

**Listas:**
```markdown
- Item com -
- Mantém consistência

1. Listas numeradas
2. Para passos sequenciais
```

**Links:**
```markdown
[Texto do link](https://url.com)

Para links internos:
[Voltar ao topo](#título-da-seção)
```

**Emojis:**
- ✅ Use com moderação
- ✅ Mantenha consistência (mesmo emoji para mesma função)
- ✅ Coloque no início de títulos quando apropriado
- ❌ Não exagere

### Conteúdo

**Tom de voz:**
- 🗣️ Seja conversacional, mas profissional
- 💬 Use "você" ao invés de "vocês"
- ✍️ Escreva como se estivesse explicando para um amigo
- 🎯 Seja direto e prático

**Estrutura:**
- 📋 Organize em seções claras
- 📊 Use tabelas quando comparar informações
- ✅ Use checklists para ações
- 💡 Destaque dicas importantes

**Exemplos:**
- ✅ Sempre que possível, inclua exemplos práticos
- ✅ Use exemplos de diferentes áreas
- ✅ Mostre "antes e depois" quando relevante

---

## 📜 Código de conduta

### Nosso compromisso

Este é um projeto **inclusivo e acolhedor**. Todos são bem-vindos, independentemente de:
- 🌍 Nacionalidade, etnia ou origem
- 🗣️ Idioma nativo
- 🎓 Nível de experiência ou educação
- 👥 Gênero, identidade ou orientação
- 🧠 Capacidades físicas ou mentais
- 💼 Área profissional ou senioridade

### Comportamentos esperados

✅ **Seja respeitoso** — Trate todos com gentileza  
✅ **Seja construtivo** — Críticas devem ser úteis  
✅ **Seja paciente** — Nem todos têm o mesmo nível de conhecimento  
✅ **Seja colaborativo** — Estamos todos aqui para ajudar  
✅ **Seja humilde** — Todos cometem erros  

### Comportamentos inaceitáveis

❌ Linguagem ofensiva ou discriminatória  
❌ Assédio de qualquer tipo  
❌ Spam ou autopromoção excessiva  
❌ Publicação de informações privadas sem consentimento  
❌ Trolling ou provocações deliberadas  

### Aplicação

Comportamentos inaceitáveis não serão tolerados. Infrações podem resultar em:
1. Aviso
2. Banimento temporário
3. Banimento permanente

Para reportar problemas, abra uma issue ou entre em contato diretamente.

---

## ❓ Dúvidas

Tem dúvidas sobre como contribuir?

- 💬 Abra uma [Discussion](../../discussions)
- 📧 Entre em contato através de uma issue
- 💡 Veja contribuições anteriores como exemplo

---

## 🙏 Agradecimento

**Muito obrigado por contribuir!** 

Cada contribuição, por menor que seja, ajuda a tornar este guia melhor para toda a comunidade.

---

<div align="center">

**✨ Construído com ❤️ pela comunidade ✨**

[⬆️ Voltar ao topo](#-guia-de-contribuição)

</div>
