## Pravidla využívání nástrojů umělé inteligence

Používání nástrojů generativní umělé inteligence při vypracování semestrálního projektu je povoleno v omezeném rozsahu. Cílem těchto pravidel není omezovat využívání moderních nástrojů, ale zajistit, aby student samostatně prokázal porozumění principům analýzy dat a strojového učení.

### Povolené využití AI

Student může využívat nástroje umělé inteligence zejména pro:

- generování a úpravu kódu jednotlivých buněk Jupyter notebooku na základě vlastních konkrétních požadavků,
- identifikaci a opravu programátorských chyb,
- vysvětlení funkcí, knihoven, algoritmů a matematických principů,
- implementaci studentem navržených experimentů a vizualizací,
- konzultaci obecných metodologických a technických otázek.

### Nepovolené využití AI

Student nesmí využívat nástroje umělé inteligence pro:

- automatické vypracování celého notebooku nebo jeho ucelených analytických částí,
- samostatnou analýzu datasetu a rozhodování o jeho předzpracování namísto studenta,
- návrh metodiky a experimentů namísto studenta,
- generování textových komentářů interpretujících výsledky experimentů, grafy nebo tabulky,
- generování zdůvodnění výběru atributů, transformací, algoritmů či hodnoticích metrik,
- formulování závěrů projektu.

### Odpovědnost studenta

Student nese plnou odpovědnost za veškerý odevzdaný obsah, včetně kódu vytvořeného pomocí umělé inteligence.

Student musí být schopen vysvětlit použitý kód, jeho účel a princip fungování, zdůvodnit jednotlivá rozhodnutí a samostatně interpretovat dosažené výsledky.

Veškeré analytické komentáře, zdůvodnění a závěry musí být výsledkem vlastní práce studenta.

Při obhajobě projektu může být student požádán o osobní vysvětlení nebo úpravu libovolné části odevzdaného notebooku.

### Transparentnost využití AI

Na konci notebooku student uvede, zda při vypracování projektu využíval nástroje umělé inteligence, které nástroje použil a k jakým účelům.
Volitelně může uvést u každého generovaného kódu i konkrétní prompt, kterým kód vygeneroval. Podobně platí, pokud používáte AI k přeformátování nebo upravení odpovědi,
vyžaduje se původní odpověď a prompt.

Samotné využívání umělé inteligence v souladu s uvedenými pravidly není důvodem ke snížení hodnocení projektu.

## Příklady povolených a nepovolených promptů

Následující příklady ilustrují rozdíl mezi využíváním AI jako pomocného nástroje a delegováním vlastní odborné práce na AI.

### 1. Explorativní analýza dat

**Povoleno:**
- Vygeneruj Python kód pro zobrazení histogramu a boxplotu atributu SalePrice.
- Jak mohu pomocí knihovny pandas zjistit počet chybějících hodnot v jednotlivých sloupcích?
- Vysvětli mi rozdíl mezi Pearsonovým a Spearmanovým korelačním koeficientem.

**Nepovoleno:**
- Proveď explorativní analýzu tohoto datasetu.
- Navrhni, které atributy datasetu bych měl analyzovat, a vytvoř odpovídající vizualizace.
- Interpretuj přiloženou korelační matici a formuluj závěry.

### 2. Předzpracování dat

**Povoleno:**
- Vygeneruj kód pro nahrazení chybějících hodnot atributu Age mediánem.
- Jaký je rozdíl mezi StandardScaler, MinMaxScaler a PowerTransformer?
- Vygeneruj kód pro one-hot encoding atributů Protocol a Service.

**Nepovoleno:**
- Analyzuj dataset a rozhodni, jakým způsobem nahradit chybějící hodnoty.
- Vyber vhodné transformační metody pro jednotlivé atributy a zdůvodni jejich použití.
- Proveď kompletní předzpracování datasetu pro klasifikaci.

### 3. Výběr atributů

