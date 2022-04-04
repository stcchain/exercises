# WaterPotabilityMetrics

Water potability data model is intended to represent water quality parameters at a certain water mass (river,  lake, sea, etc.) section. For the puspose of indicating if water is safe for human consumption
-  `pH`: Acidity or basicity of an aqueous solution. WHO has recommended maximum permissible limit of pH from 6.5 to 8.5.
   -  Attribute type: **Property**.
   -  Optional
-  `Hardness`: The amount of dissolved calcium and magnesium in the water.
   -  Attribute type: **Property**.
   -  Optional
-  `Solids`: Total dissolved solids. Desirable limit for TDS is 500 mg/l and maximum limit is 1000 mg/l which prescribed for drinking purpose.
   -  Attribute type: **Property**.
   -  Optional
-  `Chloramines`: Disinfectants used to treat drinking water. Chlorine levels up to 4 milligrams per liter (mg/L or 4 parts per million (ppm)) are considered safe in drinking water.
   -  Attribute type: **Property**.
   -  Optional
-  `Sulfate`: Concentration of sulfate. Sulfate concentration in seawater is about 2,700 milligrams per liter (mg/L). It ranges from 3 to 30 mg/L in most freshwater supplies, although much higher concentrations (1000 mg/L) are found in some geographic locations.
   -  Attribute type: **Property**.
   -  Optional
-  `Conductivity`: Electrical Conductivity. According to WHO standards, EC value should not exceeded 400 μS/cm.
   -  Attribute type: **Property**.
   -  Optional
-  `Organic_carbon`: Measure of the total amount of carbon in organic compounds in pure water. According to US EPA < 2 mg/L as TOC in treated / drinking water, and < 4 mg/Lit in source water which is use for treatment.
   -  Attribute type: **Property**.
   -  Optional
-  `Trihalomethanes`: THMs are chemicals which may be found in water treated with chlorine. THM levels up to 80 ppm is considered safe in drinking water.
   -  Attribute type: **Property**.
   -  Optional
-  `Turbidity`: Amount of light scattered by particles in the water column. The mean turbidity value obtained for Wondo Genet Campus (0.98 NTU) is lower than the WHO recommended value of 5.00 NTU.
   -  Attribute type: **Property**.
   -  Optional
-  `Potability`: Indicates if water is safe for human consumption where 1 means Potable and 0 means Not potable.
   -  Attribute type: **Property**.
   -  Optional



## Examples

### OK
