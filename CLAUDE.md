# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A static website deployed to AWS EC2 using Terraform and Claude Code. The site displays deployment status and is served from `/website/`.

## Architecture

- `Website/index.html` — Single page with inline CSS
- `Website/image/devops.jpg` — Image asset embedded in the page

## Development

Open `Website/index.html` directly in a browser to preview locally. No server needed.

## Deployment Context

The project is intended to be deployed on AWS EC2 via Terraform. Terraform configuration files are expected to be added to this repository.
