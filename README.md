# AI Receptionist — Voice Booking Agent

A voice AI system built on Vapi that answers inbound calls, checks live 
calendar availability, and books, reschedules, or cancels appointments 
during the call — no human needed for routine scheduling.

## Problem
Small businesses lose bookings when calls go unanswered outside business 
hours or during busy periods, with no way to capture and act on that 
demand automatically.

## Stack
n8n (self-hosted), Vapi AI, Google Calendar, Airtable

## How it works
- Vapi answers the call and handles the conversation in real time
- n8n receives the call data via webhook and checks Google Calendar for live availability
- Based on the caller's request, the workflow books, reschedules, or cancels the appointment
- Every call and outcome is logged to Airtable for tracking

## Status
Self-initiated build, stress-tested with realistic booking scenarios.

Full case study: https://justinrhedgep.vercel.app
