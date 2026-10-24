# 🐞 Mosca Inteligente

Simulador de vida de uma mosca com **cérebro real (Grok)**.

- O corpo (gráficos + física) já vem pronto
- A IA é **só o cérebro**
- **Sem API Key o cérebro fica desligado** (a mosca só voa de forma básica e aleatória)
- Com API Key o Grok decide tudo e ela aprende de verdade com as mortes

Não existe inteligência falsa / simulada.

---

## Como usar

### 1. Abrir

- Baixe ou abra o `index.html` no navegador
- Ou ative GitHub Pages e use: https://kratos778.github.io/mosca-inteligente/

### 2. Ligar o cérebro

1. Entre em [console.x.ai](https://console.x.ai)
2. Crie uma API Key e coloque créditos
3. No app clique em ⚙️
4. Cole a chave e salve

O status no canto superior direito mostra:
- **CÉREBRO: DESLIGADO** → sem chave
- **CÉREBRO: GROK LIGADO** → com chave

### 3. Jogar

- Sem chave: a mosca só voa aleatoriamente (corpo sem cérebro)
- Com chave: a cada poucos segundos o Grok decide a ação e o pensamento
- Você pode matar ela (Spray, Mão, Janela fechada)
- Quando morre aparece o pensamento final
- Na próxima vida as memórias de morte são enviadas para o Grok (aprendizado real)

---

## Aprendizado real

Toda morte é salva no `localStorage` do navegador.  
Na próxima vida o prompt do Grok recebe o histórico das mortes.  
Não há if/else de "se já morreu de spray então foge". Quem decide é só o modelo.

---

Repositório: https://github.com/Kratos778/mosca-inteligente
