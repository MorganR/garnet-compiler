Group account: CISC458k

Students:
	Derek Shum, Student Number: , Net ID:
	Michael Dulberg, Student Number: , Net ID:
	Morgan Roff, Student Number: 10044329, Net ID: 11mr60
	
All test files are in tests/scan-screen/. 'tests/' sits level with 'ptsrc/'.
Tests can be run by navigating to tests/scan-screen/ and running ./TestAll.
All tests compare their .exp (expected output) against the -e output found in the .rese files.
Tests can optionally compare against .resi (-i output) if appropriate, such as to look for illegal characters, by creating a .testi file which echos either "pass" or "fail".
Tests can also optionally contain an additional custom test script as a .testo file, which should again echo "pass" or "fail" as appropriate. 

Diff files showing all changes can be found here as Parser-pt-Diff-File.txt, Scan-SSL-Diff-File.txt, and stdIdentifiers-Diff-File.txt.
