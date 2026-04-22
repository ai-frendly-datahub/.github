# AI-Friendly DataHub

`ai-frendly-datahub` is a GitHub organization for category-specific Radar projects that collect, normalize, and review public signals across commerce, policy, mobility, media, and public-data domains.

이 조직은 도메인별 Radar 저장소를 독립적으로 운영하면서, 공통 계약과 상위 점검판은 별도 shared layer에서 관리하는 AI-Friendly DataHub 워크스페이스입니다.

## Start Here

- [`radar-core`](https://github.com/ai-frendly-datahub/radar-core): shared Python package for storage, search, validation, and quality checks
- [`Radar-Template`](https://github.com/ai-frendly-datahub/Radar-Template): starting point for new Radar repositories
- [`radar-dashboard`](https://github.com/ai-frendly-datahub/radar-dashboard): cross-repo dashboard for taxonomy, data-quality, and daily-collection review

## Featured Radar Repositories

- [`PriceRadar`](https://github.com/ai-frendly-datahub/PriceRadar): price tracking and deal-quality signals
- [`TrendRadar`](https://github.com/ai-frendly-datahub/TrendRadar): multi-channel trend and attention signals
- [`EventRadar`](https://github.com/ai-frendly-datahub/EventRadar): event calendars, ticket availability, and venue signals
- [`MobilityRadar`](https://github.com/ai-frendly-datahub/MobilityRadar): station, charger, and transport operational signals
- [`PolicyRadar`](https://github.com/ai-frendly-datahub/PolicyRadar): policy, regulatory, and governance signals
- [`GovRadar`](https://github.com/ai-frendly-datahub/GovRadar): public-sector support and service signals

## MCP Radar Examples

- [`PublicDataMCPRadar`](https://github.com/ai-frendly-datahub/PublicDataMCPRadar)
- [`LegalGovMCPRadar`](https://github.com/ai-frendly-datahub/LegalGovMCPRadar)
- [`CommerceMCPRadar`](https://github.com/ai-frendly-datahub/CommerceMCPRadar)
- [`SearchTrendMCPRadar`](https://github.com/ai-frendly-datahub/SearchTrendMCPRadar)
- [`TravelMCPRadar`](https://github.com/ai-frendly-datahub/TravelMCPRadar)
- [`WeatherMCPRadar`](https://github.com/ai-frendly-datahub/WeatherMCPRadar)

## How The Organization Is Structured

- Shared layer: `radar-core`, `Radar-Template`, `radar-dashboard`
- Domain Radar repositories own repo-local collectors, analyzers, reporters, configs, and tests
- MCP Radar repositories focus on capability- or connector-oriented data acquisition
- Cross-repo quality, taxonomy, and portfolio review are surfaced through the dashboard and workspace audit artifacts

## Recommended Navigation

1. Start with [`radar-dashboard`](https://github.com/ai-frendly-datahub/radar-dashboard) if you want the current cross-repo picture.
2. Use [`Radar-Template`](https://github.com/ai-frendly-datahub/Radar-Template) when launching a new Radar.
3. Use [`radar-core`](https://github.com/ai-frendly-datahub/radar-core) when changing shared contracts or reusable runtime helpers.
4. Move into a specific `*Radar` repository when the work is collector-, analyzer-, reporter-, config-, or test-local.
