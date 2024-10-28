### -> submitter ORCID (or name)

https://orcid.org/0000-0001-7649-4498

### -> slug

cenki-tok-2020-crustal-roots-in-stable-continents

### -> license

CC-BY-4.0

### -> alternative license URL

_No response_

### -> model category

model published in study

### -> model status

completed

### -> associated publication DOI

https://doi.org/10.1130/G47301.1

### -> model creators

0000-0001-7649-4498
0000-0002-1767-8593
0000-0001-6773-0807

### -> title

_No response_

### -> description

Away from tectonically active regions, the continental crust has an average thickness of 40 ± 1 km. Yet, it shows a remarkable variability from 25 to 65 km, comparable to that of the most tectonically active regions. Here, we consider the problem of the formation and preservation of anomalous deep crustal roots in stable intracontinental regions. Using two- dimensional thermomechanical experiments, we show that the interplay between partial melting, the formation of garnet-pyroxene-bearing rocks, and their strain rate–dependent retrogression result in the preservation of thick and strong crustal roots. We argue that it is the partitioning into narrow regions of strain, retrogression, and weakening coupled into a positive feedback loop that explains why strong high-grade crustal roots remain largely immune to gravitational stresses and are able to persist over hundreds of millions of years.

### -> abstract

_No response_

### -> scientific keywords

_No response_

### -> funder

https://ror.org/02wbb9367, 793978

### -> model embargo?

_No response_

### -> include model code ?

- [X] yes

### -> model code/inputs DOI

https://github.com/underworld-community/cenki-tok-et-al-crustal-roots-in-stable-continents

### -> model code/inputs notes

_No response_

### -> include model output data?

- [X] yes

### -> data creators

_No response_

### -> model output data DOI

_No response_

### -> model output data notes

_No response_

### -> model output data size

_No response_

### -> software framework DOI/URI

Underworld 2 version 2.8.5

### -> software framework source repository

_No response_

### -> name of primary software framework (e.g. Underworld, ASPECT, Badlands, OpenFOAM)

Underworld 2

### -> software framework authors

_No response_

### -> software & algorithm keywords

Python, Finite Element

### -> computer URI/DOI

_No response_

### -> add landing page image and caption


