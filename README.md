# crypto-bot dashboard

A single-file static dashboard for a GitHub-Actions-based trading bot.
It contains **no data and no credentials** — at runtime it reads the bot's
state from a private GitHub repository using a fine-grained personal access
token that the viewer supplies and that is stored only in their own browser
(localStorage).

Capabilities: equity chart with buy-and-hold comparison, position/status
display, pause/resume, run-now, emergency liquidation, paper/live mode
switch. Strategy parameters are shown read-only (locked by design).
