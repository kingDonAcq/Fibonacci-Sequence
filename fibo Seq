#include <iostream>
#include <vector>

void fiboSequence(int);

int main() {

		int requiredTerm;
		
		std::cout << "<------------------ PROGRAM TO PRRINT FIBONACCI'S SEQUENCE TO A SPECIFIED TERM ----------------->" << std::endl;
		std::cout << "Enter your preffered term: ";
		std::cin >> requiredTerm;

		fiboSequence(requiredTerm);

	return 0;
}

void fiboSequence(int nums) {
	std::vector<int>fibonacciSequence;
	int tempResult;

	for (int i = 0; i < nums + 1; i++) {
		if (i > 1) {
			tempResult = fibonacciSequence[i - 1] + fibonacciSequence[i - 2];
			fibonacciSequence.push_back(tempResult);
		}
		else {
			fibonacciSequence.push_back(i);
		}

	}

	std::cout << "The Fibonacci Sequence to the " << nums << " th term are: ";

	for (int x = 0; x < nums + 1; x++) {
		std::cout << fibonacciSequence[x] << "  ";
	}

	std::cout << std::endl;
}