![459D1B30-8E88-4E84-81CE-3201350F335A](https://github.com/user-attachments/assets/7fdc3017-5c3e-4cd4-b3cf-cbbea680f35d)

Fast modeling results (1.8 cm.y-1 extension speed) at an average strain rate of 3e-15 s-1 and 25 % extension. Colors are the same as in Fig 2. Model a. Only partial melting is allowed (garnet-pyroxene isograde and retrogression into amphibolite are removed). Model b. Partial melting, crystallization of garnet-pyroxene assemblages and retrogression are allowed. The temperature for the transformation of the continental crust into garnet-pyroxene rich rocks is 777 °C (see text for explanation). The reference temperatures for the solidus of the continental crust and the garnet-pyroxene rich crust are 650 °C and 790 °C, respectively. Model c. Same as model b but the temperature for the continental crust solidus is increased to 720 °C. Model d.  Zoom on model b illustrating the velocity field (black arrows) when the boundary condition mimicking extension is removed (after 2 Myr of gravity forces operating) showing that the partially molten crust flows while garnet-pyroxene rich rocks do not.


### -> add an animation (if relevant)

![GeolMov](https://github.com/user-attachments/assets/8c81a215-e36f-45ae-a9ec-a76b432048ea)


### -> add a graphic abstract figure (if relevant)

![459D1B30-8E88-4E84-81CE-3201350F335A](https://github.com/user-attachments/assets/5091e451-07ac-433b-a3dc-7386cfdce647)

Fast modeling results (1.8 cm.y-1 extension speed) at an average strain rate of 3e-15 s-1 and 25 % extension. Colors are the same as in Fig 2. Model a. Only partial melting is allowed (garnet-pyroxene isograde and retrogression into amphibolite are removed). Model b. Partial melting, crystallization of garnet-pyroxene assemblages and retrogression are allowed. The temperature for the transformation of the continental crust into garnet-pyroxene rich rocks is 777 °C (see text for explanation). The reference temperatures for the solidus of the continental crust and the garnet-pyroxene rich crust are 650 °C and 790 °C, respectively. Model c. Same as model b but the temperature for the continental crust solidus is increased to 720 °C. Model d.  Zoom on model b illustrating the velocity field (black arrows) when the boundary condition mimicking extension is removed (after 2 Myr of gravity forces operating) showing that the partially molten crust flows while garnet-pyroxene rich rocks do not.

### -> add a model setup figure (if relevant)

![5F6DD5CC-DF90-4860-8E76-6AA35305A50B](https://github.com/user-attachments/assets/f5452714-536e-44d6-ae4b-496947412d81)

Model geometry, initial conditions as well as geotherm, viscosity and density profiles. A weak prismatic region dipping 45° simulates a detachment fault in upper crust. The circles pattern superimposed on the continental crust represents the finite strain ellipses. 

### -> add a description of your model setup

Our 2D thermo-mechanical experiments consider a 360 km wide orogenic plateau with a 70 km thick crust (i.e. the thickness of the Tibetan plateau, Nabelek et al., 2009) above 40 km of mantle (Fig.2). A layer of air-like material with low-viscosity and low-density is imposed on top of the crust to accommodate the development of surface topography. The plateau is experiencing extensional deformation as the crust returns to a normal thermo-mechanical state. Extensional velocity boundary conditions are imposed on both vertical walls of the model. We have tested slow (0.18 cm.y-1) and fast (1.8 cm.y-1) velocities, delivering a strain rate averaged over the length of the model of 3e-16 s-1 and 3e-15 s-1 respectively. Horizontal boundaries of the model are free slips. The thermal properties of the material combined with constant basal heat flow and constant top temperature deliver an initial steady-state geotherm leading to a Moho temperature of ca. 900 °C (Fig. 2). We select from the literature plausible visco-plastic parameters (Suppl Data) so the mechanical behavior of the modeled lithosphere depends on temperature, strain rate, deviatoric stress and accumulated strain. Details of modeling procedures, rheological and thermal parameters as well as the input python script are available in GSA Data Repository*. 
In order to explore the interplay between partial melting, the formation of stronger garnet-pyroxene bearing rocks and their retrogression into weaker amphibolite facies rocks we parameterize three first-order metamorphic phase transitions. The first phase change simulates partial melting and its feedback on density, viscosity and temperature (Rey et al., 2009, Suppl Data).  A second phase change with feedback on density and viscosity occurs at T = 1050 K to simulate prograde amphibolite to garnet-pyroxene rock reaction (Philpotts and Ague, 2009). Finally, a third phase change with feedback on density and viscosity accounts for the retrogression of garnet-pyroxene bearing rocks back into amphibolite facies rocks. This third phase change occurs at T = 1050 K as well and for a strain rate ≥ 10-14 s-1. Our model implicitly assume that water is available. Therefore, retrogression is contingent upon strain rate, which simulates the metastability of dry high-grade rocks during exhumation. This strain rate threshold is in the range of expected strain rates measured in orogenic shear zones (Sassier et al., 2009; Boutonnet et al., 2013; Faregeng and Biggs, 2018). Rock solidus depends on their fertility and availability of fluid. Hence, we have tested different solidus for the continental crust and the garnet-pyroxene-bearing rocks (Suppl Data) in the range commonly accepted for these rock types. For the continental crust we have tested a solidus representative of fertile metapelites with a melting temperature at room pressure of 923 K (Fig. 3a, b; White et al., 2001), and a solidus representative of less fertile rocks with a melting temperature at room pressure of 993 K (Fig. 3c; Rey and Müller, 2010). For the dry garnet-pyroxene-bearing crust, we use a melting temperature at room pressure of 1063 K representative of refractory granulites (Cenki-Tok et al., 2016). We use Underworld, a well-tested open source finite element code, to solve the equations of conservation of momentum, mass and energy for an incompressible fluid on a Cartesian Eulerian mesh (Moresi et al., 2007; Beucher et al., 2019). 


### Please provide any feedback on the model submission process?

_No response_