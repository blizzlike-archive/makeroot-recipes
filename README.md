# makeroot recipes

a collection of recipes to setup a wow server infrastructure.

## images

prepare your environment

    git clone https://metagit.org/fnordpipe/makeroot.git
    git clone https://metagit.org/blizzlike/makeroot-recipes.git

    cd makeroot

### devenv

provides a devenv for all blizzlike activities

    make \
      RECIPE_DIRS="./recipes/* ../makeroot-recipes/recipes/*" \
      USEGIT=1 USEBINPKG=1 \
      blizzlike-devenv

### stage3

provides a stage3 tarbal for general purposes.

    make \
      RECIPE_DIRS="./recipes/* ../makeroot-recipes/recipes/*" \
      USEGIT=1 USEBINPKG=1 \
      blizzlike-stage3
