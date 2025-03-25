**fennel_x4b.h**: current LiveOcean BGC (as in 2025.Mar)

**fennel_x9b.h**: revised LiveOcean BGC with three new CPP flags - `INCREASE_ATTSW`, `INCREASE_NO3LOSS`, `BURY`; All three modifications are effective only within the Salish Sea, as the spatial extent defined by Aurora.
- INCREASE_ATTSW: in Salish, AttSW increases from 0.05 to 0.15 m-1, which is also employed in cas7_t0_x4b
- INCREASE_NO3LOSS: NO3loss increases from 1.2 to 2.4
- BURY: bury % of sinking large and small detritus (both N and C), use bury_region to define the perecentage.

**cas7_t0_x9b**: with `INCREASE_ATTSW` and `BURY` (50%) activated
