# Uranium Mine Simulator 
!!!
**Uranium Mine Simulator** is the [game](https://www.roblox.com/games/17807356578/), while **Uranium Mine Company** is the [Discord](https://discord.com/invite/B6Awa5SsKs) server.

This wiki will use **Uranium Mine Simulator** when referring to the game and **Uranium Mine Company** when referring to the Discord server
!!!
<hr>

![A player wearing Uranium Mine Issued Gear](mineissuedgear.png)

## Info & History
Uranium Mine Simulator was created on `June 10th, 2024` when two idiots thought it would be a great idea to attempt to make a game in roblox, having no experience at all. 
<span id="game-age" data-release="2024-06-10" aria-live="polite"></span>
<script>
(function(){
  const el = document.getElementById("game-age");
  if (!el) return;

  const releaseStr = el.dataset.release || "2024-06-10";
  const release = new Date(releaseStr + "T00:00:00Z");
  const now = new Date();

  // full years
  let years = now.getFullYear() - release.getFullYear();
  if (
    now.getMonth() < release.getMonth() ||
    (now.getMonth() === release.getMonth() && now.getDate() < release.getDate())
  ) {
    years--;
  }

  // month calculation:
  // total months difference minus the months inside the full years
  let totalMonths = (now.getFullYear() - release.getFullYear()) * 12 + (now.getMonth() - release.getMonth());
  if (now.getDate() < release.getDate()) totalMonths--;
  let months = totalMonths - years * 12;
  if (months < 0) months = 0;

  const asOf = now.toLocaleDateString(undefined, { year: 'numeric', month: 'short', day: 'numeric' });

  let text = "The game is now ";
  if (years > 0) text += `${years} year${years === 1 ? "" : "s"}`;
  if (years > 0 && months > 0) text += " and ";
  if (months > 0) text += `${months} month${months === 1 ? "" : "s"}`;
  if (years === 0 && months === 0) text += "less than a month";
  text += ` old (as of ${asOf}).`;

  el.textContent = text;
})();
</script>
<noscript>The game age is available when JavaScript is enabled.</noscript>


### Version 1
The first version did not have scripts and was just the terrain, spawn, and the little roofs for the mine and shop

![Version 1, originally called "Uranium Mine"](v1.png)
![Original **Uraniuim Mine Simulator** Icon](URAAANIUMFEVER.png)

### Pre-Alpha Versions
#### Version 294 
Added the first occurance of a shop (despite being just the GUI and being unscripted) and added the first revision of the mining system

![Version 294, pre-alpha, game is now called "Uranium Mine Simulator"](v2.png)

#### Version 625 
The `Robux Pickaxe` was added as a way to quickly mine ores for bug testing with the node spawning logic and a "Delete all actinium" button to test if respawning works
`Actinium T1`, `Actinium T2`, and `Actinium T3` was also added in this version

![Version 625, pre-alpha](v3.png)

### Alpha Versions
#### Version 766 (alpha 1.0)
The shop was completely remade and scripted. Categories for the shop wasn't added yet, so all items were just shoved in the shop all at once. The `Copper Pickaxe`, `Iron Pickaxe`, `Silver Pickaxe`, `Tungsten Pickaxe`, and `Alpha trophy` (now called Alpha1 Trophy) was all added during this update

![Version 766, alpha 1.0](v4.png)

#### Version 878 (alpha 1.1)
Caves got darker and the wall to block players from entering the nonexistant uranium mine was added

![Version 878, alpha 1.1](v5.png)

#### Version 989 (alpha 1.2)
The map was changed slightly, the lighting got redone, and the sell box got moved from the floor to Mikaeli's counter

![Version 989, alpha 1.2](v6.png)

#### Version 1062, (alpha 1.3)

Categories were to the shop, the new lanterns `Bulb Lantern` and `High Power Lantern` and the `Lantern` got a remodel

![Version 1062, alpha 1.3](v7.png)

#### Version 1155, (alpha 1.3)

Introduced a bug where you cannot talk to Mikaeli, but instead have to interact with the sell box before you speak to Mikaeli and removed the door from Mikaeli's shop

![Version 1155, alpha 1.3](v8.png)

#### Version 1269, (alpha 1.3)

Added the manual button and made minor lighting changes to make scenery look more vibrant and less depressing

![Version 1269, alpha 1.3](v9.png)

#### Version 2376, (alpha 1.4)

ok this is a big update:<br>
**Mining Improvements**<br>
The pickaxe swinging sound was added alongside a proper mining animation

**Uranium**<br>
Who would've thought a game called **Uranium Mine Simulator** did not have any Uranium<br>
The following minerals were added:<br>
- *Uranium Containing:*
    - Euxenite
    - Torbernite
    - Brannerite
    - Coffinite
    - Uraninite
- *Fluorine Containing:*
    - Fluorite
    - Cryolite

A brand new [workshop](/Locations/workshop) was added containing a mill, a chemical reactor, a neutron reactor, a gas centrifuge, a mixer, and an assembler. The workshop allows you to make
- Uranium Dioxide
- Fluorine
- Yellowcake Can
- Uranium Hexafluoride Can
- LE Uranium (Low Enriched Uranium)
- Plutonium
- Low Power Explosive
    - see [Explosives](/Items/explosives)
- High Power Explosive
    - see [Explosives](/Items/explosives)
- High Quality Fuel

![Version 2376, alpha 1.4](v10.png)