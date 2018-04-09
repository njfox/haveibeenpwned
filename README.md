# haveibeenpwned
Python script to verify multiple email addresses for pwnage

usage:
  -h, --help   show this help message and exit
  -a ADDRESS   Single email address to be checked
  -f FILENAME  File to be checked with one email addresses per line

This tool respects the rate limit (HTTP 429) and adjusts accordingly.
Output is in color to show the differences between breached and not breached.

Example output:
```
$ ./haveibeenpwned.py
info@example.com: 2844Breaches 8tracks Adobe AntiPublic Disqus Dropbox Evony ExploitIn HeroesOfNewerth HoundDawgs iMesh Lastfm LinkedIn MySpace Neopets OnlinerSpambot Staminus Stratfor Trillian Tumblr Parapa 
example@example.com: 000webhost 2844Breaches AbuseWithUs Adobe AntiPublic ArmyForceOnline B2BUSABusinesses Bell2017 BitcoinTalk Bitly Bolt BTCE CafeMom CouponMomAndArmorGames CrossFire Dailymotion DaniWeb Disqus DLH Dodonew Dominos Dropbox Elance Evony ExploitIn FashionFantasyGame FFShrine FlashFlashRevolution Funimation GeekedIn GFAN Playgar HeroesOfNewerth HIAPK HoundDawgs iDressup iMesh Interpals iPmart KMRU Lastfm Leet Lifeboat LinkedIn MallCZ ModernBusinessSolutions MPGH MrExcel myRepoSpace MySpace Neopets NetEase Neteller NextGenUpdate NexusMods Nihonomaru OnlinerSpambot Onverse OpenCSGO PokemonCreed PSPISO QIP QuinStreet R2Games Reverb-Nation RiverCityMedia Shotbow Staminus Stratfor SweClockers Taobao TheTVDB Tianya TorrentInvites Trillian Tumblr uTorrent uuu9 VK WeHeartIt WHMCS Wishbone xat Xbox-Scene XPGameSaves XSplit Zomato Parapa SprashivaiRu 

```