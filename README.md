# Mobile Trading QA Lab

Mobile automation portfolio project for a simulated trading application.

The goal of this project is to demonstrate how native mobile application testing can be approached from a QA/SDET perspective, using Android Emulator, Maestro and later Appium.

## Project purpose

This project focuses on mobile end-to-end testing scenarios for a demo trading app.

It is not connected to any real bank, broker, trading platform or production API. All data and flows are simulated for learning and portfolio purposes.

## Planned scope

- Demo mobile trading application
- Android Emulator based test execution
- Maestro mobile E2E tests
- Trading-related user flows
- Mobile-specific scenarios
- Risk-based QA documentation
- Optional Appium + TypeScript layer in a later phase

## Core user flows

Planned mobile flows include:

- Login
- Dashboard
- Portfolio overview
- Instrument details
- Buy order flow
- Order confirmation
- Order history
- Logout

## Testing focus

The project will focus on risks typical for mobile banking and trading applications:

- incorrect order flow behavior
- insufficient funds validation
- duplicated order prevention
- session handling
- sensitive data visibility after logout
- app behavior after background / foreground
- poor network handling
- critical smoke regression on Android Emulator

## Tech stack

Planned stack:

- React Native / Expo for the demo app
- Maestro for mobile E2E tests
- Android Emulator
- GitHub Actions in a later phase
- Appium + TypeScript as an optional second automation layer

## Status

Project initialized. Demo app and first Maestro tests will be added in the next steps.
