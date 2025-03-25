**fennel_x4b.h**: current LiveOcean BGC (as in 2025.Mar)

**fennel_x9b.h**: revised LiveOcean BGC with three new CPP flags - `INCREASE_ATTSW`, `INCREASE_NO3LOSS`, `BURY`; All three modifications are effective only within the Salish Sea, as the spatial extent defined by Aurora.
- INCREASE_ATTSW: in Salish, AttSW increases from 0.05 to 0.15 m-1, which is also employed in cas7_t0_x4b
- INCREASE_NO3LOSS: NO3loss increases from 1.2 to 2.4
- BURY: bury % of sinking large and small detritus (both N and C), use bury_region to define the percentage.

**cas7_t0_x9b.pdf**: 
- defined `INCREASE_ATTSW` and `BURY` (50%)
- restart from cas7_t0_x4b on 2013.03.15
- output saved in /dat2/jxiong/LO_roms/cas7_t0_x9b/; I deleted ocean_rst.nc in some folders to reduce the storage requirement
- the pdf includes model-data comparison based on scatterred bottle data, ORCA buoy time series, and sediment core - sediment oxygen demand (SOD)
