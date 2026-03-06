## Workflow Logic Explained

1. **Trigger**: Telegram Message Received.
2. **AI Intent (Groq)**: The bot sends the text to Llama 3 via Groq to determine intent.
3. **Session Check**: Looks up 'telegram_user_id' in Sessions sheet.
4. **Data Retrieval**: Filters Products sheet for specific 'product_id'.
5. **Finalization**: Appends row to Bookings sheet with unique ID.
