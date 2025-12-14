# Pet Services Voice Agent (Square Integration)

## Overview
Voice agent for pet grooming and care services (e.g., Toronto Pets). Handles booking nail care, grooming, vet checkups with staff and location selection. Full integration with Square Appointments via **n8n**.

## Features
- Service selection (nail care, grooming, boarding)
- Staff assignment (e.g., Sarah Khan, Shaheer)
- Location selection
- Real-time availability and booking in Square
- Error fallback: transfer to human if API fails repeatedly

## Tech Stack
- **Voice Agent**: Retell AI
- **Workflows**: n8n → Square
- **SMS**: Twilio

## Setup Instructions
1. Connect Square via n8n workflow nodes.
2. Import agent configuration into Retell AI.
3. Set location and staff IDs.

## Usage
- "Book dog nail care tomorrow at 12 PM with Shaheer" → Agent confirms and books

## Demo
Refer to the attached `project_demo.pdf` for Square booking screenshots, Retell AI logs, n8n workflow, and call flow.

## License
MIT
