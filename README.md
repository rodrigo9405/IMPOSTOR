# Impostor

Juego de fiesta para jugar en grupo con un solo teléfono. Todos conocen la palabra secreta menos el impostor, que tiene que disimular.

## Cómo se juega

1. Elijan cuántos juegan (de 3 a 15), cuántos impostores habrá y escriban sus nombres. Luego toquen **Jugar**.
2. Pasen el teléfono: cada uno mira su rol a solas. Los inocentes ven la palabra; el impostor no.
3. La app sortea quién empieza. Por turnos, cada uno dice una palabra relacionada con la palabra secreta, sin decirla.
4. Al terminar la ronda, cada uno vota en secreto por quien cree que es el impostor. El más votado sale y se revela si era impostor o inocente.
5. Si hay empate, pueden desempatar entre los empatados o seguir sin eliminar a nadie.

**Ganan los inocentes** si sacan a todos los impostores. **Ganan los impostores** si llegan a ser tantos como los inocentes.

## Opciones

- **Tema de la palabra:** Sorpréndeme, Comida, Animales, Lugares, Objetos, Profesiones o Deportes.
- **Pista para el impostor:** si se activa, el impostor ve el tema y una palabra relacionada.

## La palabra secreta

Cuando el juego se abre dentro de Claude, una IA elige una palabra nueva en cada partida. Abierto en cualquier otro sitio (por ejemplo, GitHub Pages), la palabra sale de una lista de unas 90 palabras incluida en `index.html`. En los dos casos la app evita repetir las últimas palabras usadas.

## Uso

Es un solo archivo, `index.html`, sin dependencias ni instalación. Ábrelo en el navegador o publícalo con GitHub Pages:

**Settings → Pages → Branch: `main` / `(root)` → Save**

Los nombres de los jugadores se guardan en el navegador para la siguiente partida.
