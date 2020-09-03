# BulkerCo

<img src="https://github.com/bigaykevin/bulkerco/blob/master/ship-condition.jpg" width="700">
<img src="https://github.com/bigaykevin/bulkerco/blob/master/ballast-console.jpg" width="700">

## Introduction

BulkerCo is a desktop application targeted as cargo and ballast simulator for bulk carrier ships. It aims to be a training simulator targeted towards aspiring deck officers for familiarization of the ballast system and bulk cargo operation. Officers can track the flow of water in each pipe, sounding in each ballast tank, and pump mechanics all the while being affected by trim and list of the ship during cargo operation. Consequently, officers will be acquainted with the nature of sea water in the ballast system.
<br><br> BulkerCo performs extended period simulation of seawater within the ship's ballast systems which consist of pipes, junctions, pumps, valves, ballast tanks and eductors. A progress report will be shown at the end of simulation corresponding to the effectiveness of ballast plan, ship’s strength throughout the operation, pump efficiency and many more. 
<br><br> The project utilizes similar  algorithms and analysis techniques used in EPANET, a widely used water distribution system modelling.  Accurate physical behaviour of ballast water in the pipe system simulation is precisely achieved.

## Get Started
This ReadMe is directed towards those interested in contributing to/acquiring the project. A quick overview about where BulkerCo is at in its development. Estimated app development is at 60%.

## Features
- [x] Draft, Trim and Displacement Calculations
- [x] Stability Calculation
- [x] Strength Calculation
- [x] Condition Monitor/Visual graphs
- [x] Ballasting
- [x] Pipe Network Analysis (Pipe Flow Calculation)
- [x] Ballast Pumps
- [x] Ballast Console
- [x] Ballast Gauges/Curves
- [x] Cargo Sequence
- [x] Cargo Loading
#### Next in development...
- [ ] Ballast Eductor
- [ ] Stripping
- [ ] Bunkering
- [ ] Water Hammering
- [ ] Progress Reports
- [ ] Trimming Stage/Calculation
- [ ] Alarms
- [ ] Training Prompts
- [ ] Cape-size Bulk Carriers
- [ ] Cargo Discharging
- [ ] Loading Sequence Plan

<img src="https://github.com/bigaykevin/bulkerco/blob/master/ship-condition.gif" width="500">
<img src="https://github.com/bigaykevin/bulkerco/blob/master/ballast-console.gif" width="500"">

## Development
The user interface in BulkerCo app currently leverages ElectronJS with possible porting to Rust Webview in the future. 
##### Frontend
* Javascipt ES6
* CSS
##### Backend
* NodeJS for communication with frontend and Rust
* Rust for multithreading and intensive calculations

## Vision 
BulkerCo aims to be an all-around ship simulator and to be a close-to-reality virtual ballast operation so officers/mates can appropriately refine their skills and use them onboard.



<img src="https://github.com/bigaykevin/bulkerco/blob/master/cargo-ops.png" width="600">

### Contact
bigaykevin@gmail.com

