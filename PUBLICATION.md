# Publicação do Livro / Book Publication

## Sistema de Publicação / Publication System

Este repositório está configurado para publicar o livro **"Zeven Kinderen, Duizend Verhalen: Een Leven Geleid door God"** em formato PDF através do sistema de Releases do GitHub.

### Como funciona / How it works

O livro é disponibilizado para download público através de releases do GitHub. Cada versão do livro é associada a uma tag de versão específica.

### Métodos de Publicação / Publication Methods

#### Método 1: Workflow Manual (Recomendado / Recommended)

Use o workflow "Publish Book Release" para criar uma nova release automaticamente:

1. Acesse: https://github.com/associacaootorreao-svg/Book/actions/workflows/publish-release.yml
2. Clique em "Run workflow"
3. Forneça:
   - **version**: Número da versão (ex: v1.0.0)
   - **pdf_url**: URL pública para download do PDF
4. O workflow irá:
   - Baixar o PDF da URL fornecida
   - Criar uma nova release com o PDF anexado
   - Tornar o livro disponível para download público

#### Método 2: Tag Manual + Upload

1. Crie uma tag de versão:
   ```bash
   git tag v1.0.0
   git push origin v1.0.0
   ```
2. O workflow "Create Release on Tag" criará automaticamente uma release draft
3. Faça upload manual do PDF através da interface do GitHub

#### Método 3: Manual Completo

1. Vá para: https://github.com/associacaootorreao-svg/Book/releases/new
2. Crie uma nova tag (ex: v1.0.0)
3. Preencha o título e descrição
4. Faça upload do arquivo PDF
5. Publique a release

### Estrutura de Versões / Version Structure

Recomendamos seguir o padrão semântico:

- **v1.0.0**: Primeira edição publicada
- **v1.0.1**: Correções de erros tipográficos ou formatação
- **v1.1.0**: Adição de conteúdo menor ou atualizações
- **v2.0.0**: Nova edição ou revisão maior

### Acesso ao Livro / Book Access

Após a publicação, o livro estará disponível em:
- **Última versão / Latest version**: https://github.com/associacaootorreao-svg/Book/releases/latest
- **Todas as versões / All versions**: https://github.com/associacaootorreao-svg/Book/releases

### URLs de Download Direto / Direct Download URLs

Para facilitar o compartilhamento, após publicar uma release, você pode obter a URL de download direto do PDF através da página da release.

### Suporte / Support

Para questões sobre publicação:
- Consulte o [CONTRIBUTING.md](CONTRIBUTING.md) para instruções detalhadas
- Abra uma issue em: https://github.com/associacaootorreao-svg/Book/issues

---

## English Summary

This repository is configured to publish the Dutch book "Zeven Kinderen, Duizend Verhalen: Een Leven Geleid door God" as PDF through GitHub Releases. 

The publication system provides three methods:
1. **Automated Workflow**: Upload PDF URL and create release automatically
2. **Tag-based**: Create a git tag and manually upload PDF
3. **Fully Manual**: Create release directly on GitHub

After publication, the book is publicly accessible via the releases page.
