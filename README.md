# AR Foundation - Kill the Goblin

## Description

**The Bad Avocado** és un minijoc de realitat augmentada desenvolupat amb Unity i AR Foundation. El jugador ha de trobar i capturar un alvocat malvat que apareix integrat en el món real.

El projecte utilitza diferents funcionalitats d'AR Foundation per combinar objectes virtuals amb l'entorn físic:

- **Plane Detection:** detecta superfícies planes de l'entorn real i permet col·locar-hi la presó (Jail).
- **Image Tracking:** detecta una imatge de referència d'una taula de tallar i fa aparèixer el model 3D del Bad Avocado sobre aquesta.
- **Occlusion:** permet que els objectes virtuals quedin ocults quan un objecte real es troba entre la càmera i l'objecte virtual.
- **Point Cloud:** proporciona informació sobre punts de l'entorn i ajuda en el seguiment de les superfícies.

## Installation

1. Clona o descarrega aquest repositori.
2. Obre el projecte amb Unity.
3. Obre l'escena AR del projecte.
4. Configura un dispositiu compatible amb AR i executa l'aplicació.

> **Nota:** La documentació del projecte no especifica la versió exacta de Unity, AR Foundation ni els requisits mínims del dispositiu. Consulta la configuració del projecte per utilitzar les versions corresponents.

## Usage

L'objectiu del joc és trobar i capturar el **Bad Avocado**.

1. Inicia l'aplicació i apunta la càmera cap a l'entorn real.
2. Mou la càmera per permetre que el sistema detecti les superfícies de l'espai.
3. Quan es detecta un pla adequat, es pot col·locar la **presó (Jail)** sobre la superfície.
4. Mostra davant de la càmera la imatge de referència de la **taula de tallar (cutting board)**.
5. Quan l'aplicació reconeix la imatge, apareix el **Bad Avocado** sobre aquesta.
6. L'oclusió permet que l'alvocat quedi parcialment ocult quan un objecte real es troba entre la càmera i el model virtual.

El projecte també utilitza Point Cloud per facilitar el seguiment de l'entorn i permetre el seguiment de punts que no necessàriament formen superfícies planes.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

The Bad Avocado es va desenvolupar a partir de les plantilles i funcionalitats proporcionades per Unity i AR Foundation.

El desenvolupament va començar amb la preparació de l'escena AR i la configuració de l'escena de Unity. Posteriorment es va implementar el seguiment d'imatges, l'oclusió i el Point Cloud, juntament amb els ajustos necessaris dels models 3D.

Durant el desenvolupament es van trobar diversos problemes, especialment relacionats amb:

- La compatibilitat entre diferents versions de les eines del projecte.
- La posició, orientació i origen dels models 3D.
- La implementació de l'oclusió.

Per solucionar aquests problemes es va adaptar la configuració del projecte, es van modificar els models 3D fora de Unity quan va ser necessari i es va revisar la configuració dels components relacionats amb l'oclusió.

## Credits

### Autors

- **Isaac Oliver Monells**
- **David Caldés Bou**

### Tutors

- **Marc Galvez Llorens**

### Contribucions

**David** va realitzar la major part del treball relacionat amb les funcionalitats d'AR i els scripts del projecte. També va ser el responsable principal de les proves de l'aplicació en un dispositiu Android compatible.

**Isaac** va participar en totes les fases del desenvolupament, va ajudar en la implementació i revisió dels canvis, i va ser el responsable principal dels assets 3D i de la documentació del projecte.

El desenvolupament es va realitzar de manera col·laborativa, integrant els assets 3D amb les funcionalitats d'AR Foundation i comprovant el funcionament de l'aplicació en un dispositiu real.

## License

No s'especifica una llicència concreta a la documentació del projecte.
