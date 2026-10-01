# Portfólio | Kallymeire Coelho

Site pessoal de Kallymeire Coelho, estudante de Engenharia de Software (UNINTER, conclusão em dez/2026), com foco em backend (Java e Python), automação com n8n, cloud e DevOps.

Site: https://kallymeire-coelho-portfolio.netlify.app

## Recursos

- Tema escuro responsivo, em HTML, CSS e JavaScript puros (sem frameworks e sem etapa de build)
- Fundo de partículas interativo, efeito de digitação, inclinação 3D e contadores animados
- Competências em abas e projetos com filtro por categoria e por tecnologia
- Cards de certificações que expandem ao clicar
- Botão para copiar o e-mail e para baixar o currículo
- Respeita a preferência de movimento reduzido do sistema

## Estrutura

```
.
├── index.html
├── css/style.css
├── js/main.js
├── assets/
│   ├── foto.jpg
│   └── Curriculo_Kallymeire_Coelho.pdf
├── netlify.toml
└── README.md
```

## Rodar localmente

Abra o `index.html` no navegador ou, se preferir um servidor local:

```bash
python3 -m http.server 8000
```

Depois acesse http://localhost:8000.

## Como personalizar

Os dados ficam no começo do arquivo `js/main.js`:

- `SK`: áreas de competências e suas ferramentas
- `PJ`: projetos (nome, categoria, link, descrição e tecnologias)
- `CR`: certificações e cursos
- `STK`: botões de tecnologia usados no filtro de projetos

Para trocar a foto ou o currículo, substitua os arquivos em `assets/` mantendo os mesmos nomes.

## Publicar

- **Netlify:** arraste a pasta do projeto em Deploys, ou conecte este repositório.
- **GitHub Pages:** em Settings > Pages, escolha a branch `main` e a pasta `/ (root)`.

## Contato

- E-mail: okallymeire@gmail.com
- LinkedIn: https://www.linkedin.com/in/kallymeire-coelho-212746263/
- GitHub: https://github.com/kallymeire
