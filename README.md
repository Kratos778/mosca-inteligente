# 🐞 Mosca Inteligente

Simulador de vida de uma **mosca inteligente** com cérebro real (Grok API).

A mosca tem um corpo gráfico e se move sozinha.  
A IA (Grok) é **apenas o cérebro**.  
Ela **aprende de verdade** com cada morte (memória persistente).

---

## Como usar

### 1. Abrir o app

- Vá em: [https://kratos778.github.io/mosca-inteligente/](https://kratos778.github.io/mosca-inteligente/)  
  *(ou abra o arquivo `index.html` direto no navegador)*

### 2. Colocar sua chave da API do Grok (opcional mas recomendado)

1. Entre em [console.x.ai](https://console.x.ai)
2. Crie uma API Key e adicione créditos
3. No app, clique em **⚙️ Configurações**
4. Cole a chave e salve

> Sem a chave o app funciona em **modo simulado** (cérebro fake).  
> Com a chave ela fica realmente inteligente.

### 3. Jogar

- A mosca nasce e começa a viver sozinha
- Ela sente fome, curiosidade, medo, energia, etc.
- Coisas que atraem: açúcar, fruta, luz
- Você pode:
  - Clicar na mosca → tentar matar com a mão
  - Usar o botão **Spray**
  - Usar o botão **Fechar Janela**
- Quando ela morre, aparece o **pensamento final** dela
- Na próxima vida ela já lembra das mortes anteriores e tenta evitar os mesmos erros

---

## O que é aprendizado real?

Toda morte é salva no navegador (`localStorage`).  
Na próxima vida o cérebro recebe o histórico completo das mortes.  
Quanto mais ela morre, mais esperta fica. Isso não é código if/else — é memória real.

---

## Estrutura do projeto

- `index.html` → App completo (HTML + CSS + JS embutidos)
- Memória salva automaticamente no navegador
- Pronto para ser transformado em APK depois (Capacitor / PWA)

---

## Próximos passos possíveis

- Melhorar o visual da mosca (sprites melhores)
- Adicionar mais objetos e perigos
- Transformar em APK Android
- Adicionar som e partículas

Feito com ❤️ para o Elizier.
