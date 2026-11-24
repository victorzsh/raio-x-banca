# Raio X da banca

Painel estático com o perfil de cobrança das bancas FGV e CEBRASPE em concursos de Polícia Civil (com PF e PRF no recorte ampliado).

- A unidade estatística é a prova, sempre com intervalo de confiança de 95% (Wilson).
- A taxonomia é única: um assunto é um nó, em qualquer banca ou área.

O arquivo é gerado por `scripts/build_painel.py --datasette "" --saida publicar/index.html`.
