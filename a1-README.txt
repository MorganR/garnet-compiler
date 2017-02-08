Group account: CISC458k

Students:
	Derek Shum, Student Number: 10073643, Net ID: 12ds27
	Michael Dulberg, Student Number: 10053956, Net ID: 11mjd21
	Morgan Roff, Student Number: 10044329, Net ID: 11mr60
	
All test files are in tests/scan-screen/. 'tests/' sits level with 'ptsrc/'.
Tests can be run by navigating to tests/scan-screen/ and running ./TestAll.
All tests compare their .exp (expected output) against the -e output found in the .rese files.
Tests can optionally compare against .resi (-i output) if appropriate, such as to look for illegal characters, by creating a .testi file which echos either "pass" or "fail".
