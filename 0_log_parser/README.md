To generate the `davinci_output.dat` file to parse:
1. Clone my fork of `DaVinci_TTracks` (oops, it's private. I honestly don't know how to change that).
2. Checkout to branch `TTrackPhys_v45r3_DebugFailedConvergence`.
3. Compile with `make`.
4. Run with something like
```
${DIRECTORY_WHERE_TTRACK_WAS_CLONED}/run gaudirun.py davinci_opt.py |& tee davinci_output.dat
```

(Memo: add `davinci_opt.py` to the repository.)
