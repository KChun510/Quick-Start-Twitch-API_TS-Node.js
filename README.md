# Quick Start Twitch API (TS + Node.js)
Boiler plate code to get you started making API request to Twitch.
**Including Automatic OAuth 2.0 Access Token Refreshing.**

## Dependencies
1. **NPM**
    - [Installing NPM](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
2. **TypeScript**
    - [Installing TS](https://www.npmjs.com/package/typescript)

## Usage
1. Create a Twitch Dev Account.
    - [Twitch Dev Console](https://dev.twitch.tv/)
2. Navigate to Twitch dev console, follow these steps to get your ClientID & ClientSecret.
    - [Register App Steps](https://dev.twitch.tv/docs/authentication/register-app/)
3. Paste your ClientID & ClientSecret into .env-example, and rename it to .env.
4. Install NPM Packages.

     > `npm install`

4. Compile and Run twitchAPI.ts.

     > `npx tsx twitchAPI.ts` 
     >  -or-
     > `npx tsc twitchAPI.ts && node twitchAPI.js`

Thats it, start making request!

[List of Twitch EndPoints](https://dev.twitch.tv/docs/api/reference/)


