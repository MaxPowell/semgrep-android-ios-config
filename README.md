# Semgrep Android/iOS bad config rules
Semgrep regex rules to detect insecure configurations in Android or iOS. I'm trying this from the scratch and just for fun, so there may be many thigs to improve.

At the moment, semgrep can't parse XML or .plist documents, so I'm using regex to trynna catch each case. Some are customized rules, so you may need to adapt the regex to make it work for your implementation, but I'm trying to make it as generic as I can.
