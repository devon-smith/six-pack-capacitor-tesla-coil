# Six-Pack Capacitor Tesla Coil ⚡️

A homemade Tesla coil powered by a capacitor bank made from six glass bottles filled with salt water and topped with mineral oil — essentially the same approach Tesla used with champagne bottles, except I used whatever was in the recycling bin. The coil produces visible arcing plasma off the top load, and yes, you can light a bulb by holding it near it.

## How It Works

A neon sign transformer steps 120V AC up to ~10kV, which charges the six-pack capacitor. The spark gap acts as a switch — air is an insulator until the voltage across the capacitor climbs high enough to arc across the gap, at which point the stored energy dumps into the primary coil. That induces a much higher voltage in the secondary coil, and the top load discharges plasma into the air. The whole cycle repeats many times per second, which is what makes the arcs look continuous rather than like individual sparks.

A Terry Filter sits between the NST and the rest of the circuit to protect the transformer from RF interference and voltage spikes feeding back into it. Neon sign transformers are not cheap to replace, so the filter earns its spot.

## Key Components

- **Neon Sign Transformer (NST)** — steps 120V AC up to ~10–12kV to charge the capacitor
- **Six-Pack Capacitor** — six glass bottles filled with salt water, topped with mineral oil to hold in the charge. Low-tech and surprisingly effective.
- **Primary Coil** — low-gauge copper tubing, carefully spaced around the base of the secondary coil
- **Secondary Coil** — high-gauge copper magnet wire wound tightly around a PVC pipe. Any overlap in the winding and the coil is toast — I learned to go slow on this one.
- **Spark Gap** — acts as the circuit's switch. Air insulates until the voltage is high enough to arc across.
- **Top Load** — a toroid shape that the plasma discharges from. The fun part.
- **Terry Filter** — protects the NST from RF interference and overvoltage. The responsible part.

## Build Process

1. **Wind the secondary coil** — wrapped a PVC pipe with high-gauge copper magnet wire under tension, keeping each turn flush against the last. Overlapping wires will short the coil, so this step is either meditative or maddening depending on your patience.
2. **Install secondary coil terminals** — connected the wire ends to secure terminals at top and bottom.
3. **Build the top load** — shaped a toroid for the plasma to discharge from.
4. **Construct the six-pack capacitor** — filled glass bottles with salt water, topped with mineral oil, wired them together. It looks like a science fair project and works like actual high-voltage infrastructure.
5. **Build the primary coil** — bent copper tubing into a flat spiral, spaced carefully around the secondary coil.
6. **Assemble and tune** — put everything together and adjusted the primary coil tap point for optimal arcing. Tuning is mostly trial and error with a healthy respect for the fact that everything is live at 10kV.


## Demo

The video shows the coil arcing plasma off the top load and lighting a fluorescent bulb held in my hand — no wires, just the electric field doing its thing.

[![Tesla Coil Demo](https://github.com/user-attachments/assets/PLACEHOLDER)](https://github.com/user-attachments/assets/PLACEHOLDER "Six-Pack Tesla Coil Demo")

## Credits

- [Tesla Coil Design](https://en.wikipedia.org/wiki/Tesla_coil)
- [Terry Filter Design](http://www.hvtesla.com/terry.html)



Here’s a video sneak peek of the arching plasma lighting up a light bulb I hold in my hand: [![Tesla Coil in Action](https://github.com/user-attachments/assets/af36c75e-ecf4-4c07-a1b6-c9b6e64979cb "Tesla Coil Video")](https://github.com/user-attachments/assets/af36c75e-ecf4-4c07-a1b6-c9b6e64979cb)

