install:
	poetry install

try:
	poetry run try

say-hello:
	@echo "Hello, World!"

build:
	poetry build

lint:
	poetry run flake8 brain_games

publish:
	poetry publish --dry-run

package-install:
	pip install --user --force-reinstall dist/*.whl

.PHONY: install build brain-games
