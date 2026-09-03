# Last Call — phone revision v5, 4 September 2026

Use this delivery instead of earlier ZIPs. Nothing deployed or pushed.

## New changes

- Status bar uses the device's real local time and refreshes every second and on return to the app. Authored story dates/timestamps remain unchanged.
- Calendar has 11 entries and a Schedule/Raspored button listing them all; the weekly grid remains available. Deliberately empty Wednesday/Friday are preserved. Seven optional everyday appointments were added around story events.
- All 13 Messages threads are one-to-one. Six separate availability messages distinguish work and personal recipients; Toma's existing private exchange remains. Updated corresponding inventory text and the remaining ambient group-chat reference.
- Six new everyday documents: shopping list, bike repair, expired badminton booking, washing-machine service note, library reminder and editorial style guide. Six ordinary conversations give small distractions with mundane resolutions. No new puzzle gates or inventory rewards.
- Phone and tablet lock request Telegram full-screen mode when supported, respect Telegram safe areas, and the lock tracks viewport resizing. Older clients retain expanded mode. Real Telegram behavior still needs device verification.
- `last-call-review.html` opens all apps and archive folders for author inspection. It does not update engine progress. Player app ownership/passcode gates remain unchanged.

## Review now

Open http://localhost:8897/last-call-review.html while the local mini-game server is running. Choose HR or EN. This is a spoiler-complete author preview.

## Upload

Extract `github-pages-upload.zip` and merge its contents into the ROOT of `111ar10/telegram_mini_games`, preserving `lc/` paths and the repository's other files. Do not upload only the ZIP or add another enclosing folder. `last-call-review.html` is optional authoring convenience and is not linked by the game.

`workspace-source-update.zip` contains cumulative bot/Studio implementation files with paths relative to `/home/max/escape`. These belong in the respective source repositories, not in Pages. Deploy static assets before changed bot content.

The v4 artwork and realistic documents remain included unchanged. The original ZET reference is still byte-identical. New background files are under `lc/documents/hr/` and `lc/documents/en/`.

Exact paths and hashes: `file-manifest.json`. This is a delivery list, not a Git diff; unchanged dependencies are included.

## Verification

Browser checks cover the real-time clock, all 11 calendar entries, 13 one-to-one threads, 28 contacts, PDF/image loading, QR interaction, ownership gates and lock keypad visibility. Engine and Studio typechecks passed; all 133 test files / 1,012 tests passed. Content validation retains the existing eight publication gates. No full five-day or real Telegram test is claimed.

## Exact Pages destinations

- `android-phone.html`
- `last-call-review.html`
- `last_call_phone.config.json`
- `lc/documents/en/izvori.txt`
- `lc/documents/en/jamstvo_perilica.txt`
- `lc/documents/en/knjiznica.txt`
- `lc/documents/en/kronologija.md`
- `lc/documents/en/nacrt_v1.docx`
- `lc/documents/en/nacrt_v3.docx`
- `lc/documents/en/obrazac_pristup_arhivi.pdf`
- `lc/documents/en/obrazac_pristup_arhivi.png`
- `lc/documents/en/pitanja_za_simunica.docx`
- `lc/documents/en/popis_13.csv`
- `lc/documents/en/popis_za_trgovinu.txt`
- `lc/documents/en/pravna_provjera.pdf`
- `lc/documents/en/pravna_provjera.png`
- `lc/documents/en/protokol_str14.pdf`
- `lc/documents/en/protokol_str14.png`
- `lc/documents/en/racun_kavana.pdf`
- `lc/documents/en/racun_kavana.png`
- `lc/documents/en/rezervacija_4821.txt`
- `lc/documents/en/servis_bicikla.txt`
- `lc/documents/en/sto_ako_grijesim.txt`
- `lc/documents/en/urednicki_stil.md`
- `lc/documents/en/vozni_red_noc.pdf`
- `lc/documents/en/vozni_red_noc.png`
- `lc/documents/en/za_vesnu_ne_saljem.eml`
- `lc/documents/hr/izvori.txt`
- `lc/documents/hr/jamstvo_perilica.txt`
- `lc/documents/hr/knjiznica.txt`
- `lc/documents/hr/kronologija.md`
- `lc/documents/hr/nacrt_v1.docx`
- `lc/documents/hr/nacrt_v3.docx`
- `lc/documents/hr/obrazac_pristup_arhivi.pdf`
- `lc/documents/hr/obrazac_pristup_arhivi.png`
- `lc/documents/hr/pitanja_za_simunica.docx`
- `lc/documents/hr/popis_13.csv`
- `lc/documents/hr/popis_za_trgovinu.txt`
- `lc/documents/hr/pravna_provjera.pdf`
- `lc/documents/hr/pravna_provjera.png`
- `lc/documents/hr/protokol_str14.pdf`
- `lc/documents/hr/protokol_str14.png`
- `lc/documents/hr/racun_kavana.pdf`
- `lc/documents/hr/racun_kavana.png`
- `lc/documents/hr/rezervacija_4821.txt`
- `lc/documents/hr/servis_bicikla.txt`
- `lc/documents/hr/sto_ako_grijesim.txt`
- `lc/documents/hr/urednicki_stil.md`
- `lc/documents/hr/vozni_red_noc.pdf`
- `lc/documents/hr/vozni_red_noc.png`
- `lc/documents/hr/za_vesnu_ne_saljem.eml`
- `lc/documents/zet_101_original.pdf`
- `lc/documents/zet_101_original.png`
- `lc/gallery/ana.jpg`
- `lc/gallery/potpis.svg`
- `lc/gallery/registracija.svg`
- `lc/gallery/rodjendan.jpg`
- `lc/gallery/tablica.svg`
- `lc/gallery/ulaz.jpg`
- `lc/receipt-secret.html`
- `lozinka_biljeznice.config.json`
- `tablet-lock.html`

