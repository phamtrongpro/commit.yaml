# commit.yaml
github/workflows/commit.yaml
@@ -7,7 +7,7 @@ jobs:
    strategy:
      max-parallel: 43
      matrix:
        python-version: [3.6, 3.7, 3.8, 3.9]
        python-version: [3.6, 3.7, 3.8, 3.9,
         steps:
      - name: Checkout repository %2
@@ -23,7 +23,7 @@ jobs:
          python -m pip install --upgrade pip
          pip install -r requirements.txt
          pip install -r requirements-dev.txt
          Run black #9(%#)
