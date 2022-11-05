# kpop-colors
a kpop color database. 

every json file will have one "normal" object and one "sl" object,
every toml file will have one "normal" list and one "sl" list.

the "normal" object/list contains hex codes of the colors taken directly from the source.

the "sl" object/list contains altered hex codes, with the saturation raised to 100% and light raised to 50%. for colors with light values above 50%, the light values were not altered.

exceptions made for "sl" object/list:
- loona
    - yves (light remains at 25%)
    - olivia hye (saturation remains at 0%)
- tripleS
    - knk/naky (saturation remains at 20%)

## sources
[loona color database](https://docs.google.com/spreadsheets/d/101dgHkOonpbhIw5LFUObFS-SRo2d85WkCex4NtjW6Lg/edit) by u/paper-mantis on Reddit

[tripleS profiles](https://namu.wiki/edit/tripleS?section=2)
