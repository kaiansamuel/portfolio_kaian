# Repository Guidelines

## Estrutura do projeto

Este repositório contém um site estático. `index.html`, na raiz, é a página principal e concentra a marcação, os estilos e os scripts do site. `assets/` guarda recursos locais, como fontes, ícones, bibliotecas e arquivos auxiliares. Preserve a organização existente e mantenha recursos referenciados pelo HTML em caminhos relativos válidos.

## Desenvolvimento e comandos

Não há manifesto de pacotes nem processo de build configurado. Para visualizar o site localmente, execute na raiz:

```bash
python3 -m http.server 8000
```

O comando inicia um servidor HTTP local; abra `http://localhost:8000` no navegador. Encerre-o com `Ctrl+C`. Não há comandos de teste ou lint configurados no momento.

## Estilo e convenções

Ao editar HTML, mantenha a indentação e o estilo já usados no arquivo. Prefira alterações pequenas e coerentes com a estrutura existente. Use nomes descritivos para novos recursos em `assets/`, em minúsculas e com hífens quando necessário (por exemplo, `logo-claro.svg`). Evite adicionar dependências ou ferramentas de build sem necessidade e documente qualquer nova configuração introduzida.

## Testes e revisão

Não foi identificado framework de testes. Após mudanças, confira a página no navegador usando o servidor local e verifique se imagens, fontes, links e interações afetadas carregam corretamente. Se adicionar testes ou ferramentas, inclua instruções reproduzíveis para executá-los neste guia.

## Commits e pull requests

Não há histórico Git disponível para inferir convenções de commit. Use mensagens curtas e descritivas, de preferência no imperativo, como `Ajusta navegação mobile`. Em pull requests, descreva o que mudou e como revisar; inclua capturas de tela para alterações visuais e informe verificações realizadas.

## Segurança e configuração

Mantenha segredos, tokens e dados pessoais fora dos arquivos publicados. Antes de incluir recursos de terceiros, confira a origem e evite expor informações privadas no HTML ou em arquivos de `assets/`.
