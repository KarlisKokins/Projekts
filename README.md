# Projekts (Kārlis Kokins; 231RDC004)
## Uzdevums izveidot programmu, kas izmantojot studenta datus no excel faila un datiem, kurus students pats ievada, aprēķina produktivitātes sadalījumu pirmajā mācību semestrī.

### Students paralēli studijām strādā un regulāri sporto, tāpēc ir pieejami vairāki produktivitātes rādītāji.
### Programmai jāizvada dati no excel faila "Studenta_kalendars". Nepieciešamie dati ir divās tabulās (Studiju laiks, minūtēs), (Darba laiks, stundās). Studiju laiks ir dots minūtēs, jo visas lekcijas vai studiju nodarbības ir 95 minūšu garas. Šos datus vajag iegūt no excel faila, datus par studiju laiku vajag pārveidot stundās, lai varētu izmantot vienādu laika mērvienību priekš produktivitātes sadalījuma.
### Ņemot vērā to, ka students regulāri sporto un pavada laiku, lai pildītu mājasdarbus vai mācītos ārpus universitātes laika ir nepieciešami arī šie dati, produktivitātes sadalījumam. Tomēr, šie dati netiek nekur reģistrēti un tos studentam ir nepieciešams pašam ievadīt.
### Pēc visu nepieciešamo datu iegūšanas un apstrādāšanas (Studiju laiks, minūtes=>stundas), vajag aprēķināt produktivitātes sadalījumu. Ir nepieciešams summēt visas produktīvās stundas (studiju laiks + mājasdarbi + darbs + sports) un katru no atsevišķiem skaitītājiem dalīt ar kopējo summu un pārveidot procentos.

### Izmantota Python bibliotēka, lai varētu izmantot un strādāt ar datiem no excel faila "Studenta_kalendars"
## Programmas pielietojums
### Šo programmu var izmantot, lai labāk un precīzāk saprastu konkrēta cilvēka produktivitātes sadalījumu, ja rezultāti šķiet neapmierinoši, tad pēc produktivitātes sadalījuma ir iespējams redzēt, kur persona būtu gatava mainīt prioritātes. Protams, rādītājos kā studiju laiks un darba laiks ir noteikts stundu skaits vienā semestrī, ko nevar mainīt, vienīgi neapmeklējot studijas vai darbu.
