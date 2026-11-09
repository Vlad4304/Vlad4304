# Vladyslav Lysytskyi

I build voice AI that picks up the phone for small businesses in Germany and Ukraine.

Call the demo and talk to it: **+49 89 904225226** · [meldedirekt.de](https://meldedirekt.de)

## Meldedirekt

When nobody at a company can answer, the assistant takes the call and speaks the caller's language. The owner gets the request in WhatsApp, Telegram or by email. It knows the company's hours, prices and services. First businesses are testing it on their real phone lines.

- Real-time audio bridge between phone carriers (Telnyx, SIP, Twilio as fallback) and Gemini Live
- A config per business: greeting, languages, prices, where requests go
- Self-service signup page for a new line
- Every demo call is reviewed automatically, and a watchdog checks the bridge, the model, the carrier balance and SIP every 5 minutes

Roughly 58,000 lines of Python since September 2026, written together with Claude Code. The code is private. I'm glad to walk through the architecture on a call.

## Other projects

- **[Sluhayu](https://sluhayu.com)**: the same assistant for Ukraine, on a Ukrainian number, with a radio campaign behind it
- **[@klarDE_bot](https://t.me/klarDE_bot)**: explains German letters in Telegram and answers from a knowledge base (RAG). Takes text, photos, PDFs and voice messages
- **postbot**: drafts posts for an insurance channel on Telegram, runs legal checks and publishes from a queue every day
- **[UFC market-efficiency study](https://github.com/Vlad4304/ufc-market-efficiency)**: took an open-source XGBoost fight model, added Elo and calibration, and tested it on 1,645 fights against real odds. The market won, 70 % accuracy against the model's 62 %
- **[@HoHoCallBot](https://t.me/HoHoCallBot)**: a Telegram bot where parents order a phone call from Santa for their child
- **[@pic_restore_bot](https://t.me/pic_restore_bot)**: restores old photos in Telegram, paid with Telegram Stars

## Stack

Python · WebSockets · Gemini Live · RAG (Dify) · Telnyx · SIP · Telegram Bot API · Caddy · systemd · Debian
