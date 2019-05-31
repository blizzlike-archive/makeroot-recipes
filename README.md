# makeroot recipes

a collection of recipes to setup a wow server infrastructure.

## images

### devenv

provides a devenv for all blizzlike activities

    git clone https://metagit.org/fnordpipe/makeroot.git
    git clone https://metagit.org/blizzlike/makeroot-recipes.git

    cd makeroot

    make \
      RECIPE_DIRS="./recipes/* ../makeroot-recipes/recipes/*" \
      USEGIT=1 USEBINPKG=1 \
      blizzlike-devenv
