## Contributions to Science

### Newton's Law of Universal Gravitation
#### History
Sir Issac Newton was an English mathematician, physicist, astronomer, alchemist, theologian, and author (described in his time as a "natural philosopher"), widely recognised as one of the greatest mathematicians and physicists and among the most influential scientists of all time.<br><br>
<img src = "https://i.natgeofe.com/n/faf6f6b2-3d6f-4fee-82ed-77a2f28c0063/11606.jpg?w=636&h=437" width='400px'> </img>
<p style = "color:black;font-size:80%"> Sir Isaac Newton surrounded by symbols of some of his greatest findings </p>

#### Simple Definition
Newton's Law of Gravitation states that any particle of matter in the universe attracts any other with a force varying directly as the product of the masses and inversely as the square of the distance between them.
#### Equation
The equation for universal gravition is written as:<br><br>
$$ F=G\frac{{m_1}{m_2}}{{r^2}} $$ 
- $F$ is the gravitational force acting between two objects 
- $G$ is the gravitational constant
- $m_1$ and $m_2$ are the masses of the objects 
- $r$ is the distance between the centers of their masses
#### Datasets
If we wanted to look at more astronomy data, we could download a dataset from [data.world](https://data.world/markmarkoh/future-asteroids) and load it like this:
```python
import pandas as pd
asteroids_df = pd.read_csv("./data/raw/future.csv)
asteroids_df
```
<br>

### Telescopic Observation of Mars
Galileo Galilei was the first person to observe Mars with a primitive telescope in 1610. However, Mars has been documented for at least 4000 years so it is impossible to credit a specific person with it's discovery.
#### History
Galileo was an Italian astronomer, physicist and engineer, sometimes described as a polymath. His contributions to observational astronomy include telescopic confirmation of the phases of Venus, observation of the four largest satellites of Jupiter, observation of Saturn's rings, and analysis of lunar craters and sunspots.
<br><br>
<img src = "https://upload.wikimedia.org/wikipedia/commons/thumb/d/d4/Justus_Sustermans_-_Portrait_of_Galileo_Galilei%2C_1636.jpg/330px-Justus_Sustermans_-_Portrait_of_Galileo_Galilei%2C_1636.jpg" width='400px'> </img>
<p style = "color:black;font-size:80%"> Galileo Galilei in a 1636 portrait by Justus Sustermans </p>

#### Mars Stats
- Mars has a mass of $m_{j} \approx 6.42 \times 10^{23} \: \text {kg}$, about 10 times less than Earth
- Mars has a volume of  $1.6318 \times 10^{11} \: \text {kg}^{3}$, which is the equivalent of 0.151 Earths
- Mars has a density of $3.93 \: \text {g}/{cm}^3$, lower than the Earth’s density
#### Calculations
Here is how we could create a dictionary to store the ratio between gravity on another planet and Earth, so in future we could calculate what objects would weigh there.
```python
gravity_ratio_dict = {
    "Mercury": 38,
    "Venus": 91,
    "Earth": 100,
    "Mars": 38,
    "Jupiter": 234,
    "Saturn": 106,
    "Uranus": 92,
    "Neptune": 119,
}
```




 