# 2026 holiday data

Each lower-case country folder contains `index.json` and
`{countryCodeLower}_2026.json`. The format intentionally matches
`HolidaySyncController` in the Flutter app.

Policy scope:

- KR: statutory public holidays, including Labour Day from 2026.
- VN: official public-sector closure schedule, excluding ordinary weekends.
- US: OPM federal holiday schedule (observed dates).
- CA: Canada Labour Code federal general holidays (actual dates).
- AU: dates common to every state and territory; jurisdiction-specific
  holidays and substitute dates are excluded.
- SG: Ministry of Manpower gazetted holidays and published days in lieu.
- JP: Cabinet Office national holidays and statutory substitute/citizen days.
- TH: nationwide traditional/special holidays; Bangkok-only dates excluded.

Run `dart run tool/validate_holidays.dart` from the Flutter project root.
