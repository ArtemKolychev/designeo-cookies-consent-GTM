Prvni copotrebujeme udelat. je to importirovat template do projektu. Pro to zkopirujem z repa "https://github.com/ArtemKolychev/designeo-cookies-consent-GTM" soubor "template.tpl" a "workspace.json". Pak Templates -> New -> settings (tri tecky v pravo) -> import. Vybereme nasi sablonu a kliknime save.

Dal potrebujeme importovat tags. Otevreme tab "Admin" (v levo) a dame "import container".

Vybereme "container file" a nahrajeme "workspace.json".

vybereme workspace. "Merge" option. Zkontrolujeme zmeny a dame ulozit.

Posledni vec bude zalozeni noveho tagu pro listu.

Ve sekce "Tags" zalozime novy tag. V configuration najdeme nasi sablonu a trigering bude "Init lang Event". Dale potrebujeme propojit sablonu s nastavenim jazykove mutace. Dela se to tak ze klikneme na "tag configuration" v tam v inputu "automaticLang" vybereme {{DL lang Variable}}. 
Triggering zvolime "Init Lang Event".

Lista je plne pripravena.

Ted zapneme samotny consent mode v google tags.

Projdeme do sekce Admin. Tam najdeme "Container Settings" a zapneme consent mode zvoliv "Enable consent overview".

Ted muzeme ucovat jaky tagi za jakich podminek se zapnou.

Na priklad "Google Analytics".

V jeho sekce "tag configuration" rozklikneme "Advanced Settings" a "Consent Settings". Dal zvolime "Require additional consent for tag to fire" a nastavime prislusne opravneni. Zbyva posledni vec. A to je Trigering. Ma byt nastaveny na "tracking Trigger"

Save -> submit ->enjoy
