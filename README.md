# JWPlay History — App

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/igor-rl/jwplay-history-app?style=flat-square&color=blue)](https://github.com/igor-rl/jwplay-history-app/releases/latest)

Página de download e releases do aplicativo desktop **JWPlay History** — acompanha listas de vídeos do jw.org (Adoração Matinal, Discursos, Formatura de Gileade, Boletins, Broadcasting e Clipes Musicais), marca o que você já assistiu e abre direto no JW Library.

## 📥 Download

| Sistema | Arquivo |
|---|---|
| **macOS** (Apple Silicon e Intel) | `JWPlay-History-x.x.x.dmg` |
| **Windows** (instalador) | `JWPlay-History-Setup-x.x.x.exe` |

👉 **[Ver todas as versões](https://github.com/igor-rl/jwplay-history-app/releases)**

### macOS

1. Abra o `.dmg` e arraste o app para **Aplicativos**
2. Como o app não é assinado pela Apple, o macOS irá bloqueá-lo na primeira abertura. Para liberar, abra o **Terminal** e rode:

```bash
xattr -rd com.apple.quarantine '/Applications/JWPlay History.app' && open '/Applications/JWPlay History.app'
```

Ou vá em **Ajustes do Sistema → Privacidade e Segurança** e clique em **"Abrir mesmo assim"**.

### Windows

1. Execute o instalador `.exe` e siga os passos
2. Se o Windows avisar que o app não é reconhecido, clique em **Mais informações → Executar assim mesmo** (o app não é assinado)
3. O app criará um atalho na Área de Trabalho e no Menu Iniciar

> O histórico de assistidos fica em `~/Library/Application Support/AdoracaoMatinal` (macOS) ou `%AppData%\AdoracaoMatinal` (Windows) e não é apagado ao instalar uma versão nova ou desinstalar.

## Página

A página de download (`home.html`, `index.html`, `privacidade.html`) é servida pelo GitHub Pages deste repositório. O `index.html` busca a última release e monta o botão de download conforme o sistema do visitante.

---

> Não é um aplicativo oficial do jw.org.

<br/>
<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-Igor_Lage-blue?style=social&logo=github)](https://github.com/igor-rl)

</div>
