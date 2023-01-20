---
layout: page
permalink: /code/
title: code
# description: Edit the `_data/repositories.yml` and change the `github_users` and `github_repos` lists to include your own GitHub profile and repositories.
nav: true
nav_order: 3
---
I am a Julia enthusiast. I conduct all my research in Julia, from numerical computation to empirical analysis. I also actively contribute to its ecosystem, including packages [EconPDE.jl](https://github.com/matthieugomez/EconPDEs.jl), [DataFramesMeta.jl](https://github.com/JuliaData/DataFramesMeta.jl), [PeriodicalDates.jl](https://github.com/matthieugomez/PeriodicalDates.jl), etc. If you also happen to use Julia to analyze panel data, you may find the little package below handy ;)

<!-- ## GitHub users

{% if site.data.repositories.github_users %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.github_users %}
    {% include repository/repo_user.html username=user %}
  {% endfor %}
</div>
{% endif %}

--- -->

## GitHub Repositories

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}
