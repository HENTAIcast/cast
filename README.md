# cast
@@ -17,7 +17,7 @@ jobs:

    strategy:
      matrix:
        rust: ['stable', 'nightly', '1.70.0']
        rust: ['stable', 'nightly', '1.74.0']

    steps:
      - uses: actions/checkout@v2

-----
