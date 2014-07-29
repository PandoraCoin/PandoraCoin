PandoraCoin (PDC)

http://www.pandoracoin.org - not yet establish
What is PandoraCoin?

PandoraCoin is a lite version of Bitcoin using scrypt as a proof-of-work algorithm.

    2 minute block targets
    subsidy halves in 250k blocks
    25 million total coins

The rest is the same as Bitcoin.

    50 coins per block
    720 blocks to re-target difficulty (about 1day)

Automated Testing

Developers are strongly encouraged to write unit tests for new code, and to submit new unit tests for old code.

Unit tests for the core code are in src/test/. To compile and run them:

cd src; make -f makefile.unix test

Unit tests for the GUI code are in src/qt/test/. To compile and run them:

qmake BITCOIN_QT_TEST=1 -o Makefile.test bitcoin-qt.pro
make -f Makefile.test
./pandoracoin-qt_test
