
# Reliability-Based Sizing of Islanded Multi-Energy Microgrid: A Conic Chance-Constrained Optimization Approach

Data available for the paper called Reliability-Based Sizing of Islanded Multi-Energy Microgrid: A Conic Chance-Constrained Optimization Approach

# Info available

### hourly_data.csv: 
Shows the whole year (hourly basis) data used in the optimization

### parameters.csv:
Shows the parameters used in the study cases

## Results

### Basecase:
1. dispatchbaseCase: Shows the electric dispatch for the generator available in the microgrid in the basecase.
2. dispatchCoolingBasecase: Shows the dispatch for the cooling technologies in the basecase
3. SOCBasecase: Shows the *state-of-charge* for the storage (BESS and TESS) technologies available
4. SpinningReservesBasecase: Shows the Up/Down spinning reserve requirements and the scheduled spinning reserve for each technology

### Reliability-based case:*
1. dispatch: 
Shows the electric dispatch for the generator available in the microgrid in the reliability-based case.
2. dispatchCooling: 
Shows the dispatch for the cooling technologies in the reliability-based case
3. SOC: 
Shows the *state-of-charge* for the storage (BESS and TESS) technologies available
4. SpinningReserves: 
Shows the Up/Down spinning reserve requirements and the scheduled spinning reserve for each technology
5. OutageReserves: 
Shows the reserve requirements againts N-1 outages. The scheduled N-1 reserves for each technology is also shown
6. DSL-limits:
Shows the scheduled power output for the Diesel generator, the scheduled assigned reserves (N-1 reserves, up and down spinning reserves). This charts shows how never the scheduled power surpases the operational limits
7. BESS-limits:
Shows the scheduled charge/discharge for the Battery Energys Storage System, the scheduled assigned reserves (N-1 reserves, up and down spinning reserves). This charts shows how never the scheduled charge/discharge and reserves surpases neither the available stored energy limits nor available remaining power output limit.
8. Sizes: Shows the sized for each technology in the reliability-based case
