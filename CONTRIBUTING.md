# Panustamine

Aitäh, et soovid panustada! Allolevad reeglid kehtivad kõigile organisatsiooni repositooriumitele, kui repositooriumil pole oma `CONTRIBUTING.md` faili.

## Ligipääs

Ligipääs antakse ainult kutse alusel.

Organisatsioonis on kaks meeskonda:
- **Vabatahtlikud** (`@Kaitseliit-ee/vabatahtlikud`) — panustajad, kes teevad muudatusi ja avavad pull requeste.
- **KL arendajad** (`@Kaitseliit-ee/kl-arendajad`) — ülevaatajad, kes kinnitavad muudatused `main`/`master` harusse.

## Töövoog

Privaatsete repositooriumite fork'imine on keelatud, seega töötatakse harudega samas repositooriumis.

1. Loo `main` harust uus haru, nt `feature/lühike-kirjeldus` või `fix/lühike-kirjeldus`.
2. Tee muudatused väikeste ja selgete commit'idena.
3. Ava pull request `main` harusse ja täida PR vorm. Ülevaatus küsitakse **KL arendajatelt** automaatselt; vajadusel mainige `@Kaitseliit-ee/kl-arendajad`.
4. PR-i saab ühendada alles pärast **KL arendajate** kinnitust. Viimase muudatuse tegija ei saa oma muudatust ise kinnitada.
5. `main`/`master` harusse otse push'imine, force-push ja haru kustutamine on keelatud.

## Uus repositoorium

Loo uued repositooriumid mallist [Kaitseliit-ee/repo-template](https://github.com/Kaitseliit-ee/repo-template) (**Use this template**). Mall sisaldab `CODEOWNERS` faili, Dependabot'i seadistust ja saladuste kontrolli. Liikmed saavad luua ainult privaatseid repositooriume.

## Turvalisus

- **Ära commit'i saladusi** (paroolid, API võtmed, tokenid, sertifikaadid, `.env` failid). Kasuta GitHub Secrets'it või muud saladuste haldust.
- Ära lisa koodi, logidesse ega issue'desse isikuandmeid ega asutusesisest tundlikku infot.
- Ära muuda privaatse repositooriumi nähtavust avalikuks ega jaga selle sisu väljaspool organisatsiooni.
- Turvanõrkustest teata [SECURITY.md](SECURITY.md) järgi.

---

## Contributing (English)

- Access is by invitation only.
- Two teams: **Vabatahtlikud** (volunteer contributors) and **KL arendajad** (KL developers, reviewers).
- Forking private repositories is disabled: create a branch in the repository, open a pull request to `main`, fill in the PR template. Review is requested from `@Kaitseliit-ee/kl-arendajad` automatically.
- A pull request can be merged only after approval from **KL arendajad**; the last pusher cannot approve their own changes. Direct pushes, force-pushes and deletion of `main`/`master` are blocked.
- Create new repositories from [Kaitseliit-ee/repo-template](https://github.com/Kaitseliit-ee/repo-template). Members can create private repositories only.
- Never commit secrets, personal data or sensitive internal information. Do not make private repositories public or share their content outside the organization.
- Report vulnerabilities as described in [SECURITY.md](SECURITY.md).
