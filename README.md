# Bot for a make an appointment for a getting IND Permit

> **⚠️ Disclaimer**
>
> It just custom Node.js script which runs from terminal,
> opens browser (by Playwright),
> starts checking available date,
> choose **first available time**,
> and starts the form filling, when date is available.
> 
> It was written for my requirements without options for configure this, 
> by this reason check and fix [code](./src/index.js) 
> of finding first available date for your requirements.
> 
> Sorry. I don't have time for doing the best DX/UI for this
> and fixing all incorrect moments of the solution.

### Before running

- Install Node.js [directly](https://nodejs.org/en/) or any way you would like.
- Open Terminal in root of the project
- Run in the terminal `npm ci` (installing project dependencies)

### Running

- Open Terminal in root of the project
- Run in the terminal `npm start`
- Waiting... a notification about browser is ready
- Check that date is OK for you
- Filling and submit form by yourself
- Enjoy


