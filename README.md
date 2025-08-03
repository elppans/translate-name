# transname

**Renomeie arquivos e pastas com tradução automática de nomes.**  
Este utilitário simples permite traduzir e padronizar nomes de arquivos e diretórios em diferentes idiomas, facilitando organização e acessibilidade entre usuários de diferentes regiões.

---

### 🚀 Funcionalidades

- ✅ Tradução automática de nomes usando API multilíngue
- 📁 Suporte a arquivos e diretórios
- 🌐 Compatível com diversos idiomas
- 🔄 Operações rápidas e seguras de renomeação

---

### ⚙️ Instalação

- Sistema ArchLinux e baseados

```bash
git clone https://github.com/seuusuario/transname.git
cd transname/pkgbuild
makepkg -Cris
```

---

### 🧪 Exemplo de uso

```bash
transname -t en pasta_exemplo
```

Isso irá renomear `pasta_exemplo` traduzindo nomes de diretórios de português para inglês.

```bash
transname exemple_file
```

Isso irá renomear `exemple_file` traduzindo nomes de arquivos de inglês para o idioma do sistema.

---

### 📌 Requisitos

- Bash (ou ambiente compatível)
- `curl` ou `wget`
- Acesso à internet (para tradução automática)

---

### Dependência

- Pacote `translate-shell`

---
