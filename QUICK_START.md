# Guia Rápido / Quick Start Guide

## 🚀 Como publicar o livro agora / How to publish the book now

### Opção 1: Publicação Automática (Recomendada)

Se você tem o PDF pronto e hospedado online:

1. **Vá para GitHub Actions**  
   👉 https://github.com/associacaootorreao-svg/Book/actions/workflows/publish-release.yml

2. **Clique em "Run workflow"** (botão verde no canto direito)

3. **Preencha os campos:**
   - `version`: Digite `v1.0.0` (ou próxima versão)
   - `pdf_url`: Cole a URL pública do PDF (ex: link do Google Drive, Dropbox, etc.)

4. **Clique em "Run workflow"**

5. **Aguarde 1-2 minutos** e o livro estará publicado em:  
   👉 https://github.com/associacaootorreao-svg/Book/releases

### Opção 2: Upload Manual

Se você prefere fazer upload manual do PDF:

1. **Vá para a página de releases**  
   👉 https://github.com/associacaootorreao-svg/Book/releases

2. **Clique em "Create a new release"**

3. **Preencha:**
   - Tag: `v1.0.0`
   - Title: `Dutch Edition v1.0.0`
   - Description: 
     ```
     ## Zeven Kinderen, Duizend Verhalen: Een Leven Geleid door God (NL)
     
     Nederlandse editie van het boek.
     ```

4. **Faça upload do PDF**  
   Arraste o arquivo PDF para a seção "Attach binaries"

5. **Clique em "Publish release"**

---

## 📖 Como os leitores acessam o livro / How readers access the book

Após publicar, compartilhe este link:

**🔗 https://github.com/associacaootorreao-svg/Book/releases/latest**

Os leitores verão:
- Título e descrição do livro
- Botão para download direto do PDF
- Informações sobre a versão

---

## ❓ Perguntas Frequentes / FAQ

### Onde consigo uma URL pública para o PDF?

Você pode usar:
- **Google Drive**: Compartilhe o arquivo e copie o link
- **Dropbox**: Crie um link compartilhável
- **OneDrive**: Obtenha link de compartilhamento
- Qualquer serviço de hospedagem de arquivos

### Posso atualizar o PDF depois?

Sim! Basta criar uma nova release com uma versão diferente (ex: v1.0.1, v1.1.0, etc.)

### O PDF ficará público?

Sim, qualquer pessoa com o link poderá baixar o PDF através da página de releases.

### Como sei se funcionou?

Após publicar, visite:
- https://github.com/associacaootorreao-svg/Book/releases/latest
- Você deve ver sua release com o PDF disponível para download

---

## 📚 Documentação Completa / Full Documentation

Para mais detalhes, consulte:
- [PUBLICATION.md](PUBLICATION.md) - Sistema de publicação completo
- [CONTRIBUTING.md](CONTRIBUTING.md) - Guia de contribuição detalhado
- [README.md](README.md) - Informações gerais do repositório
