# osrs-ping-checker

Run `./osrs_pingchecker.sh` or `bash osrs_pingchecker.sh` from your chosen command line tool.

Note: The RuneScape worlds in the client (or RuneLite) are incremented by 300. i.e., To log into what the script calls "World 1", select World 301 in the client. This is because the url "oldschool1.runescape.com" corresponds with World 301 in the Old School client.

### TODO:
*Configure script to print the world number and average ping on the same line (rework echo and ping commands).*
*Allow printing of servers whose latency fall below a user-inputted threshold. e.g., set 50ms as the upper limit*
*Allow printing of most optimal 5/10/15 servers*
