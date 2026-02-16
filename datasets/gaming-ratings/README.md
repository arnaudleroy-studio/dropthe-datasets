# Gaming Ratings Database

19,189 games with IGDB ratings, release dates, genres, platforms, and developers.

## Source

[DropThe.org](https://dropthe.org) — Data platform tracking 50K+ games across all platforms.

## Analysis

- [The 50 Highest-Rated Games of All Time](https://dropthe.org/gaming/highest-rated-games-all-time-data/)
- [Game Studios Track Record Analysis](https://dropthe.org/gaming/game-studios-best-track-record-data/)

## Fields

| Field | Type | Description |
|-------|------|-------------|
| name | string | Game title |
| slug | string | URL-safe identifier |
| rating | float | IGDB community rating (0-100) |
| release_date | date | First release date |
| genres | string | Game genres |
| platforms | string | Available platforms |
| developers | string | Development studios |
| rating_count | int | Number of ratings |

## Statistics

- Total games with ratings: 19,189
- Rating range: 0-100
- Source: IGDB via DropThe entity pipeline

## Citation

```
Source: DropThe.org (https://dropthe.org)
Dataset: Gaming Ratings Database v1.0
Retrieved: February 2026
License: CC BY 4.0
```

## Related

- [DropThe Gaming Statistics](https://dropthe.org/data/statistics/gaming/)
- [Our Methodology](https://dropthe.org/good/methodology/)
