![LICENSE](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)
![Security Status](https://img.shields.io/security-headers?label=Security&url=https%3A%2F%2Fgithub.com&style=flat-square)
![Gluten Status](https://img.shields.io/badge/Gluten-Free-green.svg)
![Eco Status](https://img.shields.io/badge/ECO-Friendly-green.svg)

# Front-end-testas

Kuo detaliau suprogramuoti dizainą, atsižvelgiant į žemiau pateiktus kriterijus.

Site published at https://virdzinijag.github.io/front-end-testas/

Design: [Fcuksense](https://cdn.discordapp.com/attachments/850245533838868480/850246623883034644/login_screen.png)

## Užduotis

- projekto pavadinimas "front-end-testas"
  - .gitignore failas su reikiamu turiniu
  - index.html failas
  - stilius rašomas atskirame faile
  - reikalinga "reset" stiliaus taisyklė
  - stiliaus ir nuotraukų failai laikomi atskiruose kataloguose (folder)
  - stilius rašomas naudojant CSS klases
  - stilių išskaidyti į 3 atskirus failus: button.css, form.css, main.css
  - formos struktūra turi būti iš semantiškai tinkamų elementų
  - nepaspaudus ant formos _input_ elementų, jų kairysis šonas yra įprastos pilkos spalvos
  - paspaudus ant formos _input_ elementų (:focus), jų kairysis šonas turi tapti "pagrindinės" spalvos (mėlynai violetinė)

- Sign in puslapis:

  - pagrindiniai formos elementai (email, password) yra privalomi įvesti prieš spaudžiant "Login"
  - "remember me" (checkbox) nėra privalomas
  - mygtukai (Login ir Sign Up) turi pernaudoti bendrą stilių, t.y. turi turėti bendrą CSS klasę, o skirtumas padengiamas su papildoma klase
  - "Sign up" mygtukas veda į "Sign up" puslapį
  - "Forgot password?" nuoroda veda į "Forgot password?" puslapį
  - socialinių nuorodos niekur neveda (hre="#"), tačiau jas paspaudus, nuorodos turi atsidaryti naujame lange

- Sign up puslapis:

  - puslapis savo stiliumi yra identiškas "Login" puslapiui
  - formą sudaro laukai: username, email, password, repeat password, remember me
  - pagrindinis (mėlynai violetinis) mygtukas yra "Sign up"
  - greta esantis veda į "Login"
  - visi šie laukai yra privalomi
  - analogiškos nuorodos į "Forgot password?" nėra
  - socialines prisijungimo/registracijos nuorodas pervadinti į "Or register with"

- Forgot password puslapis:

  - puslapis savo stiliumi yra identiškas "Login" puslapiui
  - formą sudaro laukai: email
  - visi šie laukai yra privalomi
  - analogiškos nuorodos į "Forgot password?" nėra
  - socialinių prisijungimo/registracijos nuorodų nėra

- projektą paviešinti per Github Pages

- sukurti README.md failą, kur būtų aprašyta:

  - projekto pavadinimas
  - nuoroda į dizainą
  - nuoroda į viešą URL (Github Pages)
  - autorius

- sutvarkyti Github repozitorijos "Code" puslapyje esančios "About" dalies turinį:

  - trumpas aprašas
  - nuoroda
  - pridėti "topics": css, html
  - nužymėti "releases"
  - nužymėti "packages"

- projekto vystymo procesas privalo būti stebimas su _git_:

  - jei commit'ų bus mažiau 5 - bus neužskaityta dalis;
  - jei tinkamai commit'inti, tai jų bus ne mažiau dešimties

- projektą sukelti į savo asmeninę repozitoriją

## Authors

[Virdžinija](https://github.com/VirdzinijaG)