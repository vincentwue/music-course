# Music Course

A browser-based piano fundamentals course with short lessons, guided explanations, and lightweight interactive practice.

[Open the course](https://vincentwue.github.io/music-course/#/music/course)

## Overview

Music Course presents beginner-friendly keyboard theory as a sequence of focused lessons. The published experience walks through natural notes, sharps and flats, half steps, octaves, finding C quickly, and early interval work, then reinforces those ideas with small practice drills.

## Included Content

- Course landing page with lesson navigation
- Natural notes lesson and practice
- Sharps and flats lesson and practice
- Half-step and octave lessons
- "Find C quickly" keyboard-orientation lesson
- Interval introduction and follow-up lessons
- Command-palette based lesson jumping inside the web app

## Repository Structure

This repository currently contains the published static site assets rather than the authoring source project. The main items are:

- `index.html` and `404.html` for GitHub Pages routing
- `assets/` for the shipped bundle
- `dist/` for the Pages deployment artifact
- `.github/workflows/deploy-pages.yml` for automatic publishing

## Local Preview

Because this repo is already static output, you can preview it with any simple file server that serves the repository root or the `dist/` directory.

## Deployment

Pushes to `main` trigger the GitHub Pages workflow in [`.github/workflows/deploy-pages.yml`](.github/workflows/deploy-pages.yml), which uploads `dist/` and publishes the course site automatically.
