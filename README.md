# 6D-Advanced-
6D Advanced🔺
additional header files: The code now includes the <fstream>, <memory>, <thread>, <chrono>, and <sstream> header files to provide functionalities for file input/output operations, smart pointers, multi-threading, timing, and string stream operations.

File I/O functions: The code includes two new functions, saveEncryptedMessage and loadEncryptedMessage, which allow saving the encrypted message to a file and loading the encrypted message from a file, respectively. These functions use file streams (std::ofstream and std::ifstream) to write and read the encrypted message data.

Time delay simulation: After encrypting the message, the code simulates a time delay using std::this_thread::sleep_for to introduce a pause before loading the encrypted message from the file. This demonstrates the delay between encryption and decryption.

Updated main function: The main function now includes the steps to save the encrypted message to a file, load the encrypted message from the file, and decrypt the loaded message using the 6D lattice symbols. It also prints the encrypted message as a string of Unicode code points.

These improvements enhance the functionality of the code by introducing file I/O operations, simulating time delays, and providing more comprehensive encryption and decryption capabilities.
