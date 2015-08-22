# Roda example app

#### a more advanced example than  https://github.com/makevoid/roda_example_app/tree/70ca3e8c15b20a3b91e8374d210b341d859f212d

example app in Roda, routing tree microframework:

#### http://roda.jeremyevans.net

running on mbp retina 2.2ghz linux ubuntu quad core

rack env set to production (obviously)

roda:

    20k request/sec

vs

sinatra:

    4k req/sec

---

### running it:

    RACK_ENV=production puma


requirements:

    gem i bundler

    bundle
