# SCP Order Dashboard & Shipping Board
### status : developing...

## Notes
This project is a personal case study based on my experience at Parts Logistics Operations, TMT. I usually visit suppliers and found out that some of them rely on manual operations to handle daily parts orders. I always gave suggestion about `automations`, `visualizations` and `internal communications`. In this project I will try to make a sample software (web applications) based on them.

Hopefully, this project will help suppliers who receives parts orders via the SCP system to have some ideas about their daily order managements.

** This project is open to modify and use. **

## Features
- Upload daily order `.csv` and load into `sqllite` database.
- Summary of daily orders.
- Tracking order preparation progress.
- Trucks arrival board ( Daily Shipping Progress Board )

## Technologies
Project is created with:
* MongoDB : 
* Express : `4.18.1`
* ReactJS : ``
* NodeJS  : `19.0.0`

## Requirement
1. NodeJS [https://nodejs.org/en/](https://nodejs.org/en/)

## Installation (Windows)
1. Download and extract [this project](https://github.com/techaploog) or
   ```
   git clone https://github.com/techaploog/scp-dashboard.git
   ```
2. Initial and download all dependencies
   ```
   npm run install
   ```
3. Run server
   ```
   npm run deploy
   ```
4. Open browser and browse to `http://localhost:8000`
  __(linux and macOS need to update `scripts` in `package.json` before `npm run`)__

## Author
**Chaikrit Techaploog**

## Support
Contributions, issues, and feature requests are welcome!
Give a ⭐️ if you like this project!
