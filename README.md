## Vídeos pel curs Desenvolupament d'aplicacions per a dispositius iOS

<div>👤 Albert Mata</div>
<div>📅 Tardor 2018</div>

📲 [__14. Dissenyar cel·la amb UIImageView, UIStackView i Auto Layout (Part 3)__](https://www.youtube.com/watch?v=4in4skNGgg8) 🔗 24/10/18

Comentem com, de fet, hi ha gent que prefereix que el codi de configuració d'una cel·la estigui situat a la mateixa cel·la (en el nostre cas a `ElementCell`). Expliquem els pros i contres d'aquesta manera de fer, relacionant-ho amb el compliment del patró de disseny MVC. Com a nota afegida, segurament el mètode `bind` és millor crear-lo amb la signatura `func bind(_ chemicalElement: ChemicalElement)`, amb aquest `_` afegit per fer que no calgui posar el nom extern del paràmetre, cosa que farà que cridar el mètode des del controlador sigui tan senzill i breu com `cell.bind(chemicalElement)`.

📲 [__13. Dissenyar cel·la amb UIImageView, UIStackView i Auto Layout (Part 2)__](https://www.youtube.com/watch?v=ny_9kDjdYys) 🔗 24/10/18

Expliquem com eliminar un warning corresponent a un error que ens marca Auto Layout.

📲 [__12. Dissenyar cel·la amb UIImageView, UIStackView i Auto Layout (Part 1)__](https://www.youtube.com/watch?v=SLQctjsP_Bw) 🔗 24/10/18

Creem una cel·la visualment més atractiva que la que teníem fins ara. Per fer-ho, treballem amb `UIImageView`, l'arxiu `Assets.xcassets`, `UIStackView` horitzontal i vertical, Auto Layout, transparències, etc.

📲 [__11. Relació entre storyboard i instàncies de UIViewController i subclasses__](https://www.youtube.com/watch?v=9_oWYB5bke4) 🔗 21/10/18

Aquest vídeo no ensenya com fer res en concret. Es tracta més aviat d'una explicació conceptual sobre la manera com les instàncies de `UIViewController` (i subclasses) que dissenyem als storyboards es relacionen amb els arxius de codi .swift que creem en paral·lel a Xcode. Mostrem la part que Xcode fa automàticament per nosaltres quan utilitzem storyboards i veiem que, de fet, si volem podem treballar sense storyboards.

📲 [__10. Navegar entre cel·la i detall de dues maneres diferents (Part 2)__](https://www.youtube.com/watch?v=TFH4b-wfhDc) 🔗 19/10/18

Entrem a fons en els dos sistemes diferents de navegar entre les cel·les d'una taula i un altre `UIViewController` que mostri el detall de la selecció feta per l'usuari. A banda, veiem com el `sender` del mètode `prepare(for:sender:)` pot ser una cel·la o qualsevol altre objecte que ens interessi.

📲 [__9. Navegar entre cel·la i detall de dues maneres diferents (Part 1)__](https://www.youtube.com/watch?v=1YYDt11yWgQ) 🔗 19/10/18

Mostrem com funciona una extensió d'una classe i comencem a preparar un projecte que ens permetrà explorar dues maneres diferents, però equivalents, de navegar entre les cel·les d'una taula i un altre `UIViewController` que mostri el detall de la selecció feta per l'usuari.

📲 [__8. Obrir la llibreria d'objectes com a finestra flotant__](https://www.youtube.com/watch?v=7QO8091E5k4) 🔗 17/10/18

Mostrem com podem obrir la llibreria d'objectes de tal manera que romangui oberta fins que decidim tancar-la manualment.

📲 [__7. Utilitzar prepare(for: sender:) per enviar informació a un UIViewController__](https://www.youtube.com/watch?v=vVK9R8gVOrE) 🔗 17/10/18

Mostrem com preparar la navegació entre la nostra cel·la personalitzada i el nou controlador que hem creat als vídeos anteriors, de tal manera que quan el controlador de destí es carregui mostri la informació de l'element que s'ha seleccionat a la taula.

📲 [__6. Crear subclasse de UIViewController i utilitzar-la a l'storyboard__](https://www.youtube.com/watch?v=wQHTfJbX9HI) 🔗 17/10/18

Creem una subclasse de `UIViewController` i expliquem quan és necessari fer-ho i per què ho fem en comptes de treballar directament amb instàncies de `UIViewController`. 

📲 [__5. Afegir navegació entre una cel·la i un nou UIViewController__](https://www.youtube.com/watch?v=8YpZ4KtJajY) 🔗 16/10/18

Fixem l'alçada de la nostra cel·la personalitzada. Afegim navegació entre cada cel·la i un nou `UIViewController` per mostrar el detall de l'element seleccionat. Veiem alguna noció més de `UIStackView` i Auto Layout.

📲 [__4. Crear subclasse de UITableViewCell per dissenyar una cel·la personalitzada__](https://www.youtube.com/watch?v=tu1jRishhYw) 🔗 15/10/18

Mostrem com crear una cel·la (subclasse de `UITableViewCell`) personalitzada per la nostra taula. En dissenyem una de trivial, però el procés és exactament el mateix per crear-ne de més vistoses. A més, fem anar per primera vegada un `UIStackView`, que és un element clau per dissenyar interfícies gràfiques en iOS.

📲 [__3. Dubtes bàsics sobre DataSource i Delegate__](https://www.youtube.com/watch?v=oPVBzuiDK9M) 🔗 14/10/18

Donem resposta a dubtes bàsics habituals sobre el funcionament de `UITableView`. Cal informar les propietats `dataSource` i `delegate`? I tots aquests mètodes que implementem... quan els cridem? O, si no els cridem nosaltres, qui i quan ho fa?

📲 [__2. Mostrar un conjunt de dades amb UITableViewController__](https://www.youtube.com/watch?v=ymo82HkMGbM) 🔗 12/10/18

Veiem com mostrar un conjunt de dades amb un component `UITableViewController` (que ja inclou automàticament un objecte `UITableView`). Aprenem que amb només dos mètodes ja aconseguim crear una taula amb un llistat d'elements.

📲 [__1. Crear esquelet bàsic de MyPlaces partint de plantilla bàsica__](https://www.youtube.com/watch?v=H8hCPuDTiEg) 🔗 11/10/18

Veiem com crear una interfície gràfica per MyPlaces semblant a la que hem fet per la PLA1, però partint d'una altra plantilla i amb algunes diferències respecte el que s'ha proposat a la PLA1, per tal que conegueu altres possibilitats.

