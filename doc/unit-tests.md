Compiling/running unit tests
------------------------------------

Unit tests will be automatically compiled if dependencies were met in configure
and tests weren't explicitly disabled.

After configuring, they can be run with 'make check'.

To run the criptopesod tests manually, launch src/test/test_criptopeso .

To add more criptopesod tests, add `BOOST_AUTO_TEST_CASE` functions to the existing
.cpp files in the test/ directory or add new .cpp files that
implement new BOOST_AUTO_TEST_SUITE sections.

To run the criptopeso-qt tests manually, launch src/qt/test/criptopeso-qt_test

To add more criptopeso-qt tests, add them to the `src/qt/test/` directory and
the `src/qt/test/test_main.cpp` file.
