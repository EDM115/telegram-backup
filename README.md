# telegram-backup-dump
### Backs up a whole (or not) chat/channel by forwarding to another one
  
## Usage
+ Start bot
+ Add it to the chat/channel as admin with full rights if it's private (else, not needed)
+ `/backup {id}`. {id} can be @channelname or -100×××××××
+ *(optional)* `/range ××:××`. ×× are the numbers of start:end of posts/messages backup
+ `/dump {id}` id of chat/channel where you back it up. Bot MUST be admin with full rights there
+ `/tag {on}/{off}` If you need the forward tag or either send as copy
+ `/go` HERE WE GOOOOOOOW ! Sends a message with progressbar, success/fail (fails are mostly due to deleted messages) and when it's done
  Can take less or more time depending to how many messages  
  
## Needed variables
+ `BOT_TOKEN`
I think it's enough…

## Hosting
Heroku I think…

### Framework
PyroGram gang forever 💪

### Code style
Minimalistic
