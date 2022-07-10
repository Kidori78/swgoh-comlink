# swgoh-comlink
[DiscordChannel](https://discord.gg/)

## Deploy with Heroku steps
### 1. Click the button below.
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?button-url=https%3A%2F%2Fgithub.com%2FKidori78%2Fswgoh-comlink&template=https%3A%2F%2Fgithub.com%2FKidori78%2Fswgoh-comlink)

### 2. Create the application with a unique name and press `Deploy app` button.
![ScreenShot](assets/create-app.png)

### 3. Once deployed press `Manage App` button.
![ScreenShot](assets/app-deployed.png)

### 4. Go to settings tab.
![ScreenShot](assets/go-to-settings-tab.png)

### 5. Press `Reveal Config Vars` button and set environment variables.
![ScreenShot](assets/set-env-variables.png)

#### Environment variables:

|Variable Name| Description                             | Notes |
|-------------|-----------------------------------------|------ |
|APP_NAME | `your_app_name`                 | Required|

### 6. Check to see if the Dyno is running, if not activate it under the `Resources tab`.
![ScreenShot](assets/activate-worker-resource.png)

### 7. Check logs under `More -> View logs` for any errors.
![ScreenShot](assets/check-logs.png)
