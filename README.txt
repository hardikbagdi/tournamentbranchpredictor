The makefile handles all commands.
To run:

make < input_file > output_file


(or alternatively,  
javac TournamentBranchPredictor.java
java  TournamentBranchPredictor < input_file > output_file )


and then

diff --ignore-all-space output_file ref_output

Programmed in Java.
Reads from STDIN and Writes to STDOUT.
The output_file can be compared against reference directly.
Uncomment last 4 lines in the TournamentBranchPredictor.java to obtain benchmarks(Problem 1.3).