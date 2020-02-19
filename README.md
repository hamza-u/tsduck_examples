# tsduck_examples
Few example use cases of TsDuck

## Unicast to multi-cast
tsp -I ip 23456 -O ip -l 127.0.0.1 224.2.2.2:23456

## Stream MPEG-TS file infinitely
tsp -I file -i file.ts -P regulate -O ip 127.0.0.1:6870
