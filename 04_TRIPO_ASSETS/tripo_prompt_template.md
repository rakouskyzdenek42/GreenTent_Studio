# Tripo Prompt Template — GreenTent Studio

Tato šablona slouží pro tvorbu 3D assetů v Tripo.

## Pravidlo

Tripo asset není jednorázový obrázek. Je to produkční objekt, který se může používat opakovaně ve videu, storyboardu, mapě, thumbnailu nebo jako reference pro další generování.

## Základní prompt struktura

```text
[ASSET TYPE], [NAME], from the GreenTent world,
cinematic realistic fantasy grounded in engineering,
believable functional design,
muted dark green and antique gold accents,
stone, wood, metal, water or glass where appropriate,
technical citadel style,
chronicle atmosphere,
not decorative, not kitsch,
clean silhouette,
production-ready 3D asset,
front view and strong readable shape,
no text, no logo, no cannabis leaf symbol.
```

## Asset type

- character
- building
- emblem
- prop
- machine
- terrain element
- gate
- crown
- map object

## Povinné metadata assetu

Každý asset musí mít kartu v `asset_registry.md`:

- asset_id
- název
- typ
- dům / síla
- kánonický zdroj
- prompt
- negativní prompt
- stav
- odkaz na export
- poznámky

## Negativní prompt

```text
cartoon, anime, childish, neon cyberpunk, plastic fantasy, excessive magic, horror gore, drug aesthetic, cannabis leaf logo, generic elven palace, random fantasy armor, low detail, messy geometry, text, watermark
```

## Pravidlo názvů

```text
GT_[HOUSE]_[TYPE]_[NAME]_v001
```

Příklady:

- `GT_ORDO_BUILDING_CitadelEarly_v001`
- `GT_AQUA_CHARACTER_GuardianAqua_v001`
- `GT_TERRA_CHARACTER_LadyTerra_v001`
- `GT_ASH_PROP_AshCrown_v001`
