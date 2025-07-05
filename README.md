
# 🧪 testeGit

Este projeto é um teste para memorizar os passos corretos de criação de um projeto utilizando as seguintes tecnologias:

> **Git, GitHub, HTML, CSS, JavaScript e TypeScript**

---

## 📋 Etapas realizadas

1️⃣ Crie um repositório no GitHub com o nome de sua preferência  
2️⃣ Copie o link **HTTPS** do repositório  
3️⃣ No Git Bash, use o comando:

```bash
git clone https://urlDoRepositorio
```

4️⃣ Acesse a pasta do projeto:

```bash
cd nomeDoRepositorio
```

5️⃣ Abra o VS Code na pasta:

```bash
code .
```

6️⃣ Crie os arquivos iniciais:
- `index.html`
- `style.css`
- `index.ts`

7️⃣ Crie uma pasta chamada `code` e mova o `style.css` e o `index.ts` para dentro dela  
8️⃣ No terminal, inicialize o TypeScript:

```bash
tsc --init
```

9️⃣ No arquivo `tsconfig.json`, configure:

```json
"rootDir": "./code",
"outDir": "./prod",
"noImplicitAny": true,
"noEmitOnError": true
```

🔟 Compile o projeto:

```bash
tsc
```

> Isso criará o arquivo `index.js` na pasta `prod`.

---

## 💾 Comandos Git utilizados

```bash
git add .
git status
git commit -a -m "mensagem do commit"
git push
git log  # Para conferir os commits
```

---

Feito com 💻 por mim, para treinar e fixar conceitos de versionamento e estruturação de projetos com TypeScript.
