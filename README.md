# 🧱💥 RAMPAGE: VOXEL FURY

A pixel-perfect destruction sandbox with Neal.fun-inspired cellular automata physics.

## 🎮 Gamemodes

- **Sandbox** – Unlimited materials, full creative freedom, destroy and build at will
- **Survival** – Procedural terrain with caves and cliffs. Gather materials by digging, manage health, survive hazards (lava, acid, fire, drowning). Build shelters from your inventory. **WASD or Arrow keys** to move your character.

## 🎮 How to Play

1. **Open `index.html`** in any modern web browser
2. **Choose gamemode** – Sandbox or Survival
3. **Control** (Survival: WASD/arrows to move; Sandbox: mouse for cursor)
4. **Cause Chaos**: Smash through buildings and watch them crumble particle by particle
5. **Destroy Manually**: Right-click and drag to obliterate structures (Survival: gather materials into inventory)
6. **Spawn Materials**: Select from menu and click to place (Survival: consumes from inventory)
7. **Rebuild**: Press R to generate new world

## 🎯 Controls

| Input | Action |
|-------|--------|
| `WASD` / `Arrow Keys` | Move character (Survival mode) |
| `Left-click + Drag` | Place material |
| `Right-click + Drag` | Destroy voxels at cursor |
| `R` | Rebuild the world |
| `H` | Hide/Show UI (clean view) |
| `1` | Spawn concrete |
| `2` | Spawn dust |
| `3` | Spawn water |
| `4` | Spawn metal |
| `5` | Spawn lava (burns & spreads) |
| `6` | Spawn acid (dissolves everything!) |
| `7` | Spawn human (walks and interacts) |
| `8` | Spawn snow (melts to water) |
| `9` | Spawn oil (flammable liquid) |
| `0` | Spawn steam (rises like gas) |
| `Q` | Spawn blood (red liquid) |
| `W` | Spawn slime (viscous liquid) |
| `E` | Spawn fire (burns & rises) |
| `T` | Spawn plant seeds (grow into unique organic patterns) |
| `Y` | Spawn ice (melts near heat) |
| `U` | Spawn sand (fast particles) |
| `I` | Spawn honey (viscous, acid-resistant, sticky) |
| `O` | Spawn gravel (heavy particles) |
| `P` | Spawn wood (burnable solid) |
| `G` | Spawn gunpowder (explodes with fire!) |
| `J` | Spawn stone (heavy solid) |
| `K` | Spawn ember (glowing rising particles) |
| `A` | Spawn pellets (shotgun spread - light projectiles, launched by gunpowder) |
| `S` | Spawn fuse (burnable - carries fire along its length for chain ignition) |
| `.` | Spawn rubber (bouncy block - deflects lead and pellets) |
| ` (backtick) | Spawn antimatter (purple powder - ignite with fire for purple/blue blast!) |
| `-` | Spawn antimetal (blocks antimatter blast - immune to vaporization) |
| `C` | Spawn bacteria (reproduces near nutrients, dies from heat/acid) |
| `D` | Spawn mercury (dense toxic liquid metal) |
| **Shift + drag** | Draw straight lines with selected material (build walls, floors) |

## 🏗️ Building Tools (NEW!)

**Construct, don't just destroy!** New interactive building elements:

- **Water Spout** → Place in Solid tab. Continuously emits water downward—build fountains, fill pools, create flowing water features
- **Lava Spout** → Place in Solid tab. Emits lava continuously—build lava flows and volcanic setups
- **Quick Structures** (Build tab) → One-click placement:
  - **Bridge** → 12-wide concrete platform (2 blocks thick)
  - **Tower** → 4×20 block tower with metal-reinforced edges
  - **Arch** → Decorative stone arch
- **Line Tool** → Hold **Shift** and drag with any material selected to draw straight lines—perfect for walls, floors, and precise construction

## 🌟 Features Implemented

### ✅ Smart Builder Humans (NEW!)
Humans now exhibit lemming-like construction behavior with advanced building mechanics:
- **Patrol Mode**: Walk back and forth between edges of solid ground
- **Auto-Builder**: Deploy **sticky concrete blocks** when reaching edges or gaps
- **Sticky Blocks**: Human-placed blocks stick together and don't fall - they only collapse if completely isolated!
- **Bridge Constructors**: Automatically build over liquids, acid, and empty space
- **Randomized Building**: 
  - 25% chance to build stairs (one level up)
  - 10% chance to build towers (2-4 blocks high)
  - 5% chance to skip building (creates organic gaps)
  - 3% chance to randomly change direction while walking
- **Climbing Ability**: Humans can climb up one-block-high ledges automatically
- **Collaborative**: Multiple humans extend the same structures
- **Emergent Architecture**: Watch them create unique, organic platforms, towers, and pathways - no two structures are the same!

**Try this:** Spawn several humans on a platform surrounded by acid - watch them automatically build unpredictable sticky bridges, create random towers, and construct elaborate structures with organic variety!

### ✅ Pixel-Perfect Voxel Simulation
- Every particle is a 3x3 pixel voxel (large and visible!)
- Smooth granular motion
- Beautiful edge-based shading
- Silky Neal.fun-style physics

### ✅ Full Physics System
- Gravity simulation for all particles (except gases which rise!)
- Material-based density and strength
- Structural collapse emerges naturally
- Support and weight calculations
- Chain reactions and cascading destruction
- Corrosive acid mechanics - dissolves everything instantly!
- Lava heat spread and burning
- Fire combustion - spreads to oil, plants, and flammable materials
- Ice and snow melting near heat sources
- Organic plant growth - seeds sprout into unique branching vines, bushes, and clusters with weighted random growth patterns
- Gas physics - steam and fire rise instead of fall
- Viscous liquid physics - slime moves slowly
- **Smart Builder AI with Sticky Blocks** - Humans patrol surfaces, place sticky concrete that adheres together, climb ledges, and randomly build stairs and towers - creating unique gravity-defying structures with organic variety!

### ✅ Material Types

**Building Materials:**
- **Concrete** → Heavy, structural material
- **Metal** → Dense, high strength, resists destruction
- **Glass** → Brittle, shatters easily
- **Stone** → Heavy rugged solid
- **Wood** → Burnable solid, catches fire

**Particles:**
- **Dust** → Powder physics, flows freely
- **Sand** → Fast-falling granular particles, denser than dust
- **Snow** → White particles, melts near heat into water
- **Gravel** → Heavy fast-falling particles
- **Gunpowder** → Explosive! Ignites and spreads fire when touched by flame or lava
- **Ember** → Glowing orange particles that rise like sparks

**Liquids:**
- **Water** → Spills, pools, spreads horizontally
- **Oil** → Dark flammable liquid, ignites near fire
- **Blood** → Red liquid, similar to water
- **Slime** → Viscous green liquid, acid-resistant, sticks everything to it
- **Honey** → Very viscous golden liquid, even slower than slime, acid-resistant, sticky

**Reactive Materials:**
- **Lava** → Glowing molten material, burns weak materials, spreads heat
- **Acid** → DESTROYS EVERYTHING it touches with no remains - extremely satisfying!
- **Fire** → Burns materials, rises like smoke, spreads to flammable objects

**Gases:**
- **Steam** → Semi-transparent gas that rises instead of falls

**Life:**
- **Plant** → Organic life that starts as 1-3 small seeds and grows in fascinating ways:
  - **Inherently sticky** - plant blocks stick to each other and don't fall when connected
  - **Color variety**: Green leaves, brown stems, and infrequent bright flowers (yellow, red, pink, orange, magenta)
  - Grows upward like vines and stems (50% chance)
  - Branches sideways organically (25% chance)  
  - Spreads diagonally creating natural shapes (15% chance)
  - Creates hanging vines downward (10% chance)
  - Forms dense clusters near other plants
  - Isolated plants die back naturally
  - Each growth pattern is unique and unpredictable
- **Bacteria** → Microscopic life forms with real-life properties:
  - Reproduce and spread when near nutrients (water, blood, milk, feces)
  - Die from heat (fire, lava), acid, and mercury (toxic)
  - Colonize surfaces and form organic colonies
- **Human** → AI-controlled builder entities with lemming-like behavior:
  - Walk back and forth on solid surfaces
  - Detect edges and automatically place **sticky concrete blocks** to extend platforms
  - Sticky blocks adhere to each other and won't fall unless completely isolated
  - Randomly builds stairs, towers, or flat bridges with organic variety
  - Can climb up one-block-high ledges automatically
  - Build bridges over gaps, liquids, and acid
  - Multiple humans work together to create elaborate structures
  - Turn around after building and continue patrolling

**Special:**
- **Antimatter** → Purple powder (like gunpowder). Ignite with **fire** (E) or **lava** (5) - creates a purple and blue blast! 4-voxel core vaporizes everything, outer radius converts to glowing purple-blue blast that rises.
- **Antimetal** → Dense dark metal that blocks antimatter blast. Immune to vaporization and conversion - build shields to protect structures from antimatter explosions!
- **Ice** → Solid frozen material, melts into water near heat sources
- **Mercury** → Dense liquid metal with real-life properties:
  - One of the densest liquids - sinks through water, oil, and other fluids
  - Silvery metallic appearance with high surface tension
  - Toxic - kills humans, flies, worms, and bacteria on contact

### ✅ Procedural Buildings
- Random building generation
- Multi-floor structures
- Varied heights and widths
- Window placements
- Mixed materials

### ✅ Destruction Mechanics
- Entity-based destruction (player-controlled)
- Mouse-based manual destruction
- Material strength vs. force calculations
- Debris generation (materials convert to dust)
- Particle ejection physics

### ✅ Clean UI
- Minimalist HUD
- Real-time particle count
- Destruction percentage tracker
- FPS counter
- Transparent controls overlay

## 🎨 Visual Design

The game achieves the Neal.fun aesthetic through:

- **2x2 pixel voxels** for smooth granular appearance
- **Cellular automata** for natural particle behavior
- **Color variation** for texture without blockiness
- **Sky gradient** background
- **Soft entity rendering** with transparency

## ⚡ Technical Highlights

- **Cellular Automata Engine**: Simulates falling sand physics
- **Efficient Grid System**: 640x360 particle grid
- **Material Properties**: Density, strength, flow behavior
- **Structural Integrity**: Dynamic support calculations
- **Random Update Order**: Prevents directional bias
- **Real-time Particle Tracking**: Performance monitoring

## 🚀 Performance

- Runs at **60 FPS** with thousands of active particles
- Uses HTML5 Canvas with ImageData for direct pixel manipulation
- Optimized physics simulation with selective updates
- Efficient collision detection

## 🎭 Game Feel

Pure destruction and creation sandbox:

- Click and drag to obliterate structures
- Buildings crumble particle by particle
- Gravity creates organic collapses
- Matter flows and behaves naturally
- Destruction is both mesmerizing and satisfying
- **16 unique materials** with emergent interactions!
- **Acid provides the most satisfying destruction** - watch it eat through entire buildings with no remains!
- Lava glows and spreads heat, converting materials
- Fire spreads dramatically through flammable materials (oil, plants)
- Ice and snow melt realistically near heat sources
- Plants grow from tiny seeds into unique organic structures - vines, bushes, and clusters that are different every time
- Steam and fire rise beautifully against gravity
- Oil ignites in spectacular chain reactions
- Slime oozes slowly with viscous physics
- Each material has unique, emergent behavior
- **Humans display emergent intelligence** - they patrol surfaces with random behavior patterns, automatically extend platforms with sticky blocks, climb ledges, randomly build stairs and towers, and create unique organic structures over gaps and liquids - no two runs are the same!

## 🛠️ Customization

Want to tweak the experience? Edit the `CONFIG` object in the code:

```javascript
const CONFIG = {
    pixelSize: 2,        // Voxel size (smaller = more detail)
    gravity: 0.15,       // Physics gravity strength
    entitySize: 40,      // Destruction force size
    entitySpeed: 3,      // Movement speed
    destroyRadius: 30    // Mouse destruction radius
};
```

## 🎯 Game Loop

1. **Physics Simulation** → Particles fall, flow, and interact
2. **Entity Update** → Player movement and collision
3. **Destruction** → Materials break and convert to debris
4. **Rendering** → Pixel-perfect visualization
5. **Repeat** → 60 times per second

---

**Built with**: Pure HTML5, Canvas API, and Vanilla JavaScript

**No dependencies** • **No build process** • **Just open and play**

Enjoy the chaos! 💥
