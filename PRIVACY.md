# Informativa sulla privacy — Slant Coach

**Ultimo aggiornamento: 9 ottobre 2026**

*(English version below — [jump to it](#privacy-policy--slant-coach).)*

## In due righe

Slant Coach non ha il permesso di uscire in rete. Non è una promessa di buona condotta: è una
cosa che il telefono impedisce. Tutto quello che scrivi resta nella cartella privata dell'app,
non c'è nessun account, nessun server, nessuna statistica e nessuna pubblicità. Niente di tuo
lascia il telefono, a meno che non sia tu a mandarlo.

Dal 9 ottobre 2026 c'è una cosa in più, spenta finché non la accendi: se vuoi, l'app scrive le
sedute in **Health Connect**, l'archivio della salute che Android tiene sullo stesso telefono.
Cosa scrive e cosa no è spiegato [più sotto](#health-connect).

## Chi tratta i dati

Slant Coach è un'app scritta da una persona sola, Alessandro Favarotto, senza società dietro e
senza fornitori a cui passare qualcosa. Non essendoci trasmissione di dati, non esistono
responsabili del trattamento, sub-fornitori o trasferimenti all'estero.

## Cosa l'app salva, e dove

Tutto quello che segue sta **solo sul tuo telefono**, nella cartella privata dell'app, che il
sistema Android rende leggibile alla sola Slant Coach:

**Il tuo profilo** — il nome che scegli di darti, sesso, età, peso e altezza (servono a
stimare il metabolismo basale e le calorie), il programma settimanale, la lingua, l'animale
scelto, la voce, e le impostazioni dei promemoria.

**Le preferenze di cucina** — lo stile alimentare, le allergie e intolleranze che dichiari, i
pasti che pianifichi e cosa hai in dispensa.

**Le sedute** — data, tipo (esercizi o camminata), minuti, calorie stimate, passi, livello e
ora di inizio.

**I bicchieri d'acqua** segnati e i **test di forza** fatti.

**I percorsi delle camminate** — latitudine, longitudine e istante di ogni punto, in file
separati, uno per camminata.

**Un diario tecnico** — se l'app si chiude da sola, la traccia dell'errore; più un elenco
breve delle operazioni recenti (per esempio gli orari a cui sono programmati i promemoria), il
modello del telefono e la versione di Android.

Non c'è nessun account, nessuna registrazione, nessun identificativo pubblicitario e nessun
codice che ti identifichi fra un'installazione e l'altra.

## Cosa l'app non fa

- **Non può trasmettere niente.** L'app non chiede il permesso `INTERNET`: senza quel permesso
  Android le impedisce di aprire una connessione, quindi non è questione di fiducia.
- Nessuna statistica d'uso, nessun servizio di analisi, nessun rilevatore di crash di terze
  parti, nessuna pubblicità, nessun profilamento.
- Nessun dato venduto, ceduto o condiviso con nessuno: non c'è il canale per farlo.
- Nessuna copia in cloud: l'app esclude i suoi dati anche dal backup automatico di Android su
  Google Drive. Passano da un telefono all'altro solo col trasferimento diretto fra telefoni, o
  con la copia di sicurezza che salvi tu.

Se guardi i permessi trovi `ACCESS_NETWORK_STATE`, e va spiegato invece di lasciarlo scoprire:
lo aggiunge la libreria di sistema che fa scattare i promemoria, e serve a sapere **se** il
telefono è connesso, non a connettersi.

## I permessi, e a cosa servono

| Permesso | A cosa serve |
|---|---|
| Notifiche | I promemoria dell'allenamento e dell'acqua |
| Avvio del telefono | Riprogrammare i promemoria dopo un riavvio |
| Vibrazione | I segnali durante la seduta |
| Riconoscimento attività | Contare i passi durante la camminata |
| Posizione precisa e approssimativa | Disegnare il percorso della camminata (Android chiede le due insieme) |
| Servizio in primo piano (posizione) | Continuare a segnare il percorso a schermo spento |
| Mantenere il telefono sveglio | Non interrompere una seduta in corso |
| Health Connect: scrivere esercizio e passi | Registrare le sedute in Health Connect, solo se lo accendi tu |

Sulla posizione, due precisazioni che contano. L'app chiede solo il permesso **«mentre usi
l'app»**, non quello di sfondo. E la registrazione parte solo quando avvii tu una camminata:
finché dura c'è una notifica visibile che dice che sta registrando, e sparisce quando segni
che hai finito.

## Cosa può uscire dal telefono, e solo se lo decidi tu

Ci sono quattro cose che puoi mandare a qualcuno, ognuna con un'azione esplicita:

1. **La cartolina** con i tuoi giorni di fila: apre il normale foglio di condivisione di
   Android e sei tu a scegliere a chi.
2. **La copia di sicurezza** dei tuoi dati: la salvi dove vuoi tu.
3. **Le tabelle** in CSV — sedute e pesate — da aprire con un foglio di calcolo: le salvi dove
   vuoi tu.
4. **Il diario tecnico**, se ti va di segnalare un guasto. Contiene il modello del telefono, la
   versione di Android, le tracce degli errori e le operazioni recenti dell'app. Non contiene
   il tuo nome, il tuo peso, né i percorsi delle camminate.

In tutti i casi il destinatario lo scegli tu, e da quel momento valgono le regole
dell'app a cui lo hai mandato.

## Health Connect

Health Connect è l'archivio dei dati di salute e attività che Android tiene **sul telefono**: le
app che ci scrivono e quelle che ci leggono le scegli tu, una per una, dalle sue impostazioni.

**È spento finché non lo accendi** dalle impostazioni di Slant Coach. In quel momento Android ti
chiede due permessi, e solo di scrittura:

- **Esercizio** — per ogni seduta: inizio, fine e tipo (ginnastica a corpo libero, camminata,
  corsa sul posto), con il titolo «Slant Coach».
- **Passi** — per le camminate in cui il telefono li ha contati.

Accendendolo, l'app scrive anche le sedute degli ultimi trenta giorni; da lì in poi ogni seduta
nuova, e toglie da Health Connect quelle che annulli nell'app.

Cosa **non** fa:

- **Non legge niente** da Health Connect: non chiede nessun permesso di lettura.
- **Non scrive le calorie**, né il peso, né i percorsi: le calorie sono stime e non devono
  diventare, in un'altra app, un numero che sembra misurato.
- Non passa per internet: Health Connect sta sul telefono, e l'app il permesso di rete continua a
  non averlo.

**Uso limitato.** I dati che l'app scrive in Health Connect servono solo a farteli ritrovare lì.
Non vengono usati per pubblicità, non vengono venduti né ceduti, e l'app non ne fa nessun altro
uso.

Quello che sta in Health Connect lo vedono le app a cui **tu** dai il permesso di leggerlo, e da
quel momento valgono le loro regole — alcune, per esempio, sincronizzano i dati sui propri server.
Lo spegni dalle impostazioni di Slant Coach; togli i permessi e cancelli i dati da quelle di
Health Connect.

## Dati sanitari e posizione

Peso, altezza, allenamenti, passi e percorsi sono informazioni che riguardano la tua salute e
i tuoi spostamenti, cioè fra le più delicate che esistano. Per questo stanno dove stanno e non
si muovono: restano nella memoria privata del telefono e non vengono trasmesse. L'unica
eccezione è quella che scegli tu: le sedute e i passi in Health Connect, se lo accendi.

Le calorie, la distanza in chilometri e il metabolismo basale sono **stime**, calcolate sul
telefono da formule pubbliche a partire da quello che hai scritto tu. Non sono misure mediche
e l'app non dà consigli medici.

## Bambini

Slant Coach non è rivolta a minori di 13 anni e non raccoglie consapevolmente dati di bambini.

## Come si cancella tutto

**Disinstalla l'app**: Android cancella la sua cartella privata, e con quella spariscono
profilo, sedute, percorsi e diario. Non ne resta copia da nessuna parte, perché copie non ne
sono mai state fatte — quindi non c'è niente da chiedere a nessuno, e nessuno a cui chiederlo.

Il rovescio della medaglia va detto chiaro: **se cambi telefono o disinstalli, i tuoi dati se
ne vanno con l'app.** Per questo nelle impostazioni c'è la copia di sicurezza da esportare e
reimportare.

Il solo diario tecnico si può cancellare quando vuoi dalle impostazioni, senza toccare il
resto.

**Health Connect è a parte**: quello che l'app ci ha scritto non sparisce disinstallandola, perché
sta nell'archivio di Android e non nella cartella dell'app. Lo cancelli dalle impostazioni di
Health Connect.

## I tuoi diritti

Il GDPR ti dà diritto di accedere ai tuoi dati, correggerli, cancellarli, portarli via e
opporti al trattamento. Qui li eserciti **direttamente dall'app**, senza chiedere permesso a
nessuno: i dati li vedi nelle schermate, li correggi dal profilo, li porti via con la copia di
sicurezza e li cancelli disinstallando. Non essendoci trasmissione, non c'è un titolare che
possa avere di te qualcosa che tu non abbia già in mano.

## Se questa informativa cambia

La data in cima dice quando è stata scritta l'ultima volta. Le versioni precedenti restano
visibili nella cronologia di questo file su GitHub: non si può cambiare in silenzio.

## Contatti

**slantcoach@gmail.com**

---

# Privacy Policy — Slant Coach

**Last updated: 9 October 2026**

## In two lines

Slant Coach does not have permission to go online. That's not a promise of good behaviour: the
phone itself prevents it. Everything you write stays in the app's private folder — no account,
no server, no analytics, no advertising. Nothing of yours leaves the phone unless you send it
yourself.

Since 9 October 2026 there's one more thing, off until you turn it on: if you want, the app
writes your sessions to **Health Connect**, the health store Android keeps on the same phone.
What it writes and what it doesn't is explained [below](#health-connect-1).

## Who handles your data

Slant Coach is written by one person, Alessandro Favarotto, with no company behind it and no
suppliers to pass anything to. Since no data is transmitted, there are no processors,
sub-processors or international transfers.

## What the app stores, and where

All of the following lives **only on your phone**, in the app's private folder, which Android
makes readable to Slant Coach alone:

**Your profile** — the name you choose, sex, age, weight and height (used to estimate basal
metabolism and calories), your weekly plan, language, chosen animal, voice, and reminder
settings.

**Kitchen preferences** — your eating style, the allergies and intolerances you declare, the
meals you plan, and what's in your pantry.

**Your sessions** — date, type (exercise or walk), minutes, estimated calories, steps, level
and start time.

**Glasses of water** logged, and **strength tests** taken.

**Walk routes** — latitude, longitude and timestamp of each point, in separate files, one per
walk.

**A technical log** — if the app closes by itself, the error trace; plus a short list of recent
operations (for example the times your reminders are scheduled for), your phone model and
Android version.

There is no account, no sign-up, no advertising ID and no identifier that follows you between
installations.

## What the app does not do

- **It cannot transmit anything.** The app does not request the `INTERNET` permission, and
  without it Android prevents it from opening a connection. It isn't a matter of trust.
- No usage analytics, no analysis services, no third-party crash reporter, no advertising, no
  profiling.
- No data sold, transferred or shared with anyone: there is no channel to do so.
- No cloud copy: the app also excludes its data from Android's automatic backup to Google
  Drive. It moves between phones only through a direct phone-to-phone transfer, or through the
  backup you save yourself.

If you check the permissions you'll find `ACCESS_NETWORK_STATE`, and it deserves explaining
rather than being discovered: it's added by the system library that fires the reminders, and it
reports **whether** the phone is connected — it does not connect.

## Permissions, and what they're for

| Permission | What it's for |
|---|---|
| Notifications | Training and water reminders |
| Boot completed | Rescheduling reminders after a restart |
| Vibration | Cues during a session |
| Activity recognition | Counting steps during a walk |
| Precise and approximate location | Drawing your walking route (Android asks for both together) |
| Foreground service (location) | Keeping the route recording with the screen off |
| Wake lock | Not interrupting a session in progress |
| Health Connect: write exercise and steps | Recording your sessions in Health Connect, only if you turn it on |

Two things about location that matter. The app only asks for the **"while using the app"**
permission, not background location. And recording starts only when *you* start a walk: while
it runs there's a visible notification saying so, and it disappears when you mark the walk
finished.

## What can leave the phone, and only if you decide

Four things can be sent to someone, each by an explicit action:

1. **The postcard** with your streak: it opens Android's normal share sheet and you choose the
   recipient.
2. **The backup** of your data: you choose where to save it.
3. **The tables** in CSV — sessions and weigh-ins — to open with a spreadsheet: you choose where
   to save them.
4. **The technical log**, if you want to report a fault. It contains your phone model, Android
   version, error traces and the app's recent operations. It does not contain your name, your
   weight, or your walking routes.

In every case you pick the recipient, and from that moment the rules of the app you sent
it to apply.

## Health Connect

Health Connect is the store of health and activity data that Android keeps **on the phone**: you
choose, one by one in its settings, which apps write to it and which read from it.

**It's off until you turn it on** in Slant Coach's settings. At that point Android asks you for
two permissions, write-only:

- **Exercise** — for each session: start, end and type (calisthenics, walking, running on the
  spot), titled "Slant Coach".
- **Steps** — for the walks where the phone counted them.

When you turn it on, the app also writes the sessions from the last thirty days; from then on,
every new session, and it removes from Health Connect the ones you cancel in the app.

What it does **not** do:

- **It reads nothing** from Health Connect: it asks for no read permission.
- **It doesn't write calories**, weight or routes: calories are estimates, and shouldn't become,
  in another app, a number that looks measured.
- It doesn't go through the internet: Health Connect lives on the phone, and the app still has
  no network permission.

**Limited use.** The data the app writes to Health Connect is there only so that you find it
there. It isn't used for advertising, isn't sold or transferred, and the app makes no other use
of it.

What's in Health Connect is visible to the apps **you** allow to read it, and from then on their
rules apply — some, for instance, sync data to their own servers. You turn it off in Slant
Coach's settings; you remove the permissions and delete the data in Health Connect's.

## Health data and location

Weight, height, workouts, steps and routes concern your health and your movements — among the
most sensitive information there is. That's why they stay where they are and don't move: in the
phone's private storage, never transmitted. The only exception is the one you choose: sessions
and steps in Health Connect, if you turn it on.

Calories, distance in kilometres and basal metabolism are **estimates**, computed on the phone
from public formulas using what you entered. They are not medical measurements, and the app
does not give medical advice.

## Children

Slant Coach is not directed at children under 13 and does not knowingly collect their data.

## How to delete everything

**Uninstall the app**: Android deletes its private folder, and with it your profile, sessions,
routes and log. No copy remains anywhere, because no copy was ever made — so there's nothing to
request from anyone, and nobody to request it from.

The flip side has to be said plainly: **if you change phone or uninstall, your data goes with
the app.** That's why Settings offers a backup you can export and restore.

The technical log alone can be deleted at any time from Settings, leaving everything else
untouched.

**Health Connect is separate**: what the app wrote there doesn't disappear when you uninstall it,
because it lives in Android's store, not in the app's folder. You delete it from Health Connect's
settings.

## Your rights

The GDPR gives you the right to access your data, correct it, delete it, take it with you and
object to its processing. Here you exercise those rights **directly in the app**, without
asking anyone: you see the data on screen, correct it in your profile, take it away with the
backup, and delete it by uninstalling. Since nothing is transmitted, there is no controller
holding anything about you that you don't already have in your hand.

## If this policy changes

The date at the top says when it was last written. Previous versions stay visible in this
file's history on GitHub: it cannot be changed silently.

## Contact

**slantcoach@gmail.com**
