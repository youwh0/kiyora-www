# www.kiyoramaldives.infinitevoid.work

GitHub Pages site that sends visitors of `www.kiyoramaldives.infinitevoid.work`
to the shop at https://kiyoramaldives.infinitevoid.work, keeping the page they
asked for (`404.html` catches every path). It lives here, not on the shop's
server, so the www name doesn't reveal that server's address: Cloudflare's free
certificate can't cover a name two levels under infinitevoid.work, so this
record is DNS only.

DNS (Cloudflare, infinitevoid.work): `CNAME www.kiyoramaldives -> youwh0.github.io`, DNS only.
