<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:0F172A,100:00ADD8&text=Danillo%20Teodoro&fontColor=ffffff&fontSize=42&fontAlignY=35&desc=Go%20Developer%20%C2%B7%20Backend%20%26%20Desktop&descAlignY=55" alt="Header" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/danillo-teodoro-48a89b294/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:danillot123@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=danilloteeo&style=for-the-badge&color=00ADD8" alt="Profile views" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=2800&pause=900&color=00ADD8&center=true&vCenter=true&width=760&lines=Go+developer+from+Brazil+%F0%9F%87%A7%F0%9F%87%B7;REST+APIs+with+chi%2C+pgx+and+PostgreSQL;Desktop+apps+with+Wails+%2B+React;Brazilian+fiscal+docs%3A+NF-e%2C+NFC-e%2C+MDF-e" alt="Typing intro" />
</p>

## 👋 About Me

I'm Danillo, a 19-year-old developer from Brazil who builds **real software for real businesses** — point-of-sale systems, fiscal document emitters, licensing servers and desktop tools used every day by small shops.

My main language today is **Go**. I like it because it compiles to a single binary, runs anywhere, and keeps the code simple enough to maintain alone.

- 🐹 Backend in Go: REST APIs, PostgreSQL, migrations, JWT auth, signed tokens
- 🖥️ Desktop in Go: **Wails** (Go + React) and Fyne, offline-first with SQLite
- 🧾 Brazilian fiscal integrations: direct SEFAZ webservices, XML signing, A1 certificates
- 🖨️ Hardware on the counter: ESC/POS thermal printers, barcodes, QR codes

```go
package main

type Developer struct {
	Name     string
	Location string
	Stack    []string
	Building []string
	Focus    string
}

func main() {
	danillo := Developer{
		Name:     "Danillo Teodoro",
		Location: "Brazil 🇧🇷",
		Stack:    []string{"Go", "PostgreSQL", "SQLite", "Wails", "React"},
		Building: []string{"POS systems", "NF-e / NFC-e emitters", "license servers"},
		Focus:    "simple code, single binary, ships on Friday",
	}

	_ = danillo // err == nil, always check it anyway
}
```

## 🛠️ Tech Stack

**Main**
<p>
  <img src="https://skillicons.dev/icons?i=go,postgres,mysql,sqlite,docker&perline=8" alt="Go and databases" />
</p>

**Frontend (Wails UIs)**
<p>
  <img src="https://skillicons.dev/icons?i=ts,react,tailwind,vite&perline=8" alt="Frontend" />
</p>

**Go ecosystem I use**

![Wails](https://img.shields.io/badge/Wails-DF0000?style=flat-square&logo=wails&logoColor=white)
![chi](https://img.shields.io/badge/chi-router-00ADD8?style=flat-square&logo=go&logoColor=white)
![pgx](https://img.shields.io/badge/pgx-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![goose](https://img.shields.io/badge/goose-migrations-00ADD8?style=flat-square&logo=go&logoColor=white)
![Fyne](https://img.shields.io/badge/Fyne-GUI-00ADD8?style=flat-square&logo=go&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-auth-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=flat-square&logo=shadcnui&logoColor=white)

## 🚀 Featured Projects

> Most of these are commercial and live in private repositories — happy to walk through the code in an interview.

| Project | What it does | Stack |
|---|---|---|
| **Vexis PDV** | Point-of-sale platform: multi-company REST backend (companies, branches, registers, terminals), a Wails desktop front-counter app and a dedicated licensing/billing server that unlocks each PDV with short-lived **Ed25519-signed** tokens and Pix charges. | Go · chi · pgx · PostgreSQL · goose · JWT · Wails · React |
| **Lampa NF-e** | Desktop emitter for Brazilian electronic invoices talking **directly to SEFAZ** (no middleman): NF-e and NFC-e issuing, query, cancellation, correction letters and number voiding, with XML-DSig signing and DANFE PDF. | Go · Wails · MySQL · goxmldsig · fpdf |
| **Master PDV** | Offline-first POS: shared Go core, local SQLite, Wails cashier screen, ESC/POS printing and NFC-e. | Go · Wails · SQLite · ESC/POS |
| **ScrUtil** | Desktop app for MDF-e / NF-e fiscal documents written in pure Go, with MySQL repositories and Excel export. | Go · Fyne · MySQL · excelize |
| **[Projeção](https://github.com/danilloteeo/projecao-releases)** | Church projection system: song lyrics, Bible, media, Spotify and playbacks on a second screen. | Go · Wails · React · TypeScript |

## 🎯 Current Focus

- Going deeper into **Go concurrency, testing and profiling**
- Clean architecture for Go services: small packages, explicit dependencies, no magic
- Shipping polished **Wails** desktop apps with installers and auto-update
- Covering more of the Brazilian fiscal stack (NFS-e nacional, MDF-e)

## 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=danilloteeo&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=danilloteeo&layout=compact&hide=c%23,c%2B%2B,dart,javascript,astro,css,html&theme=tokyonight&hide_border=true" alt="Top languages" />
</p>

<p align="center">
  <img height="165" src="https://streak-stats.demolab.com?user=danilloteeo&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=danilloteeo&theme=tokyo-night&hide_border=true&area=true&color=00ADD8&line=00ADD8&point=ffffff" alt="Contribution activity graph" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danilloteeo/danilloteeo/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danilloteeo/danilloteeo/output/github-snake.svg" />
    <img src="https://raw.githubusercontent.com/danilloteeo/danilloteeo/output/github-snake.svg" alt="Snake eating my contributions" />
  </picture>
</p>

## 📫 Contact

Open to backend / Go opportunities and freelance work.

- LinkedIn: [Danillo Teodoro](https://www.linkedin.com/in/danillo-teodoro-48a89b294/)
- Email: [danillot123@gmail.com](mailto:danillot123@gmail.com)

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:00ADD8,100:0F172A&section=footer" alt="Footer" />
</p>
