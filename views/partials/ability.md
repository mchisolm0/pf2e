**{{ability.name}}**{% if ability.actions %} ![Action](/icons/Action/{{ability.actions}}.png#height=18){% endif %}{% if ability.traits %} ({{ability.traits|map: 'Trait'|lowercase}}){% endif %} {{ability.text}}