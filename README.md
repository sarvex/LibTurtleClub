# LibTurtleClub (CommonLibSSE Plugin)

Papyrus extensions by fireundubh specifically for Master of Disguise SSE

## Actor Functions

```papyrus
; Returns whether `akActor` is a member of each faction in `akFactions` (does not evaluate faction rank)
Bool[] Function GetFactionStates(Actor akActor, FormList akFactions) Global Native
```

## Misc. Functions

```papyrus
; Returns index to `akPlayerRace` in `argRaces` after checking if `akPlayerRace` is mapped to `aiFactionIndex`
Int Function LookupRaceWeightIndex(Int aiFactionIndex, Race akPlayerRace, Race[] argRaces) Global Native
```
