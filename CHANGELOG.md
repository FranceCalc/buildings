# Changelog

## Unreleased

### Added
- Cost calculation: capex and opex for appliances
### Changed
### Removed


## 2.1

### added
- floor area checks

### changed
- implemented naming changes in the GTAP interface
- changed interface naming with lifestyles from % to factor and corrected the calculation
- changed interface naming with minerals and with industry

### Fixed 
- calibration error for solid bio : energy carrier instead of energy carrier cal  in joiner
- decentral values for energy demand in unrenovated, renovated and newly constructed buildings
- usage of calibrated values for energy demand heating
- pipes calculation GWh instead of TWh for energy need



## 2.0
### added
- implemented to detailed calibration based on fuel type and use, using the new calibration data load from JRC-IDEES (Energy) and EUROSTAT (Emissions)
- added the interface to GTAP



## 1.8

### Added
- calculation of energy need based on renovation
### Changed
- dataWriter dhg output names for climate and agriculture
- pipes calculation
- accumulation of demolished, renovated and constructed floor area 


## 1.6

### Added
- NEW INPUT FILES  renovation rate to the building insulation lever (levers & ports remain)
- NEW INPUT FILES  renovation mix to the building insulation lever (levers & ports remain)
- NEW INPUT FILES  destruction rate to the building insulation lever (levers & ports remain)
- NEW INPUT FILES  renovation energy achieved to the building fixed assumptions (levers & ports remain)
- NEW INPUT FILES  construction mix to the building insulation lever (levers & ports remain)
### Changed
- calculation is now pivoted; old calculation remains so far as comparison and will be removed later
- due to the additional granularity the single lever interpolation may takes a lot of time
- heating-technology-fuel share ots and ll has been enhanced with details for countries and evolution
- renovation rate for buildings is now dependent on building insulation lever level
- destruction rate for buildings is now dependent on building insulation lever level
- construction rate for buildings is now calculated 
- industry production demand is now depending on these dynamic rates


## 1.5

### Added
- product substitution evolution interface with lifetime 
- climate interface for temperature, windspeed and solarradiation
- cost calculation for appliances and for renovation
- input data for the one-zone building simulation
### Changed
- update of climate metadata


## 1.4

### Added
- Post-0.9 adds
- example input from electricity supply from JRC IDEES data 
- established input interfaces from industry and electricity
### Changed
- separated the district heating module to prevent loops
- established district heating googlesheet for interfaces and nodes in  KNIME to fill it
### Fixed 
- district heating input from buildings module

## 1.3 

### Added
- building type granularity for emissions and energy
- calculations for non-residential
- district heating calculations
### Changed
- visual steps for each calculation
- output for industry does now contain floor area for new buildings and surface area of only walls for renovations
- unit for energy demand in buildings is now largely GWh
- unit for floor area in buildings is now largely Mm2
	
## 1.2 

### Added
- added non-residential	building types
- District heating calculation
### Fixed
- fixed energy and emission calibration	

## 0.92
- added co2 emission calculation in buildings

## 0.91 Oct 15th
- added calculation of new appliances, therefore included appliance ownership in number per household, appliance usage in hours per year
- added calculation of surface area for building components 
- added non-residential floor area 
	
## 0.9 Oct1st
- Initial version, integrating all modules





