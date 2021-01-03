# Diario del secondo progetto di Intercative 3d Graphics

Il sito presenta una piccola sezione che contiene la scena con cui l'utente può interagire. Gli oggetti disponibili sono:
- un'ascia;
- uno scudo;
- una spada.
Invece, i materiali disponibili sono:
- metallo;
- oro;
- legno;
- metallo pitturato;
- argento;
- tessuto.

# Realizzazione modelli 3d

# BRDF e luci

La BRDF utilizzata è la seguente: BRDF classica sommata alla BRDF prodotta dalla componente ambientale speculare e da quella diffusiva. La luce è una semplice pointLight che non viene effettivamente aggiunta alla scena. Per quanto riguarda cspec, non c'è una vera texture speculare da cui ottenere il valore, ma è stata ottenuta tramite la metalnessMap seguendo la logica trovata nella seguente pagina e ai collegamenti contenuti https://medium.com/gametextures/metallic-magic-2dce9001fe15 .

Per quanto riguarda la BRDF utilizzata, è stata trovata andando a cercare tipologie comuni di BRDF usate. Dopo un certo periodo passato a cercare della documentazione è stata trovata la seguente pagina su Github che fa riferimento a "https://www.unrealengine.com/blog/physically-based-shading-on-mobile - environmentBRDF for GGX on mobile". La pagina è la seguente: https://github.com/mrdoob/three.js/blob/dev/src/renderers/shaders/ShaderChunk/bsdfs.glsl.js .


# Controlli utente

All'interno della scena in cui l'utente può interagire con gli oggetti, sono stati aggiunti dei controlli relativi alla rotazione e alla dimensione degli oggetti.

# Possibili modifiche

