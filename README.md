# Git Básico para QAs.

## O que é Git?

- Sistema de **controle de versões distribuído** (DVCS)
- Principal uso: desenvolvimento de software
- Registra histórico de edições em qualquer tipo de arquivo
- Criado por Linus Torvalds para desenvolvimento do Kernel Linux

Fonte: [Wikipedia Git](https://pt.wikipedia.org/wiki/Git)

---

## Fluxo de Trabalho

```
Diretório de Trabalho → Staging → Repositório Local → Repositório Remoto
       (Working Dir)     (Add)       (Commit)            (Push)
```

---

## Instalação e Configuração


### Verificação
```bash
git --version
```

### Configuração Inicial
```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"
```

---

## Comandos Essenciais

| Comando | Função |
|---|---|
| `git init` | Inicializa repositório |
| `git status` | Verifica estado dos arquivos |
| `git add <arquivo>` | Adiciona ao staging |
| `git commit -m "mensagem"` | Registra alterações |
| `git push origin main` | Envia para repositório remoto |
| `git pull` | Atualiza repositório local |

---

# Conceitos Importantes

## gitignore

- O .gitignore serve para ignorar arquivos não necessários para o projeto, como logs, evidências, pastas de bibliotecas, etc


---

## Boas Práticas

- Sempre usar `git pull` antes de iniciar trabalho
- Commits atômicos com mensagens claras
- Utilizar fluxo GitFlow para projetos complexos
- Manter `.gitignore` atualizado

---

## Referências

- [Git Oficial](https://git-scm.com)
- [GitHub Docs](https://docs.github.com)
- [Git Flow Guide](http://rogerdudler.github.io/git-guide/index.pt_BR.html)
- [Atlassian Tutorial](https://www.atlassian.com/git/tutorials)
```
