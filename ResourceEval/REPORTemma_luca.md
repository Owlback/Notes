# STUDY AND QUESTIONNAIRE ADMINISTRATION ON 2 ALTERNATIVE RENEWABLE ENERGY PLANTS
**Authors:** Emma S. Smith ; Luca Bacilieri

*RESD, Alma Mater Studiorum University of Bologna*

<small>[**No AI** was used in the creation of this report, its writing, the accompanying
sensitivity analysis or questionnaire]</small>

## SUMMARY
The following report will explore the choice between 2 alternative projects for
the construction and implementation of a renewable energy plant in a mountainous
area located in central/southern Italy.

The two mutually exclusive proposed projects are an **onshore wind farm** composed of 7
large-size turbines with a generation capacity spanning from 6 to 7 $MW$ of power
each, or a **Photovoltaic plant** with a total generation capacity of 45 $MW$.

Considering collected data regarding similar projects, and the intrinsic nature
of the implant's infrastructure and degradation during the project's lifespans,
a useful lifespan of **20 years** is estimated for the wind farm, while there
is reason to believe the solar PV plant's lifespine will last around **25 years**.

Both projects are expected to occupy a large portion of the mountainous area,
providing power to the nearby villages, cities and commercial activities, and
hopefully, in the long run, alleviate energy prices in the surrounding areas,
and would of course mainly affect villages and cities close to the mountainous
area, being them the ones in most direct contact with the infrastructure and
getting the most benefits, and possible costs and side effects from it.

Tourists, environmental protection agencies, people who work/find themselves
nearby the energy implants regularly and could have an interest in
their onstruction or who may oppose it.

## The Onshore Wind Farm:
Wind farms transform kinetic energy from the wind into mechanical energy, a
motor then transforms it to electrical energy.
When it comes to wind turbines, territory is the most notable restriction, since
both ground quality and weather both need to be favourable to work.

This lucky combination matches the candidate area's, while steady soil not prone
to collapsing or crumbling is a need, wind speeds should also be in a range that
can guarantee's the turbine's continuous and optimal work, since too weak winds
won't generate energy and too strong ones will lock the propeller blades in place
istead.

In Italy, onshore wind speeds aren't the absolute optimal for wind energy
generation, but the central/south zone and the higher altitude help increasing
the turbine's capacity factor, which is how much of the actual capacity, which
has a mean of 45,5 $MW$, is being harnessed.

the wind farm, will undeniably have a big impact on the landscape.
Altough not as cumbersome as other renewable infrastructure, the turbines are 
very tall and impossible not to notice, installation and construction would
alter the nearby area and possibly disrupt normal plant and animal activities
and lives.

After that, the 7 turbines the project predicts would be reasonably spaced and
allow for more room for biodiversity in the surrounding area.

Due to the challenging mountainous terrain transporting, constructing, maintaining,
and, for the end of the project's life, dismantling, costs are naturally higher
than the onshore average.

*(The following estimations, even if calculated based on similar real-life cases andwidely recognized benchmarks, are still for illustrative purposes and do not represent an actual 100% accurate cost breakdown.)*

The construction cost for the entirety of the wind farm's 7 turbines is estimated
at 80.000.000 Euros, while the early years of life of the project (from 1 to 10) will with all
probability require around 2.300.000 Euros annually.
During the twilight years of the project, (11 to 20) the maintainance price will raise to 3.000.000 Euros, with a final dismantling cost of also 3.000.000 Euros.

## The Photovoltaic Plant:
Photovoltaic panels are around since quite some time already, and are continuously
evolving towards more efficient models almost each year that passes.
Solar panels absorb light through solar cells, and create direct current (DC) with
when sunlight hits them.
This process is called the "Photovoltaic effect".
PV plants are cheap and quicker to install compared to other renewable options,
which is one of the reason why they are so popular all over the world.


The photovoltaic plant will be way less tall than the turbines, but occupy much more space in terms of surface of the mountainous area. 
Installation and construction will be easier in terms of transport of the
infrastructure, but once the job's done, the area covered by the photovoltaic
panels will be way more.

The implant will be concentrated in just one large spot, in which biodiversity will be disrupted.

Solar power generation follows a so-called duck curve, that displays how the
load of photovoltaic implants drops during peak hours near midday, when solar
generation is at its maximum.
During the time of max generation, solar panels may encounter a bottleneck problem
since there could be an overload on the electrical grid and a potential production
of energy would be wasted.

During nighttime, generation will always face a halt.

Electrical energy can be stored in batteries by the solar panels, but at that size
energy dissipation is a challenge technology hasn't resolved yet.

