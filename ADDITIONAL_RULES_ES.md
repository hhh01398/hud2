Este texto es una traducción del [texto original](./README.md).

# <img src="assets/logo.png" alt="Humanity Unchained DAO" height="22px"> Humanity Unchained DAO

El código fuente y documentación técnica se encuentra en el **[directorio app](./app)**.

<!-- TOC -->

- [Humanity Unchained DAO](#humanity-unchained-dao)
    - [Introducción](#introducci%C3%B3n)
- [Reglas Adicionales](#reglas-adicionales)
    - [General](#general)
    - [Aplicación](#aplicaci%C3%B3n)
        - [General](#general)
        - [Sistema de Gestión de Identidad](#sistema-de-gesti%C3%B3n-de-identidad)
        - [Asamblea](#asamblea)
            - [Miembros](#miembros)
            - [Delegados](#delegados)
            - [Escaños](#esca%C3%B1os)
        - [Votaciones](#votaciones)
            - [General](#general)
            - [Fuera de la cadena](#fuera-de-la-cadena)
            - [En la cadena](#en-la-cadena)
                - [Quórum](#qu%C3%B3rum)
        - [Madrina](#madrina)
        - [Monedero](#monedero)
        - [Token](#token)
            - [Distribución](#distribuci%C3%B3n)
        - [Emblemas](#emblemas)
            - [Clústers](#cl%C3%BAsters)
    - [Gestión de servicios fuera de la cadena](#gesti%C3%B3n-de-servicios-fuera-de-la-cadena)
    - [Infracción de las normas](#infracci%C3%B3n-de-las-normas)
    - [Procedimiento de modificación de las normas adicionales](#procedimiento-de-modificaci%C3%B3n-de-las-normas-adicionales)

<!-- /TOC -->

## Introducción

Somos [Humanity Unchained DAO](https://humanityunchained.org) (o **HUD**, abreviado), una [Organización Autónoma Descentralizada (DAO, por sus siglas en inglés)](https://es.wikipedia.org/wiki/Organizaci%C3%B3n_aut%C3%B3noma_descentralizada) y una alternativa al monopolio de sistema de gobierno impuesto mundialmente a través de los estados, instituciones transnacionales y grandes corporaciones technológicas que esclaviza a la humanidad.

Estamos construyendo una nueva civilización basada en el principio del respeto incondicional al consentimiento de los seres humanos. Bajo dicho principio, cualquier sistema de gobierno, tal como constituciones y leyes, políticas monetarias, sistemas de justicia, sistemas electorales, tratados supranacionales, organizaciones religiosas, etc. es ilegítimo *mientras* los seres humanos bajo el mandato de dicho sistema no hayan dado su [consentimiento](./constitution/CONSTITUTION_ES.md#artículo-2) para acatar las normas del sistema.

Por el contrario, los miembros de HUD prometen voluntariamente respetar la [Constitución](./constitution/CONSTITUTION_ES) y las [Reglas Adicionales](.) (este mismo documento). Estos dos textos sientan las bases de un nuevo marco de convivencia que permite a los seres humanos crear y elegir los sistemas de gobierno, en forma de federación de DAOs, bajo los que quieren vivir. Estas DAOs pueden ser diversas en su propósito, reglas internas, y en la forma en que se organizan socialmente, económicamente, etc. También pueden compartir recursos en el mundo físico, como territorios.

En caso de disputa entre miembros y/o DAOs, se celebra un juicio por jurado formado por todos los miembros de HUD o, de forma opcional, por delegados designados por los miembros, cuyo fallo debe ser acatado, y funcionando a todos los efectos como una [democracia semidirecta](https://es.wikipedia.org/wiki/Democracia_semidirecta) en la [cadena de bloques](https://es.wikipedia.org/wiki/Cadena_de_bloques). Este sistema de votación permite a HUD además interactuar con otros [contratos inteligentes](https://es.wikipedia.org/wiki/Contrato_inteligente) en la cadena para, por ejemplo, gestionar colectivamente sus finanzas o actualizar el código de los contratos inteligentes de acuerdo con la última version de las [Reglas Adicionales](.) aprobadas democráticamente por la DAO.

Para garantizar el principio de 1-humano-1-voto, HUD utiliza el sistema de registro de identidad [Proof of Humanity](https://proofofhumanity.id/) que garantiza que todos los miembros son seres humanos vivos y que no existen identidades duplicadas. Opcionalmente, los miembros pueden crear una entidad anónima derivada de su identidad no anónima de [Proof of Humanity](https://proofofhumanity.id/) usando la criptografía de pruebas de conocimiento cero de [SISMO](https://sismo.io).

El fallo del jurado puede ejecutarse a través de multas, revocación de roles o expulsión a miembros. Para ello, HUD tiene dos tipos de tokens: un [token fungible](#token), que sirve de herramienta para crear incentivos económicos dentro de HUD, y un tipo especial de [token no fungible](https://es.wikipedia.org/wiki/Token_no_fungible) llamado [emblema](#emblems), que se utiliza para asignar roles o cargos. HUD tiene pleno control sobre dichos tokens, pudiendo incluso confiscarlos si así lo dicta el jurado.

La [Constitution](./constitution) de HUD [no puede modificarse](./constitution/CONSTITUTION_ES.md#artículo-2), lo que permite a los individuos y a las DAOs que se adhieren a HUD beneficiarse de la garantía constitucional perpetua de HUD del respeto incondicional del consentimiento de los seres humanos y de la posibilidad de solicitar un juicio con jurado en caso de disputa. Los individuos pueden unirse a HUD simplemente registrando su identidad y firmando la promesa de respetar la [Constitución](./constitution/CONSTITUTION_ES) y las [Reglas Adicionales](.) con el monedero digital asociado a su identidad. Las DAOs pueden integrarse con HUD asignando emblemas a sus usuarios y haciéndolos necesarios para pertenecer a la DAO o para desempeñar roles internos. Para funciones que requieran de responsabilidad, se pueden crear emblemas que requieran depositar HUD tokens a modo de fianza.

# Reglas Adicionales

## General

### Art. 1 
La DAO se llamará Humanity Unchained DAO.

### Art. 2
El logotipo de la DAO será una figura simplificada de dos formas humanas abrazadas.

<img src="assets/logo.png"/>

### Art. 3
El idioma oficial principal de la DAO será el inglés.

### Art. 4
Los idiomas oficiales secundarios de la DAO serán el chino mandarín y el español.

### Art. 5
En la medida de lo posible, podrán utilizarse traducciones de las fuentes originales en el idioma principal a los idiomas secundarios para la Constitución, las Normas Adicionales y la interfaz de usuario de la aplicación. En caso de discrepancia entre versiones en distintos idiomas, prevalecerá siempre la versión en el idioma principal.

### Art. 6
Los fallos del Jurado prevalecerán sobre las especificaciones. Las especificaciones prevalecerán sobre el código.


## Aplicación


### General

#### Art. 1
Habrá una aplicación que implemente los requisitos establecidos en la Constitución y en las Normas Adicionales.

#### Art. 2
La aplicación debe implementarse utilizando una tecnología que sea públicamente accesible, segura, verificable y a prueba de manipulaciones. La DAO podrá decidir si migra o no la aplicación a otras tecnologías más adecuadas a medida que evolucione el estado del arte de las tecnologías descentralizadas.

#### Art. 3
La aplicación se distribuirá bajo licencia MIT.

#### Art. 4
La aplicación será una aplicación Web3 basada en contratos inteligentes de Ethereum y se desplegará en la cadena de bloques Polygon.

#### Art. 5
Los contratos inteligentes sólo podrán ser modificados por la DAO.

#### Art. 6
La dirección de los contractos inteligentes se resolverá con el nombre de [Ethereum Name Service](https://ens.domains/) **humanityunchaineddao.eth**.


### Sistema de Gestión de Identidad

#### Art. 1
La aplicación permitirá a los miembros crear y gestionar su identidad digital mediante un Sistema de Gestión de Identidad.

#### Art. 2
El Sistema de Gestión de Identidad será a prueba de ataques sybil.

#### Art. 3
Será posible integrar otros sistemas de identidad en la aplicación.

#### Art. 4
Los miembros podrán registrar una identidad HUD no anónima y una identidad HUD anónima, y elegir libremente que identidad usar en todo momento.

#### Art. 5
La aplicación permitirá utilizar [Proof of Humanity](https://proofofhumanity.id/) como sistema de gestión de identidad no anónima. Se creará un sistema para sincronizar el contrato inteligente Proof of Humanity en la red principal de Ethereum con la cadena Polygon.

#### Art. 6
La aplicación permitirá utilizar el badge [SISMO](https://sismo.io) de [Proof of Humanity](https://proofofhumanity.id/) como sistema de gestión de identidad anónima.

#### Art. 7
EL metadata de las identidades se almacenará en [IPFS](https://en.wikipedia.org/wiki/InterPlanetary_File_System).

#### Art. 8
El acceso IPFS por defecto será [nftstorage.link](https://nftstorage.link).


### Asamblea

#### Miembros

##### Art. 1
Todos los miembros de la DAO deben poseer una identidad registrada válido en el Sistema de Gestión de Identidades.

##### Art. 2
Para hacerse miembros, los solicitantes firmarán con su monedero la promesa de respetar la [constitución](./constitution/CONSTITUTION) y las versiones actuales y futuras de las Normas Adicionales durante el tiempo que dure su membresía.


##### Art. 3
Los miembros podrán darse de baja en cualquier momento.



#### Delegados

##### Art. 1
Los miembros podrán designar a un delegado, el cual emitirá los votos en nombre de los miembros.

##### Art. 2
Los delegados no necesitarán ser miembros.

#### Escaños


##### Art. 1
Habrá 20 escaños.

##### Art. 2
Los delegados con el mayor número de miembros designados podrán ocupar un escaño.


### Votaciones

#### General


##### Art. 1
La forma de contar los votos será 1-humano-1-voto.

##### Art. 2
Habrá dos tipos de votos: votos de los miembros y votos de los delegados.

##### Art. 3
El signo del voto puede ser "Sí", "No" y "En Blanco".

##### Art. 4
Las votaciones sobre propuestas que requieran transacciones en la cadena se realizarán en la cadena. El¶esto de propuestas podrán votarse fuera de la cadena.

##### Art. 5
Las direcciones sospechosas no podrán votar.


#### Fuera de la cadena

###### Art. 1
Se podrán realizar votaciones fuera de la cadena en [Snapshot](snapshot.org).


#### En la cadena

###### Art. 1
La aplicación implementará un sistema de votación en la cadena que permita a los miembros de la DAO interactuar colectivamente con cualquier contrato inteligente que se ejecute en la misma cadena. El sistema soportará la presentación de propuestas que contengan transacciones que se ejecutarán si la mayoría de los miembros así lo aprueba.

###### Art. 2
Cualquiera, excepto las direcciones sospechosas, podrá presentar propuestas.

###### Art. 3
Las propuestas podrán contener cualquier número de transacciones.

###### Art. 4
Deberá ser posible adjuntar metadatos a las propuestas y transacciones.

###### Art. 5
Sólo los miembros podrán iniciar votaciones sobre las propuestas presentadas.

###### Art. 6
La creación de votaciones será gratuita.

###### Art. 7
Cada votación se dividirá en dos: una votación por parte de los delegados y una votación por parte de los miembros. Si los resultados de las votaciones están en conflicto (por ejemplo, los delegados aprueban y los miembros no aprueban, o viceversa), la votación por parte de los miembros siempre prevalece sobre la de los delegados. Además, la votación por parte de los miembros siempre finalizará después de la los delegados.

###### Art. 8
Votación por parte de los delegados: La propuesta será aprobada por los delegados de la DAO si la suma de todos los votos delegados de los delegados con escaño que votaron "sí" es mayor que el número total de miembros delegados por los delegados con escaño multiplicado por un umbral determinado.

Ejemplo:

Delegado D1 (con escaño) representa a los miembros M1 y M2.
Delegado D2 (con escaño) representa a los miembros M3 y M4.
Delegado D3 (con escaño) representa al miembro M5.
Delegado D4 (sin escaño) reprenseta al miembro M6.
Umbral: 50%.

D1 y D4 votan "no".
D2 y D3 votan "sí".

Número total de miembros delegados por delegados con escaño: 5.
Número de votos delegados "Sí": 2 + 1 = 3.

3 > 5 * 50% => La propuesta es aprobada por los delegados.

###### Art. 9
Votación por parte de los miembros: La propuesta será aprobada o rechazada si el número de votos de los miembros a favor del "sí" o el número de votos de los miembros en contra del "no", respectivamente, es mayor que el número total de miembros multiplicado por un umbral determinado.

Ejemplo:

Miembros: M1, M2, M3, M4, M5 y M6.

M1, M2, M3 y M4 votan "no".
M5 vota "sí".
M6 vota "en blanco".
Umbral: 50%.

4 > 6 * 50% => La propuesta es rechazada por los miembros.

###### Art. 10
La Votación por parte de los miembros

###### Art. 10
La DAO puede establecer el valor de los umbrales de votación, que por defecto serán del 50%.

###### Art. 11
Las transacciones de las propuestas aprobadas podrán ser ejecutadas por cualquiera.

###### Art. 12
Los ejecutores de las transacciones podrán ser recompensados con tokens HUD.

###### Art. 13
Los delegados con escaño que se hayan abstenido de votar en la última votación pasarán a tener el estado de sospechosos. Los miembros que se hayan abstenido de votar en las dos últimas votaciones y no hayan nombrado a un delegado pasarán a tener el estado de sospechosos.

###### Art. 14
Las votaciones comenzarán el lunes a las 00:00 CET y finalizarán el sábado a las 23:59 CET de la misma semana.


##### Quórum

###### Art. 1
Se necesitará un número mínimo de miembros registrados (deminado *Quórum de Miembros*) para que una propuesta se ejecute si es aprobada. Hasta que se alcance el Quórum, sólo la Madrina podrá ejecutar las propuestas aprobadas.

###### Art. 2
El quórum será de al menos 1000 miembros.

### Madrina

#### Art. 1
Hasta que se haya alcanzado el quórum, la madrina podrá modificar o volver a desplegar los contratos inteligentes, pero con el único fin de corregir fallos o para reducir el número necesario de miembros del quórum.

#### Art. 2
La madrina se retirá automáticamente una vez que se haya alcanzado el quórum.


### Monedero


#### Art. 1
La DAO poseerá un monedero para almacenar cualquier tipo de token en la cadena.

#### Art. 2
Las transferencias fuera del monedero sólo serán posibles a través de una votación en la cadena aprobada por la DAO.

### Token

#### Art. 1
La DAO tendrá un token fungible, que se llamará *Token HUD*.

#### Art. 2
El token implementará el [estándar ERC-777](https://eips.ethereum.org/EIPS/eip-777).

#### Art. 3
El token tendrá las siguientes características:

Símbolo: HUD
Nombre: Humanity Unchained DAO
Decimales: 18

#### Art. 4
La DAO tendrá el control total del token, como la capacidad de acuñar, destruir, confiscar y transferir forzosamente tokens, y de impedir que determinadas direcciones reciban o envíen tokens.

#### Art. 5
El suministro total de tokens será de 21 millones.

#### Art. 6
La DAO poseerá una reserva inicial de 1 millón de tokens HUD. La DAO decidirá qué hacer con la reserva a través de votaciones on-chain. El resto, 20 millones de tokens HUD, serán distribuidos entre los primeros usuarios que se registren.

#### [Distribución](#distribución)

##### Art. 1
Cada nuevo miembro registrado que haya sido referido por otro miembro podrá optar a una recompensa en tokens HUD. Se podrá ser referido solamente una vez.

##### Art. 2
Aquellos miembros que refieran a nuevos miembros podrán optar a una recompensa en tokens HUD por cada nuevo miembro referido. Se podrá referir a un número ilimitado de miembros.

##### Art. 3
La suma de tokens HUD recompensados al miembro referido y al miembro que refiere no sobrepasará la cantidad dada por la siguiente fórmula:

50 / (2 ^ floor(númeroMiembros / 200000))

o sea:

| Rango de miembros      | Número de tokens HUD |
|------------------------|----------------------|
| x < 200000             | 50                   |
| 200000 <= x < 400000   | 25                   |
| 400000 <= x < 600000   | 12.5                 |
| 600000 <= x < 800000   | 6.25                 |
|  ...                   | ...                  |

y así sucesivamente hasta llegar al límite total de tokens recompensados.

<img src="assets/token_distribution.png" alt="Token distribution" height="270px">

##### Art. 4
El número total de tokens recompensados no sobrepasará los 20 millones.


### Emblemas

Nota: En esta sección, el término "DAO" se utiliza para referirse tanto a la organización en general como a cualquiera de los contratos inteligentes de la aplicación.

#### Art. 1
La aplicación implementará un tipo especial de token no fungible, llamado Emblema, que proporciona a la DAO una forma flexible de construir y gestionar estructuras organizativas.

#### Art. 2
La implementación de emblemas seguirá el [Estándar Multi Token ERC-1155](https://eips.ethereum.org/EIPS/eip-1155).

#### Art. 3
Cualquiera podrá crear un emblema y de forma gratuita, a no ser que la DAO asigne una tasa por la creación de nuevos emblemas o por la acuñación de tokens de un emblema concreto. Dicha tasa será cobrada en tokens HUD.

#### Art. 4
El creador del emblema tendrá por defecto el rol de administrador del emblema. Dicho rol podrá ser transferido a otra dirección por parte de la DAO y del propio administrador.

#### Art. 5
El URI del emblema, donde se almacenan los metadatos del token, sólo podrá ser modificado por la DAO. Si el administrador o los poseedores del emblema desean cambiar el URI, se presentará una propuesta a la DAO para su votación en la cadena.

#### Art. 6
La DAO o el administrador del emblema podrán establecer un depósito obligatorio en tokens HUD necesario para poseer el emblema. Las direcciones que no depositen dicha cantidad no podrán recibir tokens del emblema. Si la dirección ya posee tokens, el dueño no podrá hacer uso de los tokens hasta que deposite la cantidad completa requerida.

#### Art. 7
Los emblemas podrán ser intransferibles (también llamados *soulbound*), lo que significa que el propietario no podrá transferirlos a otra dirección, a menos que el propietario sea el administrador del emblema o la DAO. Esta característica se establece al crear el emblema y sólo la DAO puede cambiarla.

#### Art. 8
Los emblemas podrán configurarse de manera que cada dirección no se pueda poseer más de un token, excepto para el administrador del emblema o la DAO. Esta característica se establece al crear el emblema y sólo la DAO puede cambiarla.

#### Art. 9
La DAO y el admin podrán transferir forzosamente tokens de emblemas desde cualquier dirección excepto desde las de la DAO. Esto incluye destruir tokens (que efectivamente equivale a transferirlos a la dirección cero).

#### Art. 10
Los emblemas podrán ser *verificados*, lo que significa que están legitimados por la DAO. La DAO podrá verificar un emblema a través de una votación en la cadena. Los emblemas creados por la DAO serán verificados por defecto.

#### Art. 11
Los miembros, delegados y escaños de la DAO serán emblemas cuyo administrador es la DAO, serán intransferibles y cada dirección sólo puede poseer un token.

#### Art. 12
La tasa de acuñación de tokens y el depósito requerido del emblema de membresía o serán cero.

#### Art. 13
La tasa de acuñación de tokens del emblema de delegación será cero. El depósito requerido será de 100 tokens HUD.

#### Art. 14
La tasa de acuñación de tokens del emblema de escaños será cero. El depósito requerido será de 200 tokens HUD.

#### Art. 15
La DAO tendrá pleno control de los tokens emblema, como la capacidad de acuñar, destruir y transferir forzosamente tokens, y de impedir que determinadas direcciones reciban o envíen tokens.

#### Art. 16
Será posible integrar emblemas en otras DAO, como p.ej. las creadas con [Aragon](https://aragon.org).


#### Clústers

##### Art. 1
Se denominará "clúster" a un tipo especial de emblemas que están vinculados a uno o más territorios. Las coordenadas espaciales de los territorios se almacenarán como parte de los metadatos del token.

##### Art. 2
Los territorios de los clústers se representarán gráficamente en un mapa en la aplicación.

## Gestión de servicios fuera de la cadena

#### Art. 1
La DAO designará miembros que se encargarán de gestionar los servicios fuera de la cadena mediante la creación y transferencia de emblemas creados para tal fin. Dichos emblemas se denominarán *emblemas de administrador*.

#### Art. 2
Se creará un emblema de administrador para cada uno de los siguientes servicios externos:

| Servicio | URI |
| --- | --- |
| Dominio web y servidor | https://humanityunchained.org |
| Subgraph | https://api.thegraph.com/subgraphs/name/hhh01398/hud-subgraph-test-1
| ENS | humanityunchaineddao.eth |
| Github | https://github.com/hhh01398/hud2 |
| Twitter | https://twitter.com/UnchainedDAO |
| Telegram | https://t.me/humanityunchaineddao |
| Foro | https://forum.humanityunchained.org |


#### Art. 3
Los emblemas de administrador sólo podrán ser transferidos por la DAO.

#### Art. 4
Un miembro sólo podrá tener un emblema de administrador por cada servicio fuera de la cadena.

#### Art. 5
Se necesitará un depósito de 5000 tokens HUD para poseer un emblema de administrador.

#### Art. 6
Los poseedores del emblema no podrán ser cuentas sospechosas.

#### Art. 7
La Madrina entregará las credenciales de cualquier servicio fuera de la cadena que ella posea a los titulares de emblemas correspondientes antes de que se alcance el Quórum.

## Infracción de las normas

### Art. 1
La Aplicación proporcionará un modo para que la DAO mantenga un registro de los miembros expulsados.

### Art. 2
La Aplicación proporcionará una manera para que la DAO mantenga un registro de las direcciones que han sido amonestadas por infringir cualquier regla. Dichas direcciones se denominarán "sospechosas".

### Art. 3
La DAO podrá establecer qué direcciones son sospechosas a través de una votación en la cadena y podrá hacerlo por cualquier razón que la DAO considere apropiada.

### Art. 4
Los miembros sospechosos podrán ser expulsados.

### Art. 5
Las direcciones sospechosas podrán dejan de serlo si la DAO lo decide a través de una votación en la cadena.

### Art. 6
Las direcciones sospechosas no podrán recibir o enviar tokens HUD o emblemas.

### Art. 7
Las direcciones o ex-miembros sospechosos no podrán convertirse en miembros o delegados.

### Art. 8
Los delegados sospechosos no podrán reclamar un escaño. Los delegados sospechosos con asiento pueden conservarlo.

### Art. 9
Las direcciones sospechosas no podrán presentar propuestas ni iniciar votaciones.

### Art. 10
Los delegados con asiento que se abstengan de votar en la última votación en cadena podrán ser asignados el estado de sospechosos.

### Art. 11
Los miembros que se abstengan de votar en las dos últimas votaciones en cadena y que no tengan ningún delegado designado podrán ser asignados el estado de sospechosos automáticamente.

### Art. 12
Las direcciones sospechosas no podrán ser administradores de emblemas.

## Procedimiento de modificación de las normas adicionales

### Art. 1
El documento de Reglas Adicionales será controlado por versiones.

### Art. 2
Las nuevas versiones del documento de Reglas Adicionales entrarán efectivamente en vigor una vez que el contrato inteligente DAO se actualice a través de una votación en la cadena con la referencia (por ejemplo, la URI a un determinado commit de Git) al nuevo documento de Reglas Adicionales.