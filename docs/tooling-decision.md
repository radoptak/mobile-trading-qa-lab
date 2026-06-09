# Tooling decision

## Context

This project is focused on mobile test automation for a simulated trading application.

The goal is to build a portfolio-ready project that demonstrates practical mobile QA skills without relying on real banking systems, paid cloud services or external production APIs.

## Initial approach

The first phase uses:

- Android Emulator
- React Native / Expo demo app
- Maestro for mobile E2E automation

## Why Android first

Android is selected as the initial platform because it allows local emulator-based testing without paid developer accounts.

This keeps the project accessible, repeatable and suitable for a public GitHub portfolio.

## Why Maestro first

Maestro is selected for the first automation layer because it allows fast creation of readable mobile E2E tests.

It is well suited for smoke and regression flows such as:

- launching the app
- logging in
- navigating between screens
- validating visible UI states
- checking critical user paths

## Why not Appium first

Appium is a strong and widely recognized mobile automation framework, but it has a higher setup and maintenance cost.

For this project, Appium is planned as a later phase after the demo app and basic mobile testing flow are stable.

## Future Appium layer

A later Appium + TypeScript layer may be added to demonstrate:

- Page Object Model for mobile screens
- reusable test helpers
- more advanced assertions
- stronger SDET-style framework design

## Decision

Start with Maestro and Android Emulator.

Add Appium later only after the mobile app and core E2E scenarios are working reliably.
