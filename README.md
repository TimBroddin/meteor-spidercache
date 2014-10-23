# spidercache
It's like Spiderable, but it caches

## Spidercache vs Spiderable

- Caches the output (24 hours default)
- Stores hits/misses in a collection
- Will output what phantomjs received after timeout (because sometimes the ready event doesn't fire)

## Usage

- Install phantomjs
- Install this package
- Boom!

## Configuration

    {
        spidercache: {
            expiration: 86400 // cache expiration in seconds
        }
    }

Enjoy!
