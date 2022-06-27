# CS300DSA

int main(int argc, char* argv[]) {

    // process command line arguments
    string csvPath;
    switch (argc) {
    case 1:
        csvPath = argv[1];
        break;
    default:
        csvPath = "course_Information.csv";
    }

    // Define a vector to hold all the prerequisites
    vector<Prerequisites> prerequisites;

void printSampleSchedule(Prerequisites prerequisites) {
    cout << prerequisites.prerequisitesId << prerequisites.courseName << prerequisites.courseNumber << endl;
    return;
}
    
    // Define a hash table to hold all the prerequisites
    HashTable* prerequisitesTable;

    Prerequisites prerequisites;
    prerequisitesTable = new HashTable();

void printSampleSchedule(Prerequisites prerequisites) {
              cout << Node* prerequisites.prerequisitesId << ": " << Node* prerequisites.courseName << " | " << Node* prerequisites.courseNumber << endl;

    return;
}

    // Define a binary search tree to hold all prerequisites
    BinarySearchTree* bst;
    bst = new BinarySearchTree();
    Prerequisites prerequisites;

    void printSampleSchedule(Prerequisites prerequisites) {
    cout << prerequisites.prerequisitesId << prerequisites.courseName << prerequisites.courseNumber << endl;
    return;
}

    

    int choice = 0;
    while (choice != 9) {
        cout << "Menu:" << endl;
        cout << "  1. Load Course List" << endl;
        cout << "  2. Display All Courses" << endl;
        cout << "  3. Find Courses" << endl;
        cout << "  4. View Prerequisites" << endl;
        cout << "  9. Exit" << endl;
        cout << "Enter choice: ";
        cin >> choice;

        switch (choice) {

        case 1:
            
            // Initialize a timer variable before loading course information list
            courseInformation = courseInformationList();

           
            // Complete the method call to load the course Information
            courseInformation = loadCourseInformation(csvPath);

            cout << courseInformation.size() << " Course List read" << endl;

            // Calculate course Information and display result
            courseInformation = courseInformationList() - courseInformation; 
            cout << "Course List: " << courseInformation<< endl;
            cout << "Course List: " << prerequsites << endl;

            break;

        case 2:
            // Loop and display the course information read
            for (int i = 0; i < courseInformation.size(); ++i) {
                displayPrerequisites(courseInformationList[i]);
            }
            cout << endl;

            break;
    cout << "EXIT" << endl;

    return 0;
}


In my analysis, I think that all the structures we used to access course information and the course prerequisites all did the same task. Each structure implemented and initialized each structure to hold prerequisites. The advantage to this, is you can use multiple different ways to locate course information and course prerequisites. I think when it comes to efficiency and speed, the hash table would be the best structure to use to lower run time and to save on memory. I think the disadvantage to the other structures is the process of having to locate the course information. Vectors are a great way to store the course information and to print the course list and prerequisites, but there are steps you must take, such as calling each line of code to locate the course information. Binary Search Trees, require a lot of allocation to moving nodes to the left and right if the node with the current course information isn’t found. To me, this means that it will be a lot of working of locating nodes that could be empty and having to start the loop again to call another location for the course information. 

What was the problem you were solving in the projects for this course?

The problem I was solving in the projects for this course centered around creating a list to hold course requirements with the intent to print the list in numerical order and also to allow users to have the abiiity to access course prerequisites.

How did you approach the problem? Consider why data structures are important to understand.

The way I approached the problem, was by first understanding what the end result is for the problem, which was to print the course schedule by coruse number. I then was able to work backwards and decide what I needed to do which was to create a list that would hold the information, but also to recoginze that if the correct course isnt chosen to display the numerical order of courses that it would be to output an error. I think data structures are important because data structures all differ in one way or another, meaning vectors may seem like a good choice to locate a course, but a hash table or binary search tree may be more functional and may take up less space/memory. 

How did you overcome any roadblocks you encountered while going through the activities or project?

I thhink the best way I overcame my obstacles were communicating with my instructor, but also forcing myself to overcome the mental obstacles of fearing I didnt know what I was doing. Taking my time, reading the documentation and utilizing the text were tools I used that resulted in helping me overcome the activities and projects this term. 

How has your work on this project expanded your approach to designing software and developing programs?

Working on this project did give me more confidence in seeing how much I am able to build and that with more work, I could easily design and develop working software. This project was a great addition to learning more C++ in depth. 

How has your work on this project evolved the way you write programs that are maintainable, readable, and adaptable?

Working on this project did allow me to understand how important clear and precise readable and adaptable programming should be. The intext comments in these projects allowed me to correlate alot of things that hadnt in previouos classes. Which means that it was easy enough for me to understand, but also clear enough for me to know what I should be executing and how it can be maintained by the next programmer. 