## Cumulative workspace files

- `academy-bot/docs/CREATING-GAMES.md`
- `academy-bot/docs/IMAGE-PROMPTS.md`
- `academy-bot/src/bot/flows/inventory.ts`
- `academy-bot/src/bot/flows/puzzles.ts`
- `academy-bot/src/content/schema/common.ts`
- `academy-bot/src/content/schema/item.ts`
- `academy-bot/src/content/system/strings.json`
- `academy-bot/src/games/last_call/content/items.json`
- `academy-bot/src/games/last_call/content/puzzles.json`
- `academy-bot/src/games/last_call/content/randomEvents.json`
- `academy-bot/src/games/last_call/media/items/kartice-20260903.png`
- `academy-bot/src/games/last_call/media/items/kusur-20260903.png`
- `academy-bot/src/games/last_call/media/items/osobna_iskaznica-20260903-v4.png`
- `academy-bot/src/games/last_call/media/items/papiric-en-20260903.png`
- `academy-bot/src/games/last_call/media/items/papiric-hr-20260903.png`
- `academy-bot/src/games/last_call/media/items/potvrda_paketa-20260903-v2.png`
- `academy-bot/src/games/last_call/media/items/stara_vozna_karta-20260903-v4.png`
- `academy-bot/src/games/where_is_mia/minigames/lozinka_biljeznice.config.json`
- `academy-bot/src/minigames/android-phone.html`
- `academy-bot/src/minigames/last-call-review.html`
- `academy-bot/src/minigames/last_call_phone.config.json`
- `academy-bot/src/minigames/lc/documents/en/izvori.txt`
- `academy-bot/src/minigames/lc/documents/en/jamstvo_perilica.txt`
- `academy-bot/src/minigames/lc/documents/en/knjiznica.txt`
- `academy-bot/src/minigames/lc/documents/en/kronologija.md`
- `academy-bot/src/minigames/lc/documents/en/nacrt_v1.docx`
- `academy-bot/src/minigames/lc/documents/en/nacrt_v3.docx`
- `academy-bot/src/minigames/lc/documents/en/obrazac_pristup_arhivi.pdf`
- `academy-bot/src/minigames/lc/documents/en/obrazac_pristup_arhivi.png`
- `academy-bot/src/minigames/lc/documents/en/pitanja_za_simunica.docx`
- `academy-bot/src/minigames/lc/documents/en/popis_13.csv`
- `academy-bot/src/minigames/lc/documents/en/popis_za_trgovinu.txt`
- `academy-bot/src/minigames/lc/documents/en/pravna_provjera.pdf`
- `academy-bot/src/minigames/lc/documents/en/pravna_provjera.png`
- `academy-bot/src/minigames/lc/documents/en/protokol_str14.pdf`
- `academy-bot/src/minigames/lc/documents/en/protokol_str14.png`
- `academy-bot/src/minigames/lc/documents/en/racun_kavana.pdf`
- `academy-bot/src/minigames/lc/documents/en/racun_kavana.png`
- `academy-bot/src/minigames/lc/documents/en/rezervacija_4821.txt`
- `academy-bot/src/minigames/lc/documents/en/servis_bicikla.txt`
- `academy-bot/src/minigames/lc/documents/en/sto_ako_grijesim.txt`
- `academy-bot/src/minigames/lc/documents/en/urednicki_stil.md`
- `academy-bot/src/minigames/lc/documents/en/vozni_red_noc.pdf`
- `academy-bot/src/minigames/lc/documents/en/vozni_red_noc.png`
- `academy-bot/src/minigames/lc/documents/en/za_vesnu_ne_saljem.eml`
- `academy-bot/src/minigames/lc/documents/hr/izvori.txt`
- `academy-bot/src/minigames/lc/documents/hr/jamstvo_perilica.txt`
- `academy-bot/src/minigames/lc/documents/hr/knjiznica.txt`
- `academy-bot/src/minigames/lc/documents/hr/kronologija.md`
- `academy-bot/src/minigames/lc/documents/hr/nacrt_v1.docx`
- `academy-bot/src/minigames/lc/documents/hr/nacrt_v3.docx`
- `academy-bot/src/minigames/lc/documents/hr/obrazac_pristup_arhivi.pdf`
- `academy-bot/src/minigames/lc/documents/hr/obrazac_pristup_arhivi.png`
- `academy-bot/src/minigames/lc/documents/hr/pitanja_za_simunica.docx`
- `academy-bot/src/minigames/lc/documents/hr/popis_13.csv`
- `academy-bot/src/minigames/lc/documents/hr/popis_za_trgovinu.txt`
- `academy-bot/src/minigames/lc/documents/hr/pravna_provjera.pdf`
- `academy-bot/src/minigames/lc/documents/hr/pravna_provjera.png`
- `academy-bot/src/minigames/lc/documents/hr/protokol_str14.pdf`
- `academy-bot/src/minigames/lc/documents/hr/protokol_str14.png`
- `academy-bot/src/minigames/lc/documents/hr/racun_kavana.pdf`
- `academy-bot/src/minigames/lc/documents/hr/racun_kavana.png`
- `academy-bot/src/minigames/lc/documents/hr/rezervacija_4821.txt`
- `academy-bot/src/minigames/lc/documents/hr/servis_bicikla.txt`
- `academy-bot/src/minigames/lc/documents/hr/sto_ako_grijesim.txt`
- `academy-bot/src/minigames/lc/documents/hr/urednicki_stil.md`
- `academy-bot/src/minigames/lc/documents/hr/vozni_red_noc.pdf`
- `academy-bot/src/minigames/lc/documents/hr/vozni_red_noc.png`
- `academy-bot/src/minigames/lc/documents/hr/za_vesnu_ne_saljem.eml`
- `academy-bot/src/minigames/lc/documents/zet_101_original.pdf`
- `academy-bot/src/minigames/lc/documents/zet_101_original.png`
- `academy-bot/src/minigames/lc/gallery/ana.jpg`
- `academy-bot/src/minigames/lc/gallery/potpis.svg`
- `academy-bot/src/minigames/lc/gallery/registracija.svg`
- `academy-bot/src/minigames/lc/gallery/rodjendan.jpg`
- `academy-bot/src/minigames/lc/gallery/tablica.svg`
- `academy-bot/src/minigames/lc/gallery/ulaz.jpg`
- `academy-bot/src/minigames/lc/receipt-secret.html`
- `academy-bot/src/minigames/tablet-lock.html`
- `academy-bot/src/presentation/message.ts`
- `academy-bot/test/item-action-results.test.ts`
- `academy-bot/test/last-call-reveal-order.test.ts`
- `academy-bot/test/media-variants.test.ts`
- `academy-bot/test/puzzle-dud-option.test.ts`
- `academy-bot/test/puzzle-hint-resume.test.ts`
- `academy-bot/tools/build-last-call-documents.py`
- `academy-bot/tools/build-last-call-props.py`
- `game-studio/scripts/last-call-phone-check.mjs`
- `game-studio/src/app/emulator/page.tsx`
- `game-studio/src/components/ItemsEditor.tsx`
- `game-studio/src/components/PuzzleLab.tsx`
- `game-studio/src/components/fields.tsx`
- `game-studio/src/lib/engine/bot/flows/inventory.ts`
- `game-studio/src/lib/engine/bot/flows/puzzles.ts`
- `game-studio/src/lib/engine/presentation/message.ts`
- `game-studio/src/lib/engine/systemUiData.ts`
- `game-studio/src/lib/schema/common.ts`
- `game-studio/src/lib/schema/item.ts`
