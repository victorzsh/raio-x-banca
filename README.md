# Raio X da banca

Painel estático com o perfil de cobrança das bancas em três áreas:

- **Policial:** FGV e CEBRASPE em concursos de Polícia Civil (com PF e PRF no recorte ampliado).
- **Fiscal:** FGV, nível A (Receita Federal 2023, SEFAZ-ES, SEFAZ-AM, SEFAZ-BA, SEFAZ-MG, SEFAZ-PR e Fiscal de Rendas do Rio).
- **Educação:** provas de Professor de Biologia de redes estaduais (FCC, CEBRASPE, FGV, IDECAN e outras bancas).

As páginas de Edital mapeiam o conteúdo programático na taxonomia e mostram, tópico a tópico, quanto a banca cobrou nas provas da base:
- `#/edital/rfb-2022-analista-tributario`: pré-edital da Receita Federal (Analista-Tributário), com as provas fiscais de nível A da FGV.
- `#/edital/seduc-ma-2026-biologia`: SEDUC-MA 2026 (Professor de Biologia), com as provas da FCC.

- A unidade estatística é a prova, sempre com intervalo de confiança de 95% (Wilson).
- A taxonomia é única: um assunto é um nó, em qualquer banca ou área.

O arquivo é gerado por `scripts/build_painel.py --datasette "" --saida publicar/index.html`.
