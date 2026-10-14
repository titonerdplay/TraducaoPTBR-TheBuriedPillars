# Tradução PT-BR — The Buried Pillars

Tradução completa para português brasileiro do jogo **The Buried Pillars**, feita via plugin BepInEx + Harmony. O jogo não possui localização oficial, então todos os textos foram traduzidos manualmente.

---

## 📋 O que está traduzido

- Menus (título, opções, controles, dificuldade, slots de save)
- Habilidades e descrições
- Diálogos e cutscenes
- Notificações (galeria, recompensas, derrotas)
- Mapa e nomes de áreas
- Itens, loja e interações com NPCs
- Telas de fim de jogo e modo Bossrush

**Observação:** a fonte do jogo não suporta acentos, então toda a tradução usa apenas caracteres ASCII (ex: `nao`, `voce`, `feitico`).

---

## ⚙️ Requisitos

- **The Buried Pillars** (versão Steam, Windows x64)
- **BepInEx 5.4.x** (x64) — [Baixar aqui](https://github.com/BepInEx/BepInEx/releases)

---

## 📥 Como baixar a tradução

1. Só ir até o botão verde lá em cima escrito **Code** nessa página.
2. Clique em **Download ZIP**.
3. Extraia o conteúdo em qualquer pasta.

---

## 🔧 Como instalar

### 1. Instalar o BepInEx

1. Baixe o **BepInEx 5.4.x (x64)** no link acima.
2. Extraia o conteúdo do `.zip` diretamente na pasta raiz do jogo, onde fica o `TheBuriedPillars.exe`.

   O caminho típico é:
   C:\Program Files (x86)\Steam\steamapps\common\The Buried Pillars\

3. Execute o jogo uma vez e feche. Isso faz o BepInEx criar as pastas necessárias (`BepInEx\plugins\`, `BepInEx\config\`, etc.).

### 2. Instalar a tradução

1. Abra a pasta `BepInEx\plugins\` dentro da pasta do jogo.
2. Copie a pasta `TraducaoPTBR` (com o `TraducaoPTBR.dll` e o `traducao.json` dentro) para lá.

A estrutura final deve ficar assim:
The Buried Pillars
└── BepInEx
└── plugins
└── TraducaoPTBR
├── TraducaoPTBR.dll
└── traducao.json

3. Abra o jogo. A tradução estará ativa automaticamente.

---

## ❓ Possíveis Perguntas

**A tradução não apareceu. O que fazer?**
- Verifique se o BepInEx está instalado corretamente (deve existir uma pasta `BepInEx` na raiz do jogo).
- Confirme que o `TraducaoPTBR.dll` e o `traducao.json` estão na mesma pasta (`BepInEx\plugins\TraducaoPTBR\`).
- Abra o arquivo `BepInEx\LogOutput.txt` e procure pela linha `Traducao PT-BR carregada com sucesso!`. Se ela aparecer, o plugin está funcionando.

**A tradução quebra o jogo ou os saves?**
Não. O plugin apenas substitui os textos em tempo de execução. Ele não altera nenhum arquivo do jogo e não interfere nos saves.

---

## 📜 Créditos

Tradução feita por **Tito** (https://x.com/TitoNerdArts).

Espero que a tradução esteja ok, enquanto eu fui jogando eu ia traduzindo junto, não pretendo ter q atualizar novamente ou algo do tipo, se ainda tiver algo em inglês, espero q seja algo bobo e que não faça diferença :P
---

## ⚠️ Aviso

Este é um mod amador e sem fins lucrativos. Todos os direitos sobre o jogo original pertencem aos seus respectivos desenvolvedores. A tradução é distribuída gratuitamente e não deve ser vendida.
