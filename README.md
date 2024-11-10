# bruteforce-seed

    usage: bruteforce.py [-h] --seed SEED --address ADDRESS [--address-type {segwit,legacy}]

optional arguments:
  -h, --help            show this help message and exit
  --seed SEED           the wallet seed, consists of 24 words
  --address ADDRESS     the wallet address at 0
  --address-type {segwit,legacy}
                        the wallet address typeusage: bruteforce.py [-h] --seed SEED --address ADDRESS [--address-type {segwit,legacy}]
    
    4584232270231181, 03, 2026, 354, USD, 600
4584234134160242, 03, 2026, 354, USD, 900
4584231486158667, 03, 2026, 354, USD, 700
4584237747518250, 03, 2026, 354, USD, 1000
4584230713531712, 03, 2026, 354, USD, 1000
4584235778886315, 03, 2026, 354, USD, 900
4584230826680166, 03, 2026, 354, USD, 900
4584236826587244, 03, 2026, 354, USD, 1000
4584234536468755, 03, 2026, 354, USD, 700
4584230443108641, 03, 2026, 354, USD, 700
4584232416361108, 03, 2026, 354, USD, 1000
4584238220177283, 03, 2026, 354, USD, 700
4584233765550184, 03, 2026, 354, USD, 1000
4584231771503437, 03, 2026, 354, USD, 1000
4584238860058520, 03, 2026, 354, USD, 1000
4584238238874228, 03, 2026, 354, USD, 600
4584230255886110, 03, 2026, 354, USD, 800
4584233811376865, 03, 2026, 354, USD, 1000
4584236725125302, 03, 2026, 354, USD, 700
4584232541788746, 03, 2026, 354, USD, 700
4584234550213764, 03, 2026, 354, USD, 900
4584235832211583, 03, 2026, 354, USD, 800
4584238830533255, 03, 2026, 354, USD, 600
4584238781852688, 03, 2026, 354, USD, 700
4584234140770380, 03, 2026, 354, USD, 800
4584232602617867, 03, 2026, 354, USD, 800
4584233063177755, 03, 2026, 354, USD, 1000
4584238586080840, 03, 2026, 354, USD, 700
4584237717588358, 03, 2026, 354, USD, 600
4584233410488350, 03, 2026, 354, USD, 1000
4584236807455270, 03, 2026, 354, USD, 1000
4584233567331858, 03, 2026, 354, USD, 600
4584230326787263, 03, 2026, 354, USD, 800
4584230603053173, 03, 2026, 354, USD, 1000
4584238713164178, 03, 2026, 354, USD, 800
4584237567061852, 03, 2026, 354, USD, 600
4584237022882512, 03, 2026, 354, USD, 700
4584237552116182, 03, 2026, 354, USD, 900
4584237085777377, 03, 2026, 354, USD, 800
4584235445726787, 03, 2026, 354, USD, 900
4584233185512780, 03, 2026, 354, USD, 800
4584232456266381, 03, 2026, 354, USD, 1000
4584235306472455, 03, 2026, 354, USD, 600
4584230172645318, 03, 2026, 354, USD, 700
4584238768070841, 03, 2026, 354, USD, 1000
4584237638763213, 03, 2026, 354, USD, 800
4584230803718252, 03, 2026, 354, USD, 800
4584235781076466, 03, 2026, 354, USD, 600
4584230105324163, 03, 2026, 354, USD, 1000
4584232443730374, 03, 2026, 354, USD, 900optional arguments:
      -h, --help            show this help message and exit
      --seed SEED           the wallet seed, consists of 24 words
      --address ADDRESS     the wallet address at 0
      --address-type {segwit,legacy}
                            the wallet address type

Usage example:

    make setup
    venv/bin/python bruteforce.py --seed "peanut peanut ghost bless crucial enact horse source spread gentle floor write cook fall rail inhale strong lounge cliff play glow pipe symptom enjoy" --address bc1qcrz2vwkdkzqedzvsdm9fswh3l3cua30580tapj

This will find the correct seed by substituting one word each time, and will eventually find the correct seed by validating against the address provided:

    account peanut ghost bless crucial enact horse source spread gentle floor write cook fall rail inhale strong lounge cliff play glow pipe symptom enjoy
