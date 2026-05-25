# 💅 Meus Atendimentos

> App mobile-first para profissionais da beleza registrarem atendimentos, acompanharem ganhos e exportarem relatórios mensais.

![HTML](https://img.shields.io/badge/HTML-puro-orange?style=flat-square&logo=html5)
![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-yellow?style=flat-square&logo=javascript)
![PWA Ready](https://img.shields.io/badge/PWA-ready-green?style=flat-square)

---

## ✨ Funcionalidades

- **Registrar atendimentos** com serviço, cliente e data
- **Cálculo automático** do ganho líquido — cada serviço tem seu próprio preço e percentual de comissão configurados diretamente no código
- **Serviço "Outros"** para registrar qualquer procedimento fora da lista, informando descrição, valor e percentual de ganho na hora
- **Histórico mensal** agrupado por dia, com opção de excluir registros
- **Resumo visual** com ranking de serviços e totais do mês
- **Exportar planilha `.xlsx`** com duas abas: atendimentos detalhados e resumo por serviço
- **Navegação por mês** para consultar históricos anteriores
- **Dados salvos localmente** no navegador (sem servidor, sem cadastro)

---

## ⚙️ Personalizando serviços e valores

Todos os serviços, preços e percentuais de comissão ficam no objeto `SERVICOS` dentro do `index.html`. Para adicionar, remover ou ajustar qualquer serviço, basta editar esse trecho diretamente no arquivo — não é necessário nenhuma ferramenta especial, um editor de texto simples já resolve.

---

## 🚀 Como usar

O app é um único arquivo HTML — sem instalação, sem dependências, sem servidor.

### Opção 1 — Abrir direto no navegador

1. Baixe o arquivo `index.html`
2. Abra no Chrome ou Safari (mobile ou desktop)
3. Comece a registrar!

### Opção 2 — GitHub Pages (acesso via link, de qualquer celular)

1. Faça fork ou clone deste repositório
2. Vá em **Settings → Pages**
3. Em *Source*, selecione a branch `main` e a pasta `/ (root)`
4. Salve — em alguns minutos o app estará disponível em:
   ```
   https://seu-usuario.github.io/nome-do-repositorio/
   ```

### Opção 3 — Adicionar à tela inicial (PWA-like)

No **iPhone/iPad (Safari):**
1. Abra o link do GitHub Pages no Safari
2. Toque em **Compartilhar** → **Adicionar à Tela de Início**
3. O app abre em tela cheia, igual a um aplicativo nativo

No **Android (Chrome):**
1. Abra o link no Chrome
2. Toque nos três pontos → **Adicionar à tela inicial**

---

## 🗂 Estrutura

```
/
└── index.html   # App completo (HTML + CSS + JS em um único arquivo)
```

---

## 🔒 Privacidade

Todos os dados ficam salvos apenas no `localStorage` do seu próprio navegador — nada é enviado para nenhum servidor. Limpar os dados do site apaga os registros.

---

## 🛠 Tecnologias

- HTML5, CSS3 e JavaScript puro (sem frameworks)
- [SheetJS (xlsx)](https://sheetjs.com/) para exportação de planilhas
- [Google Fonts](https://fonts.google.com/) — DM Serif Display + DM Sans
- `localStorage` para persistência local dos dados

---

## 📄 Licença

Uso pessoal. Sinta-se à vontade para adaptar para a sua realidade.
