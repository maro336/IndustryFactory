/// Requirements ///
1. New User input form -> Pushes data to an array 
2. User list display.
3. User Training status. 
    Requires two arrays 
    General (Business Values Assessment)
    1. Vision
    2. Mission 
    3. Values
    4. Strategy
    5. Systems (Lean Competency )
    6. Cultural Maturity 
    7. Battlefield to Brilliance

        3a. 
        Each of these has to have a subarray, which will record 
        a score for each area of assessment. There will be a function 
        to update assessment, this will push the values to the array. 
        It can also have a nested function to take an average
        (or other calculating method) to create an overall/progress
        rank for each assessment criteria. 


Ultimately, these could have training courses with video content
or questionaire/exams. These could be entered to review (if they are in 
the form of responses to questions), or submit a pass/fail for that criteria
there could also be an ability to add notes/comments, which get stored on the 
file and are able to be reviewed. 

There could be a student login where students can go to access certificates and/or resources
via download or even video content if it were made. Book lists, educational videos, etc. 
access to contacts for employment resources, etc.

There could also be a login for clients to view training profiles for students and across the board 
And support for "groups" or "teams" which could be customised by the client. 
IE: Management Staff, Factory Staff, Paint, Assembly.
Reports could then be generated in a Pi chart style
Or as a graph/grid. 

--- What is the best way to store trainee records? 

Could it be best to use a single Object/Array, with an Trainee ID 

For example 

const traineeObject = {

    traineeId: 1,
    personalDetails: [
        firstName: "Mason";
        lastName: "Robb";
        gender: 'male';
        dateOfBirth: [10,09,1995];
        position: "Factory Worker";
    ],













}


