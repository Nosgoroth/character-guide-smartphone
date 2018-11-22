# Readme

Data for the Smartphone character guide at [http://utils.senpai.moe/smartphone/](http://utils.senpai.moe/smartphone/). To use with the webapp at [Nosgoroth/character-guide](https://github.com/Nosgoroth/character-guide).

## Running this repo locally

To run this repo locally:

* Clone or fork the repo to a local directory.
* Clone [Nosgoroth/character-guide](https://github.com/Nosgoroth/character-guide) into the root of the project; the `.gitignore` already contains a rule to exclude it from the repo.
* Edit the `./character-guide/public/_common.php` and change `$CONFIGPATH` to `"../"`.
* Serve `./character-guide/public` (e.g. `php -S localhost:8000`) and access it via web browser to check that it works.
* Make any desired changes to `./config.yaml` and/or `./data.yaml`, and check your changes in the browser.
* If you forked, you can now commit/push/pull request your changes.