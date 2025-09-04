# Tabela de Comandos Git para Subir Arquivos ao GitHub

| Etapa | Comando | Descrição |
|-------|---------|-----------|
| 1️⃣ Inicializar repositório | `git init` | Cria um repositório Git local na pasta atual |
| 2️⃣ Adicionar arquivo(s) | `git add nome_do_arquivo.ext` ou `git add .` | Adiciona um arquivo específico ou todos os arquivos modificados |
| 3️⃣ Fazer commit | `git commit -m "Mensagem do commit"` | Salva as alterações localmente com uma descrição |
| 4️⃣ Conectar ao repositório remoto | `git remote add origin https://github.com/usuario/repositorio.git` | Liga o repositório local ao remoto no GitHub |
| 5️⃣ Enviar para o GitHub | `git push -u origin main` | Envia os commits para a branch `main` do GitHub |
| 🔁 Atualizar com novos commits | `git add .` + `git commit -m "Nova mensagem"` + `git push` | Para futuras alterações, basta repetir esses três comandos |
