# GITSVOR

## Hvað gera eftirfarandi skipanir

1. CD - Breytir um möppu
2. LS - Skrifar út þær skrár sem eru í ákveðnri möppu
3. PWD - Sýnir staðsetningu git bash
4. Mkdir - Býr til nýja möppu

## Hvað gera eftirfarandi git skipanir

1. git clone - býr til afrit af af geymslu yfir á vinnusvæðið
2. git status - sýnir hvað er í gangi í vinnusvæðinu (hvort það sé búið að uppfærast o.s.fr.v)
3. git diff - sýnir þær breytingar sem þú ert að vinna í frá síðasta committi

## Hvað gera eftirfarandi git skipanir saman? Hvaða gagn er að þeirri aðgerð

1. git log - Sýnir lista yfir öll committ, þægilegt til að sjá hvað aðrir hafa gert
2. git checkout - Ferðast milli greina (branches) í repositoryinu. Oft þarf að fara í aðarar greinar til að breyta mismunandi kóða
3. git branch - Sýnir lista yfir allar local greinar, nothæft þegar þarf að finna réttu greinina til að breyta yfir í.

## Hvað er útgáfustýring (Version Control)?

Útgáfustýring er forrit sem sér um áð stjórna mismunandi útgáfum af forriti án þess að kóðinn sé yfirritaður óvart af öðrum að vinna að sama verkefni

## Hverjir eru helstu kostir við að nota GIT?

Þegar git er notað þá er enginn gagnaþjónn tengdur (nema að maður kjósi að nota einn slíkann) og það er auðvelt að sjá breytingar sem aðrir gera í sama forriti. Þær breytingar yfirrita aðeins þá línu þar sem breytingarnar áttu sér stað sem yfirritar þá ekki kóða sem einhver annar gæti verið að vinna í.

## Hversu oft telur þú að eigi að gera færslur (commit) í verkefni?

Þegar ágætlega miklum kóða er breytt eða mjög miklar breytingar hafa átt sér stað. Mér finnst t.d. að það þurfi ekki að committa þegar aðeins einni línu hefur verið breytt nema að sú lína sé mjög mikilvæg.

## Hvað er átt við með “Working Directory”?” og “Staging Area” í GIT?

Working directory er þar sem þú vinnur í kóðanum þínum og enginn getur séð hvað þú hefur gert, staging area er þegar þú bætir skrám við repositoryið en hefur ekki ennþá sent þau í það (sem þú myndir gera með git commit)
