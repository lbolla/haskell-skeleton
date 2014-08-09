## Setup

    $> cabal sandbox init

## Run main

    $> cabal install --only-deps
    $> cabal run

## Tests:

    $> cabal configure --enable-tests
    $> cabal install --only-dep --enable-tests
    $> cabal test

## Benchmarks:

    $> cabal configure --enable-benchmarks
    $> cabal install --only-dep --enable-benchmarks
    $> cabal bench --benchmark-options="--output bench.html"
