We are the data assimilation system constructed under 
the Oceanographic Modeling and Observation Network (REMO). We are
called REMO Ocean Data Assimilation System (RODAS) @rodas-remo

REMO is a research group dedicated to operational oceanography and physical oceanography
in Brazil. The REMO members are the Federal University of Bahia (UFBA), Federal University
of Rio de Janeiro (UFRJ), the Brazilian Navy Hydrography Center (CHM) and the Petrobras
research center CENPES.

RODAS was constructed by the REMO-UFBA, under the leadership of Prof. Clemente A. S. Tanajura, in
collaboration with Prof. Jiang Zhu (Institute for Atmospheric Physics, Chinese Academy of Sciences)
and other scientists envolved in the international project GODAE OceanView.

The data assimilation method employed in RODAS is the Ensemble Optimal Interpolation (EnOI) and it
is mainly based on the works by
- Evensen G (2003) The Ensemble Kalman Filter: theoretical formulation and practical implementation. Ocean Dynamics  53:343-367.
- Thacker W, Esenkov OE (2002) Assimilating XBT data into HYCOM. J Atmos Ocean Tech 19:709-724.
- Xie J, Zhu J (2010) Ensemble optimal interpolation schemes for assimilating Argo profiles into a hybrid coordinate 
ocean model. Ocean Modelling 33: 283-298.

It was developed to produce analysis increments into the Hybrid Coordinate Ocean Model (HYCOM), but it can
be adapted to be used with any ocean model, since it is a stand alone code that works separetely from the
model. It reads observations, ocean model states and the model background to calculate the Kalman Gain 
Matrix, innovation and the analysis increments. 

Details about RODAS and results can be found in
- Tanajura C.A.S., Santana A, Mignac D, Lima L, Belyaev K, Ji-Ping X (2014) The REMO Ocean Data Assimilation System 
into HYCOM (RODAS_H): General description and preliminary results. J Atmos Oceanic Sci Lett 7: 464-470.
http://159.226.119.58/aosl/EN/10.3878/j.issn.1674-2834.14.0011.
- Mignac D, Tanajura CAS, Santana A, Lima LN, Xie J (2015) Argo data assimilation into HYCOM with an EnOI 
method in the Atlantic Ocean. Ocean Sci 11:195-213. https://doi.org/10.5194/os-11-195-2015.
- Tanajura C.A.S., D. Mignac, A. N. de Santana, F. B. Costa, L. N. Lima, K. P. Belyaev, J. Zhu, 2020: Observing 
System Experiments over the Atlantic Ocean with the REMO Ocean Data Assimilation System (RODAS) into HYCOM. 
Ocean Dynamics, 52, 123-132. https://doi.org/10.1007/s10236-002-0013-8
- Santana, R., F.B. Costa, D. Mignac, A.N. Santana, V.R.S. Vidal, J. Zhu, C.A.S. Tanajura, 2020: Model sensitivity experiments 
on data assimilation, downscaling and tides for the representation of the Cape São Tomé Eddies. Ocean Dynamics, 70, 77–94. 
https://doi.org/10.1007/s10236-019-01307-w
- Carvalho J. P. S., F. B. Costa, D. Mignac, C. A. S. Tanajura, 2019: Assessing the extended-range predictability of the 
Ocean Model HYCOM with the REMO Ocean Data Assimilation System (RODAS) in the South Atlantic. Journal of Operational 
Oceanography, v.13, p.1 – 11. doi:10.1080/1755876x.2019.1606880

The goal of the GitHub area is to publicaly provide the RODAS code under the MIT license and invite students, reserchers
and professionals in operational oceanography and physical oceanography to use RODAS and help us to improve it.

<!---
rodas-remo/rodas-remo is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
