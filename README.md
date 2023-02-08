# reMarkable Scripts

My own personal collection of scripts to work with my reMarkable tablet.

They basically solve my problem of not having access to the reMarkable cloud and
having to do everything locally.

# Dependencies

## Both

- ssh (optimally with a ssh-config entry)

## For pulling/rendering side

### Format: v6

- python-rm2pdf

### Format: v5

- python-rmrl

## For pushing side

- uuidgen
- imagemagick

# Acknowledgements

The "push" script `pdf2remarkable` is heavily inspired by the work Adrian Daerr
did in his comparable repo [here](https://github.com/adaerr/reMarkableScripts)
