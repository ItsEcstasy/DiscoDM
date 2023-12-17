# Discord Mass Messenger

### Overview

DiscoDM is a bot that lets you send messages to specific members or to members across an entire server

# Configuration

Edit **`settings.json`** to your prefrence, You can change things like, delay between messages, set it to target specific users or an entire server server, or the amount of messages sent to each user and more

# Usage

Set up **`settings.json`**
Once setup properly and ran, It will authenticate with Discord using your bot's token and send messaging according to the set configuration

# Notes

- Make sure your bot's token is in the **`settings.config`** and has permissions to send messages
- Make sure the **`SecondDelay`** and Repetition settings arnt too fast to avoid rate limits

# Contact

if you have any questions or need help contact me
- Discord: itsjusnix
- Telegram: ItsJusNix
- Instagram: Capalot.Ecstasy

# Notes

- Everyone you plan on messaging must share a mutual server with the bot or else it wont be able to reach them
- To msg ppl in a server set **`UseMemberIDs`** & **`SaveMemberIDs`** to true (it scrapes member's discord ids in a txt and sends from there)
- To msg specific ppl add their ids in **`targets`**
- Any ids in **`exceptions`** will be skipped if found in the list or the `MemberIDs.txt`
- If you're dming more than 30 i'd suggest setting the **`SecondDelay`** higher value such as 15-20 to avoid the bot being flagged as spam (blocks it from dming)
- **`SaveMemberNames`** is a misc option still need to fix it as it saves all their names on the same line rather than separate lines
