# Telegram-Based AI Service Booking System

An automated AI-powered booking agent built with **n8n**, **Groq (Llama 3)**, and **Google Sheets**. This bot handles service inquiries, displays catalogs, and manages multi-step booking conversations with session persistence.

## 🚀 Features
- **AI Intent Recognition**: Uses Groq (LLM) to understand if a user wants to book, see the catalog, or cancel.
- **Session Persistence**: Remembers user progress (name, email, etc.) using a "Sessions" Google Sheet.
- **Dynamic Catalog**: Fetches services and pricing in real-time from Google Sheets.
- **Automated Bookings**: Records confirmed appointments into a dedicated "Bookings" sheet with unique IDs.

## 🛠️ Tech Stack
- **Automation**: n8n (Self-hosted or Cloud)
- **AI Brain**: Groq Cloud (Llama 3 70B)
- **Database**: Google Sheets (Products, Bookings, Sessions)
- **Interface**: Telegram Bot API

## 📋 Example Commands
- `/catalog` - View all available services.
- `/book P001` - Start the booking process for a specific service.
- `My name is [Name]` - The bot "hears" your name and updates your session.
