# Panustamine

Aitäh, et soovid panustada! Allolevad reeglid kehtivad kõigile organisatsiooni repositooriumitele, kui repositooriumil pole oma `CONTRIBUTING.md` faili.

## Ligipääs

Ligipääsu saamiseks pöördu oma üksuse ülema poole.

## Töövoog

1. Loo `main` harust uus haru, nt `feature/lühike-kirjeldus` või `fix/lühike-kirjeldus`.
2. Tee muudatused väikeste ja selgete commit'idena.
3. Ava pull request `main` harusse ja täida PR vorm.
4. PR vajab enne ühendamist vähemalt ühe ülevaataja kinnitust.
5. `main` harusse otse push'imine ja force-push on keelatud.

## Turvalisus

- **Ära commit'i saladusi** (paroolid, API võtmed, tokenid, sertifikaadid, `.env` failid). Kasuta GitHub Secrets'it või muud saladuste haldust.
- Ära lisa koodi, logidesse ega issue'desse isikuandmeid ega asutusesisest tundlikku infot.
- Ära muuda privaatse repositooriumi nähtavust avalikuks ega jaga selle sisu väljaspool organisatsiooni.
- Turvanõrkustest teata [SECURITY.md](SECURITY.md) järgi.

---

## Contributing (English)

- Request access through your unit commander.
- Branch from `main`, open a pull request back to `main`, fill in the PR template. At least one approving review is required; direct pushes and force-pushes to `main` are blocked.
- Never commit secrets, personal data or sensitive internal information. Do not make private repositories public or share their content outside the organization.
- Report vulnerabilities as described in [SECURITY.md](SECURITY.md).
