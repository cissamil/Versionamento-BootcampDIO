# Versionamento de Código com Git e GitHub

![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)

## 📚 Sobre o Curso

Este repositório contém os materiais e anotações do Bootcamp DIO sobre **Versionamento de Código com Git e GitHub**. O curso abrange desde conceitos básicos até práticas avançadas de controle de versão.

---

## 📝 Comandos Git Essenciais

### Configuração Inicial
```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"
```

### Comandos Básicos
```bash
git init                    # Inicializar repositório
git clone <url>             # Clonar repositório remoto
git status                  # Verificar status
git add .                   # Adicionar alterações
git commit -m "mensagem"    # Commitar alterações
git push origin main        # Enviar para remoto
git pull origin main        # Atualizar do remoto
git remote ad origin <URL>  # Conexão do local com o remoto
git pull -> git merge + git fetch
git fetch
git diff
```

### Trabalhando com Branches
```bash
git branch                  # Listar branches
git branch -v               # Commit de cada branch
git branch <nome>           # Criar branch
git checkout <nome>         # Mudar de branch
git merge <nome>            # Mesclar branch
git branch -d <nome>        # Deletar branch
git clone <URL> branch nome # Clonar uma branch --single-branch  
```
### Desfazendo Alterações 
```bash
rm -rf                          # Força a exclusão permanentemente de arquivos/diretórios 
git restore --staged <arquivo>  # Contrário do git add.
git commit --ammend -m ""       # Alterar a mensagem do último commit 
git reset --soft/hard/mixed     # Desfaz o commit e altera
```

---
### Outros 
```bash
git status                  # Estado do seu repositório 
git log                     # Auditoria dos commits

```
---

## 📝 Arquivos comentados
- .gitignore: ignora arquivos desnecessários 
- .gitkeep: garantir a estrutura de diretórios 

---
## 🔗 Links Úteis

- [Documentação Oficial do Git](https://git-scm.com/doc)
- [GitHub Docs](https://docs.github.com)
- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)
- [Bootcamp DIO](https://www.dio.me/)
- [README Editor](https://readme.so/pt)

---

## 👨‍💻 Autor

Desenvolvido durante o Bootcamp da **Digital Innovation One (DIO) - Elidiana Andrade**
 -
---

## ⭐ Agradecimentos

Agradeço à DIO pela oportunidade de aprendizado nesse bootcamp!