For an installation with a total capacity of 45 $MW$ the average price of construction
falls around an estimated value of 40.500.000 Euros, the yearly maintainance costs
during the first years of the project (form 1 to 10) are supposed to amount to
1.000.000 Euros, while for the remaining years of life of the project, due to
deterioration which raises maintainance costs, 2.000.000 Euros.

Dismantling costs are estimated to reach 5.000.000 Euros.

### Transformers
Having reached this point, we need to address the connections that will need to be
enstablished to connect the site to the electric power grid.

For the energy produced by both renewable sources to be actually usable by consumers,
the DC current outputted shall be converted in alternate current (AC), transformers
are an important aspect, both in terms of functionality and of **impact on the environment**.

Transformers have the function of voltage conversion among others like transmission, electrical isolation, grid integration for the implants and overall systen stability.

Basically, transformers are the piece of key infrastructure that allows renewable
energy systems to run efficiently.

The main downside, is the loud noise transformers make, which could disturb local fauna.

## From Data Calculation of the Benefits.
To explain this section, we're taking as an example the average capacity factor
for wind and solar energy recorded in the interested area, which coincides with the
values stated in the sensitivity analysis' base case, which correspond to 30% for
wind energy and 15% for solar energy.

After multiplying the respective capacity factor times the $MW$ capacity of the source, we need to know how many $MWh$ are produced in a year, so:
$$
\text{MWh Each Year}=(\text{Capacity (MWh)}\times \text{Capacity Factor (\%)})\times 8760
$$
Where 8760 are the hours in a year.

To value the $MWh$ produced, we chose as an attendible benchmark the *LCOE* 
(Levelized Cost Of Energy) for that type of renewable, which indicates the minimum price
the produced energy must be sold at to break even, and is expressed in $Euro/MWh$.
$$
LCOE = \frac{\sum_{t=1}^{n} \frac{I_t + M_t + F_t}{(1 + r)^t}}{\sum_{t=1}^{n} \frac{E_t}{(1 + r)^t}}
$$
- $I_t$: Initial capital loss.
- $M_t$: Operations and maintenance costs.
- $F_t$: Fuel costs.
- $E_t$: Electricity generated ($MW$).
- $r$: Discount rate.
- $n$: Expected lifetime.

In alternative, we can see that a capture price benchmark could give a more honest overview of a power plant's energy generation and its possible value for the market.
For renewables in particular, it accounts for the implant's overgeneration and undergeneration respectively during peak hours in which other similar implants may also provide electricity for the electric grid which would then be overcharged, and the generated power wasted, and low generation hours (like at night for solar panels or during less windy days for the wind turbines).
$$
\text{Capture Price}=\frac{\sum_{i=1}^n (\text{Electricity Sold (MWh)}\times \text{Market Price (MWh)})} {\sum_{i=1}^n \text{Electricity Sold (MWh)}}
$$
The capture price represents the average price per $MWh$ the producer gets selling
the electricity they produced.
Like the LCOE, prices are allowed to fluctuate.

#### PLACEHOLDER BIBLIOGRAPHY, <u>needs to follow standard</u>
[buisnessnorway.com](https://businessnorway.com/articles/wind-speed-for-wind-turbines-unlocking-optimal-output)\
[opura.com](https://opoura.com/energy-explained-learning-hub/wind-turbine-capacity-factor/)\
[windeurope.org](https://windeurope.org/about-wind/daily-wind/capacity-factors)\
[atlanteeolico](https://atlanteeolico.rse-web.it/html/help/help-terria-calcolo)\
[iea-wind.org](https://iea-wind.org/annual-report-2025-italy)\
[iea-pvps.org](https://iea-pvps.org/national_survey/nsr-italy-2024)\
[energy.gov](https://www.energy.gov/cmei/systems/solar-photovoltaic-system-cost-benchmarks)\
[fotovoltaico.it](https://fotovoltaicoinfo.it/guide/quanto-produce-impianto-fotovoltaico)\
[joint research centre](https://joint-research-centre.ec.europa.eu/photovoltaic-geographical-information-system-pvgis/using-pvgis-5/pvgis-5-user-manual_en)\
[euenergy](https://euenergy.live/it)\
[gokinsolar.com](https://www.gokinsolar.com/en/news/Solar-Power-Plant-Cost-per-MW-2025-Benchmarks-and-2026-Outlook-for-EPCs-and-Developers)\
[energysage.com](www.energysage.com/solar/solar-panels-work/)\
[Enlitia.com](https://www.enlitia.com/resources-blog-post/capture-price-definition)\
[Taishan](https://taishantransformer.com/transformers-support-renewable-energy/)