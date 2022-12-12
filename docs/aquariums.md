### Freshwater Aquariums
<img src="http://www.petmetwice.com/wp-content/uploads/2022/03/neon-tetras-in-an-aquarium-e1646348094176-768x513.jpg" width="400px"></img>
<p style="color:black; font-size:80%"> Well maintained aquariums can be a wonderful hobby for anyone! </p>
     
#### Basic Requirements
- Water conditioner
- Water filter
- Aquarium heater
- Air pump
- Substrate
- Lighting
- Aquarium water test strips

#### Water Conditioning
It is recommended to only use water conditioners that say “Sodium Thiosulfate” on the Bottle in the Ingredients List as they are very safe to use with fish. The reaction of chlorine (“chlorine” is typically added to water as sodium hypochlorite) with sodium thiosulfate is:<br><br>
$$ Na_2S_2O_3 + 4NaClO + H_2O = H_2SO_4 + Na2SO4 + 4NaCl $$

#### Aquarium Volume
The common rule for keeping fish is 1 gallon of water per inch of grown fish. 
<br><br>
Let's say you have one betta fish at 3 inches and 6 black neon tetras at 1.5 inches, like I do. This is the calculation you'd do to find the minimum volume of water your aquarium needs to hold: <br>
$$(6 \times 1.5) + 3 = 12 $$ <br>
Phew! I have a 15-gallon tank for them, so my fish can all safely co-exist there.

<img src="https://www.fishkeepingworld.com/wp-content/uploads/2017/11/Crowntail-Betta-Care-Guide-Lifespan-Facts-and-Compatibility-Banner-1.jpg" width="400px"> </img>
<p style="color:black; font-size:80%"> Blue and red Crowntail Betta, similar to the lovely fellow in my tank </p>

#### Aquarium Datasets
Let's say you wanted to see aquarium data from [data.world](https://data.world/city-of-ny/gzk5-mux8) which happens to be in *json* format. Here's how you would load it:

```python
import pandas as pd

aq_df = pd.read_json('./data/raw/directory-of-zoos-and-aquariums-1.json')

print(aq_df.to_string()) 
```

You could also create variables of your fish measurements and compare against your aquarium size to figure out if you need to "level up"!

```python
betta = 3
neon_tetra = 1.5
rosy_barb = 6
blue_dwarf_gourami = 4
aquarium_gal = 15

aquarium_vol = (neon_tetra * 6) + betta

print("your aquarium must hold at least " + str(aquarium_vol) + " gallons of water to have this many fish!")
```





