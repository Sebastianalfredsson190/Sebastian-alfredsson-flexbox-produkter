När jag gör hemsidan och använder mig av "Flexbox-containers" och "Flexbox-items" Så har jag valt mig att göra en unik flex box container och item för varje item och container så att jag kan justera en viss mängds items utan att justera alla items i hela hemsidan. Och då har jag strukturerat det i alfabets ordning. Så När jag skapar en flexboxitem skriver jag "Flexbox-item_a" A sympoliserar att det är första och jag går neråt i alfabets ordning för att jag ska hålla struktur.
Jag har bilder med olika storlekar, jag har bild som är utklippt medans jag har bild som har ett mellan rum mellan kanten och slutet av bilden. Vilket leder till att när jag ska för flytta dessa bilder så måste jag använda mig av margins för att för flytta bilderna, men samtidigt så använde jag mig av spacebetween, men eftersmo avståenden är annorlunda pga av storlek av bilderna så använda jag mig av margins.
För att du skall slippa leta vart jag har använt mig av alla olika typer av flexes så visar jag de, Kunna använda flex
direction- Rad 16 i style.css
wrap- rad 19 css
flow- rad 85 i css
space-around- Rad 75 i style.css
space-between- Rad 299 i style.css
        <div class="flexbox-container_a">
            <div class="flexbox-item_a flexbox-item_a_1">
                <img src="cocacola.jpg" alt="" width="215px">
            </div>
            <div class="flexbox-item_a flexbox-item_a_2">
                <img src="cocacola-zero.jpg" alt=""width="300px">
            </div>
            <div class="flexbox-item_a flexbox-item_a_3">
                <img src="cocacola-light.png" alt=""width="300px">
            </div>
        </div> 