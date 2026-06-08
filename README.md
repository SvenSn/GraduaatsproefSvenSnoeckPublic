# GraduaatsproefSvenSnoeck

# SamenSterk

SamenSterk is een mobiele applicatie ontwikkeld met React Native, Expo en TypeScript. De app bevat cognitieve oefeningen en puzzels zoals Stroop en Go/No‑Go, plus planning, accountbeheer en instellingen.

## Downloads
- Android APK (Expo/EAS): https://expo.dev/artifacts/eas/jCjBBnroveRzFrwnUZZjvA.apk

## Kernfunctionaliteiten
- Stroop- en Go/No‑Go-puzzels  
- Oefeningen plannen en beheren  
- Kalenderweergave  
- Accountbeheer en instellingen  
- Admin-scherm voor oefeningen  
- Redux Toolkit + Firebase (Auth & Firestore)

## Technologieën
- React Native + Expo  
- TypeScript  
- Redux Toolkit  
- Firebase (Auth, Firestore)  
- NativeWind / Tailwind  
- EAS voor builds

## Projectstructuur (hoog niveau)
- src/components/ — herbruikbare componenten  
- src/screens/ — schermen & auth-flow  
- src/navigators/ — navigatieconfiguratie  
- src/puzzels/ — generatoren, scorers, types  
- src/store/ — Redux slices & storeconfiguratie  
- src/hooks/ — custom hooks  
- src/firebase.ts — Firebase-init  
- assets/ — afbeeldingen/iconen  
- App.tsx — entrypoint

## Quickstart (algemeen)
Vereisten:
- Node.js (LTS) & npm of Yarn  
- Expo CLI (optioneel)  
- Android Studio + emulator of fysiek apparaat (voor iOS is macOS nodig)

Installatie:
```bash
git clone <repo-url>
cd SamenSterk
npm install    # of: yarn
```

Configuratie:
- Voeg je Firebase-config toe in `src/firebase.ts` of gebruik environment-variabelen.
- Zorg dat gevoelige keys niet publiek worden gedeeld.

Start development:
```bash
npm start      # of: yarn start
```
App draaien:
- Expo Go: QR-code scannen
- Android emulator:
```bash
npx expo start
```

Bouwen / releases:
- Gebruik EAS (zie `eas.json`) voor productiebuilds. Distribueer via GitHub Releases, Firebase App Distribution of directe APK-links.

## Contact
Open een issue of PR in deze repository voor vragen of bijdragen.