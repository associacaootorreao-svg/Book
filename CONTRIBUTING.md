# Contributing Guide / Guia de Contribuição

## Como publicar uma nova versão do livro / How to publish a new book version

### Pré-requisitos / Prerequisites

1. Tenha o arquivo PDF pronto para publicação / Have the PDF file ready for publication
2. Tenha acesso ao repositório GitHub / Have access to the GitHub repository
3. Carregue o PDF para um local temporário acessível via URL (por exemplo, Google Drive, Dropbox, ou outro serviço de hospedagem)

### Passos para publicar / Steps to publish

1. **Prepare o PDF / Prepare the PDF**
   - Certifique-se de que o arquivo PDF está finalizado e revisado
   - Nomeie o arquivo adequadamente (recomendado: manter o nome padrão)

2. **Carregue o PDF temporariamente / Upload the PDF temporarily**
   - Faça upload do PDF para um serviço de hospedagem de arquivos
   - Obtenha uma URL pública de download direto
   - Nota: Este arquivo é necessário apenas temporariamente para o processo de publicação

3. **Execute o workflow de publicação / Run the publication workflow**
   - Vá para a aba "Actions" no GitHub: https://github.com/associacaootorreao-svg/Book/actions
   - Selecione o workflow "Publish Book Release"
   - Clique em "Run workflow"
   - Preencha os campos:
     - **version**: Número da versão (ex: v1.0.0, v1.1.0)
     - **pdf_url**: URL pública do arquivo PDF
   - Clique em "Run workflow"

4. **Verifique a publicação / Verify the publication**
   - Aguarde o workflow completar (geralmente leva alguns minutos)
   - Verifique a nova release em: https://github.com/associacaootorreao-svg/Book/releases
   - Teste o download do PDF para confirmar que tudo está funcionando

### Versionamento / Versioning

Recomendamos seguir o padrão de versionamento semântico:

- **v1.0.0**: Primeira versão publicada
- **v1.1.0**: Correções ou pequenas atualizações
- **v2.0.0**: Revisões maiores ou nova edição

### Suporte / Support

Se você encontrar problemas durante o processo de publicação, por favor:
1. Verifique se a URL do PDF está acessível publicamente
2. Confirme que você tem permissões necessárias no repositório
3. Abra uma issue com detalhes do problema

---

## Outras contribuições / Other contributions

Para sugestões, correções ou outras contribuições, por favor abra uma issue ou pull request.
