
### hey, i'm sal

3rd year comp sci @ uc santa cruz. i do data and simulation for [formula slug](https://github.com/formulaslug), ucsc's fsae electric race car team. long term i want to work in motorsport, ideally formula 1.

**interests**: vehicle dynamics and simulation · data analysis and machine learning · game dev · cybersecurity

**what i'm working on**
- **yaw rate modeling**: building a physics model of how the car rotates (steering, speed, tire loads) and validating it against logged fs-3 data
**things i've built**
- **laptime sim**: a quasi-steady-state laptime simulator for formula slug, plus research docs on sim methods
- **fault detection**: xgboost model predicting motor controller fault events from telemetry (the hard part: super imbalanced classes)
- **driver-in-loop sim:** the unity side of our driving simulator, which hooks into the team's python vehicle model. i added the FS-4 model with spinning and steering wheels, a live dashboard, a lap timing screen for autocross, accel and skidpad, three camera views, and car sound generated from the drivetrain math
- **[f1 25 discord rich presence](https://github.com/zoldival/f1-discord-presence):** a tray app that reads f1 25's udp telemetry and shows your mode, track, team and position on your discord profile. decodes the raw packets byte by byte, with custom track outlines and team badges for each one (will receive consistent updates)

**tools**: python · c · lua · javascript · sql · pandas · numpy · matplotlib · jupyter · xgboost · pyinstaller · unity · roblox studio · git · github · github actions · linux

**skills**: udp telemetry · binary packet parsing · discord rpc · machine learning · vehicle dynamics
