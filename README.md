# bot_twitter
belajar

# bot_twitter

![MassTweet](https://i.ibb.co/F5sZ0gR/ss.png)


*** NOTE : USE AT YOUR OWN RISK! ***

## • Kegunaan
- Multi accounts
- Follow
- Like
- Retweet
- Reply
- Quote

## • Yang diperluin
- Python3
- Git
- Vscode ( biar gampang ) atau lebih prefer pake terminal langsung ya gpp serah

## • Eksekusi

```bash
git clone https://github.com/BrianBathory98/bot_twitter.git
```

## Buat token dan key nya di :
https://developer.twitter.com/en/portal/dashboard

* ikuti aja langkahnya

## • Edit Configurations *config.yaml* file, buka pake vscode enak sih tinggal edit edit aja

isi pake token, key kalian yg di dapet dari developer twitter di atas

```env
ACCOUNTS: 
  - USERNAME: user_1
    BEARER_TOKEN: AAAAAAAAAAAAAAxxxxxxxxxxx
    CONSUMER_KEY: xKvfBnz0xxxxxxxxxxxxxxxxx
    CONSUMER_SECRET: aWZe8qZh2Kxxxxxxxxxxxx
    ACCESS_TOKEN: 1387755xxxxxxxxxxxxxxxxxx
    ACCESS_TOKEN_SECRET: EiJ8Y3kZxxxxxxxxxx
    TEXT: "Join guys @mention1 @mention2 #solana #BTC"
  - USERNAME: user_2
    BEARER_TOKEN: AAAAAAAAAAAAAAxxxxxxxxxxx
    CONSUMER_KEY: xKvfBnz0xxxxxxxxxxxxxxxxx
    CONSUMER_SECRET: aWZe8qZh2Kxxxxxxxxxxxx
    ACCESS_TOKEN: 1387755xxxxxxxxxxxxxxxxxx
    ACCESS_TOKEN_SECRET: EiJ8Y3kZxxxxxxxxxx
    TEXT: "Join guys @mention1 @mention2 #solana #BTC"
```

## • Jalanin ?
```bash
cd MassTweet
pip install -r requirements.txt
python bot.py
```
