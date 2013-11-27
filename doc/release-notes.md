(note: this is a temporary file, to be added-to by anybody, and deleted at
release time)

0.8.6 changes
=============

- Default block size increase for miners
  (see https://gist.github.com/gavinandresen/7670433#086-accept-into-block)

- Remove the all-outputs-must-be-greater-than-CENT-to-qualify-as-free rule for relaying
  (see https://gist.github.com/gavinandresen/7670433#086-relaying)

- Lower maximum size for free transaction creation
  (see https://gist.github.com/gavinandresen/7670433#086-wallet)

- Network code performance and robustness improvements

- Additional debug.log logging for diagnosis of network problems, log timestamps by default

- Update leveldb to 1.13 and other OSX block chain database corruption fixes

- Fix Bitcoin-Qt startup crash when clicking dock icon on OSX 

