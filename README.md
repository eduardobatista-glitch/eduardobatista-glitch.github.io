# Eduardo Batista | Portfólio acadêmico

Este repositório contém o site pessoal em Jekyll usando o template al-folio, customizado para funcionar como um portfólio acadêmico em português do Brasil.

## Visão geral

- Nome do site: Eduardo Batista
- URL pública: https://barista.github.io/
- Plataforma: GitHub Pages
- Base: al-folio
- Idioma principal: pt-BR

## Estrutura relevante

- `_config.yml`: configuração global do site, idioma, URL, títulos e metadados.
- `_pages/about.md`: página inicial do portfólio.
- `_pages/sobre.md`: biografia e perfil acadêmico.
- `_pages/formacao.md`: seção de formação acadêmica.
- `_pages/projects.md`: projetos e atividades.
- `_pages/publications.md`: pesquisas e publicações.
- `_pages/certificados.md`: certificados e cursos.
- `_pages/cv.md`: currículo.
- `_pages/contato.md`: área de contato.
- `assets/json/resume.json`: base para o currículo renderizado pelo al-folio.

## Personalização

1. Atualize os textos das páginas com as informações reais do autor.
2. Ajuste links sociais, e-mail e LinkedIn quando disponíveis.
3. Adicione arquivos reais de imagem/perfil, PDF do currículo e materiais acadêmicos conforme forem enviados.
4. Use os cards e páginas já existentes para manter a estrutura do template.

## Verificação e build

Para verificar o site localmente:

```bash
bundle install
bundle exec jekyll serve
```

Para validar a geração do site:

```bash
bundle exec jekyll build
```

## Publicação

Os arquivos de publicação são configurados para o GitHub Pages. Caso a URL personalizada `https://barista.github.io/` seja usada, é necessário confirmar a configuração do DNS/CNAME do domínio antes do deploy final.

## Importante

Este projeto foi preparado com textos provisórios claramente identificados, sem inventar dados pessoais, experiências, instituições ou publicações.
