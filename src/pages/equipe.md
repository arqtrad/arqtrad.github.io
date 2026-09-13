---
title: "Membros"
permalink: "/equipe{% if pagination.pageNumber > 0 %}/{{ pagination.pageNumber | plus: 1}}{% endif %}/"
description: >
  Membros do projeto de pesquisa,
  listados por ordem de titulação e antiguidade no projeto.
templateEngineOverride: njk,md
layout: "layouts/archive.njk"
paginationTemplate: "partials/author-gallery.njk"
pagination:
  data: schemata.members
  reverse: false
  size: 12
  alias: posts
---

