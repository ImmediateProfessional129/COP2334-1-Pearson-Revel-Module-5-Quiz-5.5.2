# COP2334-1-Pearson-Revel-Module-5-Quiz-5.5.2
This is a repository link of the COP2334-1 Pearson Module 5 Revel Quiz 5.5.2

// This program is designed to calculate the distance a robot went in difficult territories.

// Include the iostream library
#include <iostream>
using namespace std;
int main() {
// Declare the variables
  int distance = 0;
  int totalDistance = 0;
  char option;
  do {
    // Prompt the user to enter the distance
    cout << "Enter the distance traveled: ";
    cin >> distance;
    // Calculate the total distance
    totalDistance += distance;
    cout << "Total distance traveled: " << totalDistance << endl;
    // Prompt the user to continue or exit
    cout << "Do you want to calculate more distance? (y/n): ";
    cin >> option;
    // Check if the user wants to continue
  } while (option == 'y' || option == 'Y');
  return 0;
}
