# EssencePointSystem
Using Streamerbot's Multi-Platform Point System to create a Interactive Stream Equal to Twitch on YouTube! All redeems are done by using command prompts, no Chrome Extension Needed! This is my public build of it, to back up my current code of it and to display the command list for viewers.

---

Command List - Main Variables !aki, !floof
| Command List                    | Commands (With or Without Spaces)                                       |
| ------------------------------ | -------------------------------------------- |
| Color Toggle (Affects Model and Mascot or both)   ```cyan, green, blue, purple```                        | ```!colorall, !color all, "!floof/!aki" color, !color "floof/aki" ``` |
| Endpoint                       | `wss://youtube.redeems.live/ws`                     |
| Auto Connect on Startup        | ✅                                           |
| Reconnect on Disconnect        | ✅                                           |
| TLS (tick the following boxes) | ✅ `TLS 1.0`<br>✅ `TLS 1.1`<br>✅ `TLS 1.2` |
| Retry Interval                 | `5 seconds`                                  |

| Actions      |                                 |
| ------------ | ------------------------------- |
| Connected    | `Set Channel Rewards`           |
| Disconnected | `NONE`                          |
| Message      | `Execute Channel Reward Redeem` |
