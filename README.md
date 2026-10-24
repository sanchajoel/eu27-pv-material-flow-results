# EU27 Photovoltaic Deployment and Material-Flow Results

This repository contains the figures and numerical outputs produced for the Master's dissertation "Modelling Photovoltaic Deployment, Material Demand and End-of-Life Management in the European Union until 2050" developed by Sancha Isabel Silva Joel at Instituto Superior Técnico.

The study applies a dynamic, geographically resolved and cohort-based material flow model to photovoltaic deployment across the 27 Member States of the European Union. It assesses photovoltaic capacity deployment, technology evolution, material demand, in-use stocks, end-of-life flows, collection and material recovery between 2000 and 2050. The analysis also includes an assessment of regional photovoltaic recycling infrastructure and a comparison between stationary battery requirements and the potential availability of second-life electric-vehicle batteries.

## Repository contents

The repository is organised into two folders:
- `figures/` contains the final figures presented in the dissertation and its appendices, as well as extra ones.
- `tables/` contains the corresponding numerical outputs in CSV format, including the data underlying the figures and the tables presented in the dissertation. The CSV files retain a machine-readable numerical format. Consequently, decimal points are used in the files even where the dissertation presents values using decimal commas.

## Scenario notation

The photovoltaic scenarios combine three dimensions:
- photovoltaic deployment pathway: accelerated (`A`), central (`B`) or constrained (`C`);
- technology evolution pathway: accelerated (`1`), central (`2`) or constrained (`3`);
- year in which the Waste Electrical and Electronic Equipment collection and module recycling pathway targets are reached: 2030 (`30`) or 2050 (`50`).

The reference case is `A.1.30`, which combines accelerated photovoltaic deployment, accelerated technology evolution and achievement of the Waste Electrical and Electronic Equipment targets in 2030.

The battery extension combines the accelerated, central and constrained photovoltaic deployment pathways with either the Net Zero Emissions High Reuse pathway (`NZE`) or the Announced Pledges Scenario Low Reuse pathway (`APS`).

## Materials covered

The material flow analysis covers:
- aluminium;
- copper;
- glass;
- silicon;
- silver;
- cadmium;
- tellurium.

## Important interpretation notes

Generated, collected and recovered end-of-life material represent different stages of the material management chain and should not be interpreted as equivalent quantities.

The recycling infrastructure analysis uses the collected mass of the seven tracked materials as a proxy for facility throughput. This quantity is referred to as "collected tracked-material mass". It does not represent complete photovoltaic module mass or recovered material mass.

The second-life battery results compare the required stationary battery stock with the potentially available second-life EV battery stock. They do not assume that all potentially available batteries are technically or economically suitable for stationary use.

The results should be interpreted together with the methodology, assumptions and limitations presented in the dissertation.