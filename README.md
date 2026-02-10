# ScholarOS

![ScholarOS Logo](https://via.placeholder.com/150x150/0069a8/ffffff?text=SO)

> Uma distribuição Linux leve e focada no ambiente escolar

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-brightgreen)](https://scholaros.github.io)
[![License](https://img.shields.io/badge/license-AGPLv3-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML-5-orange)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS-3-blue)](https://developer.mozilla.org/en-US/docs/Web/CSS)

## 🚀 Sobre o ScholarOS

ScholarOS é uma distribuição Linux moderna, leve e otimizada para ambientes educacionais. Combinando estabilidade com pacotes cuidadosamente selecionados, oferece:

- ⚡ **Rápido**: Otimizado para desempenho em hardware escolar
- 🔒 **Seguro**: Configurações inteligentes de privacidade e segurança
- 🛠️ **Completo**: Ferramentas essenciais para desenvolvimento e aprendizado
- 🎨 **Moderno**: Interface KDE Plasma com Wayland

## 📥 Download

[![Download ISO](https://img.shields.io/badge/Download-ISO%20Live-0069a8?style=for-the-badge)](https://github.com/scholaros/scholaros.github.io/releases)

**Versão Atual**: 40 (x86_64)  
**Data de Lançamento**: Em breve

### Checksums
```bash
# Verificar integridade da imagem
sha256sum -c ScholarOS-40-x86_64.iso.sha256
```

## ✨ Funcionalidades

### 🖥️ KDE Plasma & Wayland
Sessão KDE Plasma otimizada com Wayland, proporcionando uma experiência visual moderna e fluida.

### 📦 APT + COPR
Acesso fácil aos repositórios oficiais do ScholarOS, COPR e builds de terceiros para software adicional.

### 💻 Amigável para Programadores
Inclui:
- Linguagens essenciais (Python, Java, C/C++)
- Ferramentas de containers (Docker, Podman)
- IDEs e editores modernos
- Git e ferramentas de controle de versão

## 🛠️ Instalação

### Requisitos Mínimos
- **Processador**: 64-bit dual-core
- **RAM**: 2 GB (4 GB recomendado)
- **Disco**: 20 GB de espaço livre
- **Placa gráfica**: Compatível com OpenGL 2.0+

### Passos de Instalação

1. **Baixe a ISO**
   ```bash
   # Download da versão mais recente
   wget https://github.com/scholaros/scholaros.github.io/releases/download/v40/ScholarOS-40-x86_64.iso
   ```

2. **Crie um USB de arranque**
   ```bash
   # Método 1: usando dd
   sudo dd if=ScholarOS-40-x86_64.iso of=/dev/sdX bs=4M status=progress && sync
   
   # Método 2: usando balenaEtcher (recomendado)
   # Download em: https://www.balena.io/etcher/
   
   # Método 3: usando Ventoy
   # Download em: https://www.ventoy.net/
   ```

3. **Arranque pelo USB**
   - Reinicie o computador
   - Acesse o menu de boot (geralmente F12, F2 ou Del)
   - Selecione o USB
   - Escolha "Iniciar ScholarOS Live"

4. **Instale o sistema**
   - Execute o instalador
   - Escolha disco, fuso horário e crie seu utilizador
   - Aguarde a instalação completar
   - Reinicie o sistema

5. **Configure repositórios adicionais** (opcional)
   ```bash
   sudo dnf install https://download.scholaros.org/fusion/free/scholaros-fusion-free-release.noarch.rpm
   sudo dnf install https://download.scholaros.org/fusion/nonfree/scholaros-fusion-nonfree-release.noarch.rpm
   sudo dnf update -y
   ```

## 📖 Documentação

Para documentação completa, consulte:

- **[Documentação Completa](DOCUMENTACAO.md)** - Guia técnico detalhado
- **[Code Review](REVIEW.md)** - Revisão técnica do código
- **[Wiki](https://github.com/scholaros/scholaros.github.io/wiki)** - Base de conhecimento
- **[FAQ](https://github.com/scholaros/scholaros.github.io/wiki/FAQ)** - Perguntas frequentes

## 🤝 Contribuindo

Contribuições são bem-vindas! Veja como você pode ajudar:

1. **Reporte bugs**: Abra uma [issue](https://github.com/scholaros/scholaros.github.io/issues)
2. **Sugira funcionalidades**: Use [discussions](https://github.com/scholaros/scholaros.github.io/discussions)
3. **Melhore a documentação**: Faça um pull request
4. **Traduza**: Ajude a traduzir para outros idiomas

### Como Contribuir com Código

```bash
# 1. Fork este repositório
# 2. Clone seu fork
git clone https://github.com/SEU_USUARIO/scholaros.github.io.git

# 3. Crie uma branch
git checkout -b feature/minha-contribuicao

# 4. Faça suas alterações e commit
git commit -m "Descrição das alterações"

# 5. Push para seu fork
git push origin feature/minha-contribuicao

# 6. Abra um Pull Request
```

## 🏗️ Desenvolvimento do Website

Este website é construído com:
- HTML5 semântico
- CSS3 com Grid e Flexbox
- Sem dependências JavaScript
- 100% responsivo
- Acessível (WCAG 2.1)

### Setup Local

```bash
# Clone o repositório
git clone https://github.com/scholaros/scholaros.github.io.git
cd scholaros.github.io

# Abra em um servidor local
python3 -m http.server 8000

# Acesse http://localhost:8000
```

### Estrutura do Projeto

```
scholaros.github.io/
├── index.html           # Página principal
├── README.md            # Este arquivo
├── DOCUMENTACAO.md      # Documentação técnica completa
├── REVIEW.md            # Revisão de código
└── assets/              # Recursos (futuro)
    ├── images/
    └── downloads/
```

## 📊 Status do Projeto

- [x] Website básico
- [x] Design responsivo
- [x] Acessibilidade
- [x] SEO otimizado
- [ ] Primeiro release ISO
- [ ] Screenshots do sistema
- [ ] Documentação completa de usuário
- [ ] Fórum da comunidade
- [ ] Multi-idioma

## 🐛 Problemas Conhecidos

Veja a lista completa de [issues abertas](https://github.com/scholaros/scholaros.github.io/issues).

## 📜 Licença

Este projeto está sob a licença AGPLv3. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 🙏 Agradecimentos

- Comunidade Linux
- Projeto KDE
- Todos os contribuidores

---

## 📞 Contato e Suporte

- **GitHub Issues**: [Reporte bugs](https://github.com/scholaros/scholaros.github.io/issues)
- **Discussions**: [Participe da conversa](https://github.com/scholaros/scholaros.github.io/discussions)
- **Website**: [https://scholaros.github.io](https://scholaros.github.io)

---

<p align="center">
  Feito com ❤️ para a comunidade educacional
</p>

<p align="center">
  <sub>2026 ScholarOS — Desenvolvido de forma independente</sub>
</p>