**Povoleno:**
- Vygeneruj kód, který zobrazí dvojice atributů s absolutní hodnotou Pearsonova korelačního koeficientu větší než 0,9.
- Vysvětli, jaký vliv mohou mít silně korelované atributy na algoritmus k-means.
- Jak funguje metoda PCA?

**Nepovoleno:**
- Na základě korelační matice rozhodni, které atributy mám odstranit.
- Vyber nejvhodnější atributy pro klasifikaci tohoto datasetu.
- Zdůvodni, proč jsem odstranil následující atributy.

### 4. Shlukování

**Povoleno:**
- Vygeneruj kód pro aplikaci algoritmu k-means pro hodnoty k od 2 do 10.
- Vygeneruj kód pro vizualizaci výsledků elbow metody.
- Vysvětli princip silhouette score.
- Vygeneruj tabulku obsahující mediány jednotlivých atributů pro každý shluk.

**Nepovoleno:**
- Vyber na základě tohoto grafu optimální počet shluků a zdůvodni jej.
- Rozhodni, které atributy mám použít pro shlukování zákazníků.
- Interpretuj charakteristiky jednotlivých shluků a pojmenuj je.
- Vypracuj kompletní část projektu věnovanou shlukování.

### 5. Klasifikace a návrh experimentů

**Povoleno:**
- Vygeneruj kód pro trénování rozhodovacího stromu s maximální hloubkou 5.
- Jaký je rozdíl mezi standardní a stratifikovanou cross-validation?
- Vygeneruj kód pro porovnání modelů Random Forest a SVM pomocí stratifikované 5-fold cross-validation.
- Vysvětli význam hyperparametru max_depth.

**Nepovoleno:**
- Navrhni kompletní metodiku klasifikačního experimentu pro tento dataset.
- Rozhodni, které klasifikační algoritmy mám použít, a zdůvodni jejich výběr.
- Vyber nejvhodnější hodnoticí metriky pro můj dataset a napiš zdůvodnění jejich výběru.

### 6. Vyhodnocení a interpretace výsledků

**Povoleno:**
- Vygeneruj kód pro výpočet accuracy, precision, recall a F1-score.
- Vygeneruj kód pro zobrazení confusion matrix.
- Vysvětli obecně, proč může být accuracy zavádějící u nevyvážených datasetů.
- Vygeneruj kód pro zobrazení výsledků jednotlivých modelů pomocí boxplotu.

**Nepovoleno:**
- Interpretuj výsledky mého klasifikačního modelu.
- Na základě této tabulky výsledků rozhodni, který model je nejlepší, a zdůvodni svůj výběr.
- Napiš komentář k přiloženému grafu.
- Vysvětli, proč můj model dosahuje nízké hodnoty recall, na základě přiložených výsledků.
- Napiš závěrečné zhodnocení experimentu.

### 7. Tvorba Jupyter notebooku

**Povoleno:**
- Oprav chybu v této buňce Jupyter notebooku.
- Vysvětli mi, co dělá tento úsek Python kódu.
- Zjednoduš tento kód při zachování jeho funkcionality.
- Doplň technické komentáře vysvětlující fungování tohoto kódu.

**Nepovoleno:**
- Na základě přiloženého zadání a datasetu vytvoř kompletní Jupyter notebook.
- Vypracuj druhou část semestrálního projektu.
- Doplň všechny chybějící analytické komentáře v notebooku.
- Zkontroluj zadání projektu a automaticky implementuj všechny dosud nesplněné požadavky.
- Přeformuluj AI generované závěry tak, aby působily jako vlastní práce studenta.

### Obecné pravidlo

Povolené je využití AI k implementaci konkrétního kroku, jehož účel a podobu určil student, nebo k získávání znalostí potřebných pro samostatné řešení projektu.

Nepovolené je využití AI k nahrazení vlastního analytického uvažování, odborného rozhodování, interpretace výsledků a formulování závěrů.

Tato pravidla platí bez ohledu na použitý nástroj, ať už se jedná o konverzačního asistenta, programátorského asistenta nebo autonomního AI agenta. Rozhodující je charakter delegované práce, nikoliv počet promptů nebo množství vygenerovaného kódu.