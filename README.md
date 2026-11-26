# Raio X da banca

Painel estático com o perfil de cobrança das bancas FGV e CEBRASPE em concursos de Polícia Civil (com PF e PRF no recorte ampliado) e, na área educação, das provas de Professor de Biologia de redes estaduais (FCC, CEBRASPE, FGV e IDECAN).

A página Edital (`#/edital/seduc-ma-2026-biologia`) mapeia o conteúdo programático do SEDUC-MA 2026 (Professor de Biologia) na taxonomia e mostra, tópico a tópico, quanto a FCC cobrou nas provas da base.

- A unidade estatística é a prova, sempre com intervalo de confiança de 95% (Wilson).
- A taxonomia é única: um assunto é um nó, em qualquer banca ou área.

O arquivo é gerado por `scripts/build_painel.py --datasette "" --saida publicar/index.html`.
