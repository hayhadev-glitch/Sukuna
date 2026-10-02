<div align="center">

<img src="logo.png" width="140" alt="Sukuna">

# 領域展開 — SUKUNA HOST

**「 Domain Expansion • Malevolent Shrine 」**

*PS4 Jailbreak Host*

<img src="preview.png" width="700" alt="Preview do Host">

![PS4](https://img.shields.io/badge/PS4-Jailbreak-dc0000?style=for-the-badge&logo=playstation&logoColor=white)
![Firmware](https://img.shields.io/badge/FW-13.02%20•%2013.04%20•%2013.50%20•%2013.52-8b0000?style=for-the-badge)
![Offline](https://img.shields.io/badge/Offline-AppCache-red?style=for-the-badge)
![License](https://img.shields.io/badge/Uso-Educacional-444444?style=for-the-badge)

</div>

---

> *"Know your place, fool."* — Ryomen Sukuna

---

## ⚔️ Sobre

**SUKUNA HOST** é um host de jailbreak para PlayStation 4 com tema no Rei das Maldições. Ao acessar, o domínio é expandido:

1. 🔍 Detecta automaticamente o **firmware** do console
2. 📦 Prepara o **cache offline** (AppCache) para funcionar sem internet
3. 👹 Invoca a *Domain Expansion* e executa o exploit

---

## 🩸 Firmwares Suportados

| Firmware | Status |
|:--------:|:------:|
| 13.02 | ✅ Suportado |
| 13.04 | ✅ Suportado |
| 13.50 | ✅ Suportado |
| 13.52 | ✅ Suportado |

> ⚠️ Outros firmwares mostram **UNSUPPORTED** — mas é possível forçar com `?force=1` no fim da URL (por sua conta e risco).

---

## 🔗 Acesso

**URL:**
https://hayhadev-glitch.github.io/Sukuna/


### 📜 Ver log do exploit
https://hayhadev-glitch.github.io/Sukuna/jb.html?log=1


---

## 📁 Estrutura
📦 sukuna-host
├── 📄 index.html → detecção de firmware + cache
├── 📄 jb.html → página do exploit
├── 📜 jb.js → exploit principal
├── 📜 ps4_offsets.js → tabela de offsets por firmware
├── 🗂️ cache.appcache → manifest do cache offline
├── 🖼️ bg.jpg → fundo (Malevolent Shrine)
└── 👹 logo.png → marcas do Sukuna


---

## 🔄 Atualizando o Host

Ao alterar qualquer arquivo:

1. Incremente a versão no `cache.appcache` → `# v20`
2. Se mexer no exploit, atualize o import → `jb.js?v=20`
3. Faça commit — o GitHub Pages atualiza em ~1 minuto

---

## ❓ FAQ

<details>
<summary><b>O cache não atualiza no PS4</b></summary>
<br>
Abra a página online e force a atualização, ou limpe os dados do navegador do PS4: <i>Configurações → Excluir dados do navegador</i>.
</details>

<details>
<summary><b>Aparece "FIRMWARE NÃO SUPORTADO"</b></summary>
<br>
Seu firmware não está na tabela do <code>index.html</code> e do <code>ps4_offsets.js</code>. Atualize os dois mantendo-os sincronizados, ou force com <code>?force=1</code>.
</details>

<details>
<summary><b>Funciona sem internet?</b></summary>
<br>
Sim. Após o primeiro acesso com o cache pronto (<code>cache pronto — offline ok</code>), tudo roda local no console.
</details>

---

## ⚖️ Aviso

> Este projeto é destinado **exclusivamente a fins educacionais e de preservação**. O uso é de **total responsabilidade do usuário**. Não nos responsabilizamos por danos aos consoles ou violação de termos de garantia. Jailbreak pode resultar em **banimento da PSN**.

---

<div align="center">

**両面宿儺**

*「 Domain Expansion — Malevolent Shrine 」*

⭐ Deixe uma estrela se o host te ajudou

</div>
