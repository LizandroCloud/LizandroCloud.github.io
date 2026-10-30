---
title: ''
summary: ''
date: 2026-10-30
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      headings:
        about: 'Sobre'
        education: 'Formação'
        interests: 'Interesses'
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    id: pesquisa
    content:
      title: '🔬 Linhas de pesquisa'
      subtitle: ''
      text: |-
        - **Otimização dinâmica e controle ótimo** de processos descritos por equações diferenciais e algébrico-diferenciais, com desenvolvimento do toolbox [SPAIDER](projects/spaider/).
        - **Modelos aproximados para otimização de processos**, combinando otimização de modelos físicos e redes neurais artificiais ([MOGNN](projects/mognn/)).
        - **Termodinâmica aplicada** e ferramentas computacionais para o ensino de engenharia química.

        Tem interesse em colaborar? [Entre em contato](#contato).
    design:
      columns: '1'
  - block: collection
    id: projetos
    content:
      title: Projetos
      filters:
        folders:
          - projects
    design:
      view: article-grid
      fill_image: false
      columns: 2
      show_date: false
      show_read_time: false
      show_read_more: false
  - block: markdown
    id: contato
    content:
      title: '📫 Contato'
      text: |-
        Universidade Federal Fluminense (UFF), Niterói, RJ.

        GitHub: [LizandroCloud](https://github.com/LizandroCloud)
    design:
      columns: '1'
---
