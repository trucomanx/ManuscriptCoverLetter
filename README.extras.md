# manuscript-cover-letter

Program to generate manuscript cover letters.

## Testar program

```bash
cd src
python3 -m manuscript_cover_letter.program
```

## Upload to PYPI

```bash
pip install --upgrade pkginfo twine packaging

cd src
python -m build
twine upload dist/*
```

## Install from PYPI

The homepage in pipy is https://pypi.org/project/manuscript-cover-letter/

```bash
pip install --upgrade manuscript-cover-letter
```

Using:

```bash
manuscript-cover-letter
```

## Install from source
Installing `manuscript-cover-letter` program

```bash
git clone https://github.com/trucomanx/ManuscriptCoverLetter.git
cd ManuscriptCoverLetter
pip install -r requirements.txt
cd src
python3 setup.py sdist
pip install dist/manuscript_cover_letter-*.tar.gz
```
Using:

```bash
manuscript-cover-letter
```

## Uninstall

```bash
pip uninstall manuscript_cover_letter
```
